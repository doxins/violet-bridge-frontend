# Sync Bridge Frontend

Web interface for configuring Roblox script settings.

## Setup

1. **Update Backend URL**
   - Open `index.html`
   - Find line: `const BACKEND_URL = 'https://your-backend.onrender.com';`
   - Replace with your deployed backend URL

2. **Deploy to Vercel**
   - Create account at [vercel.com](https://vercel.com)
   - Click "Add New Project" → "Import"
   - Upload or connect this folder
   - Deploy and copy the URL

## Usage

1. Deploy the backend first
2. Update the `BACKEND_URL` in index.html
3. Deploy the frontend
4. Run the Roblox script - it will generate a URL with your key
5. Open that URL to access the settings panel

## Local Testing

Simply open `index.html` in a browser with `?key=test123` appended to the URL.
