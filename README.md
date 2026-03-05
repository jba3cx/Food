# 🍽️ Food Order Suggester

A simple, collaborative website to help your team decide where to order food each day.

## Features

- **Add Restaurants**: Build a list of places your team likes to order from
- **Like/Dislike**: Mark each restaurant as liked, disliked, or neutral
- **Daily Voting**: Vote whether you'll be ordering today
- **Smart Suggestions**: Get a daily suggestion based on team preferences of people ordering
- **Local Storage**: All data persists in your browser (no server needed)

## How to Use

### 1. Add Restaurants
- Type a restaurant name and click "Add"
- You can add as many as you want

### 2. Set Your Preferences
- Click the ❤️ **Like** button to mark a restaurant as a favorite
- Click the 👎 **Dislike** button to mark one you don't prefer
- Click again to toggle off

### 3. Vote Daily
- Click **"Yes, I'm In!"** if you'll be ordering today
- Click **"No, Not Today"** if you're not participating
- Your vote resets automatically each day

### 4. Get a Suggestion
- Click **"Get Suggestion"** to get a recommendation
- The algorithm considers:
  - Places you like (higher priority)
  - Places you've marked neutral (good for variety)
  - Randomness (keeps it fun!)

### 5. Reset for Tomorrow
- Click **"Reset for Tomorrow"** to clear votes and prepare for the next day

## Upload to GitHub

1. **Initialize a Git Repository**
   ```bash
   git init
   ```

2. **Add Files**
   ```bash
   git add .
   ```

3. **Commit**
   ```bash
   git commit -m "Initial commit: Food Order Suggester"
   ```

4. **Push to GitHub**
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   git branch -M main
   git push -u origin main
   ```

5. **Enable GitHub Pages**
   - Go to your repository on GitHub
   - Navigate to **Settings** → **Pages**
   - Select **Deploy from a branch**
   - Choose **main** branch and **/(root)** folder
   - Click **Save**

Your site will be live at: `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/`

## Notes

- All data is stored in your browser's local storage
- Data is **not** shared between different people's browsers by default
- Each person needs to visit the site and add their preferences
- Perfect for small teams with shared ordering habits

## Future Enhancements

- Multi-user mode with shared voting
- Restaurant history and ratings
- Time-based preferences (Monday = pizza, Friday = something fancy)
- Import/export preferences
