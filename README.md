## Complete Website Downloader 💾
Download the complete source code of any website (including all assets) 🔨.

{
    "version": 2,
    "builds": [
        {
            "src": "./app.js",
            "use": "@vercel/node"
        }
    ],
    "routes": [
        {
            "src": "/(.*)",
            "dest": "/"
        }
    ]
}