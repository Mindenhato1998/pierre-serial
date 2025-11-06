# Pierre Serial Viewer - Live MQTT Monitor

## 🚀 Quick Deploy Options

### Option 1: Netlify Drop (Easiest - 10 seconds)
1. Go to: https://app.netlify.com/drop
2. Drag the `index.html` file onto the page
3. You'll get an instant URL like: `https://amazing-site-123.netlify.app`
4. That's it! The URL is permanent and free.

### Option 2: Vercel (Also very easy)
1. Go to: https://vercel.com
2. Sign up with GitHub or email
3. Click "Add New" → "Project"
4. Click "Continue with CLI/Third Party"
5. Upload the `index.html` file
6. Deploy → You'll get a URL

### Option 3: GitHub Pages
1. Create a new GitHub repository
2. Upload this entire folder
3. Go to Settings → Pages
4. Enable GitHub Pages
5. Your URL will be: `https://yourusername.github.io/repository-name`

### Option 4: Cloudflare Pages
1. Go to: https://pages.cloudflare.com
2. Create a project
3. Upload the `index.html` file
4. Get your URL

## 📱 How It Works

1. The Android app publishes serial data to HiveMQ Cloud
2. This web page connects to HiveMQ via WebSocket
3. Anyone with the share link can view live serial logs
4. No server needed - HiveMQ handles everything!

## 🔗 Share URL Format

After deploying, your share URLs will look like:
```
https://your-site.netlify.app?device=abc123&session=xyz789
```

## 🔒 Security

- SSL/TLS encrypted connection
- Read-only access (viewers can't send commands)
- Session IDs expire when Android app closes

---

**Deploy this NOW with Netlify Drop - it takes literally 10 seconds!**