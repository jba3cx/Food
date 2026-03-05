# 🍽️ Food Order Suggester

A collaborative website to help your team decide where to order food each day.

## Features

- **Multi-User Support**: Anyone can join with just a username (no login required)
- **Add Restaurants**: Each person builds their own list of places to order from
- **Like/Dislike**: Mark each restaurant as liked, disliked, or neutral
- **Daily Voting**: Vote each day whether you'll be ordering
- **Smart Suggestions**: Get a daily suggestion based on ALL team members' preferences (only counting those voting "Yes")
- **No Backend Needed**: All data stored in browser local storage

## How to Use

### 1. Login with Your Name
- Enter your username (no password needed!)
- You'll see your own preferences and voting panel

### 2. Add Your Favorite Restaurants
- Type a restaurant name and click "Add"
- Add as many as you want to your list

### 3. Set Your Preferences
- Click the ❤️ **Like** button to mark a restaurant as a favorite
- Click the 👎 **Dislike** button to mark one you don't prefer
- Click again to toggle off

### 4. Vote Daily
- Click **"Yes, I'm In!"** if you'll be ordering today
- Click **"No, Not Today"** if you're not participating
- See in real-time how many people are voting yes

### 5. Get a Team Suggestion
- Click **"Get Suggestion"** to get a recommendation
- The algorithm considers:
  - All restaurants from people voting "Yes"
  - Likes (higher priority)
  - Dislikes (lower priority) 
  - Neutral votes (good for variety)
  - A bit of randomness (keeps it fun!)

### 6. Reset for Tomorrow
- Your votes automatically reset each day at midnight
- Or click **"Reset for Tomorrow"** to start fresh

## Multi-User Setup

Since everyone uses the same browser/device, each person can:
1. Log out (top right button)
2. Log in with their own name
3. Add their preferences
4. Vote

Everyone's votes combine into one daily suggestion!

## Upload to GitHub

1. **Create a new repository on GitHub**
   - Go to [github.com](https://github.com)
   - Click the **+** icon in the top right → **New repository**
   - Name it (e.g., `food-order-suggester`)
   - Click **Create repository**

2. **Upload your files**
   - On the repo page, click **uploading an existing file**
   - Drag and drop these files:
     - `index.html`
     - `README.md`
     - `.gitignore`
   - Click **Commit changes**

3. **Enable GitHub Pages (to make it live)**
   - Go to **Settings** (top of repo page)
   - Scroll to **Pages** on the left sidebar
   - Under "Branch", select **main**
   - Click **Save**
   - Wait ~1 minute for the build

4. **Done!** 
   - Your site will be live at: `https://YOUR_USERNAME.github.io/REPO_NAME/`
   - Share the link with your team!

## Notes

- Each person needs to visit the site on the same device and enter their name
- For a distributed team across devices, you'd need a backend database (future enhancement!)
- Data persists until browser storage is cleared
- Voting resets automatically each day at midnight

## Future Enhancements

- Shared backend for team across different devices
- Restaurant history and ratings
- Multiple workspace support
- Import/export preferences
- Dark mode
