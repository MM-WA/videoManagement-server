## Video Server - A backend service to manage videos

This is a backend for a video-sharing platform, built to handle everything from uploading videos to social features like likes, comments, and subscriptions (controllers can be tweaked).  

### Features  
- Handles user signup, login, and profiles.
- Lets users upload and manage their videos.  
- Users can like, comment, and post tweets related to videos.  
- Follow other users to stay updated with their latest content.  
- Create and manage custom playlists for personal or public viewing.  

It's built with scalability in mind and can be a solid starting point for any video-based platform.

### Setup Locally
**1.** Clone the project
```bash
git clone https://github.com/MM-WA/videoManagement-server.git
```
**2.** Move to the project directory
```bash
cd videoManagement-server
```
**3.** Install dependencies
```bash
npm install
```

### Configuration  
Before running the project create `.env` in root directry and provide following keys  
```env
PORT = 8000
MONGODB_URI =
CORS_ORIGIN = *
ACCESS_TOKEN_SECRET = 
ACCESS_TOKEN_EXPIRY = 
REFRESH_TOKEN_SECRET = 
REFRESH_TOKEN_EXPIRY = 
CLOUDINARY_CLOUD_NAME = 
CLOUDINARY_API_KEY = 
CLOUDINARY_SECRET = 
```

### Run the Server
```bash
npm run dev
```

### Author
Mian Muhammad Waleed Asif
