# Sri Rama Navami Head Count Tracker

A simple, elegant web application for tracking apartment participation and head count for Sri Rama Navami celebrations.

## Features

✅ Real-time head count tracking (Adults & Kids)
✅ Duplicate flat number prevention
✅ Live statistics dashboard
✅ Mobile-friendly responsive design
✅ Beautiful gradient UI
✅ No backend required (all data stored locally)

## How to Deploy on Vercel

### Step 1: Create GitHub Account (if you don't have one)
- Go to https://github.com/signup
- Complete the signup process

### Step 2: Upload to GitHub

1. Go to https://github.com/new
2. Create a new repository named `rama-navami-tracker`
3. Click **Add files** → **Upload files**
4. Upload these 3 files:
   - `index.html`
   - `vercel.json`
   - `README.md` (this file)
5. Click **Commit changes**

### Step 3: Deploy to Vercel

1. Go to https://vercel.com
2. Click **Sign Up** → Choose **GitHub**
3. Authorize Vercel to access GitHub
4. Click **Import Project**
5. Select `rama-navami-tracker` repository
6. Click **Deploy**
7. Wait 30 seconds...
8. You'll get a live URL like: `https://rama-navami-tracker-abc123.vercel.app`

### Step 4: Share Your Link!

Copy your live URL and share in WhatsApp:

```
🙏 Sri Rama Navami Celebration - Head Count 🙏

Please fill this form to confirm participation:
https://your-vercel-url-here.vercel.app

Takes < 1 minute! 🙏
```

## Features

- **Name**: Participant name
- **Flat Number**: Building flat (duplicate prevention)
- **Adults**: Number of adults attending
- **Kids**: Number of children attending

## Real-Time Tracking

The dashboard shows:
- Total flats registered
- Total adults
- Total kids
- Total members count
- Progress vs. 130 member target

## Data Storage

All responses are stored in the browser (no server needed). 
To export: Open browser DevTools → Console → Type: `copy(JSON.stringify(allResponses))`

## Support

For questions or customizations, edit `index.html` directly.

---

Happy celebrating! 🙏
