# Setting Up GitHub Pages for Your AI Gift

This guide walks you through hosting the landing page and ZIP download on GitHub Pages.

## Step 1: Create a New GitHub Repository

1. Go to [github.com/new](https://github.com/new)
2. Repository name: `yourai` (or `your-ai` — GitHub will handle the URL)
3. Description: "Your Private AI — a locally-run intelligence that belongs to you"
4. Choose **Public** (so the landing page is accessible)
5. Click **Create repository**

## Step 2: Push Your Files to GitHub

Open Terminal and run these commands from the folder containing this SETUP_GITHUB.md file:

```bash
# Initialize git (one time)
git init

# Add all files
git add .

# Create your first commit
git commit -m "Initial commit: Your AI landing page and starter kit"

# Connect to GitHub (replace USERNAME with your GitHub username)
# Repository name = yourai or your-ai, whatever you chose in Step 1
git remote add origin https://github.com/USERNAME/yourai.git

# Push to GitHub
git branch -M main
git push -u origin main
```

## Step 3: Enable GitHub Pages

1. Go to your repository on GitHub (github.com/USERNAME/yourai)
2. Click **Settings** (top right)
3. Scroll down to **Pages** (left sidebar)
4. Under "Source", select **Deploy from a branch**
5. Select branch: **main**
6. Select folder: **/ (root)**
7. Click **Save**

GitHub will show you the live URL. It typically appears as:
- `https://USERNAME.github.io/yourai/` (if repo is called "yourai")
- `https://USERNAME.github.io/your-ai/` (if repo is called "your-ai")

Wait 1-2 minutes for the site to deploy.

## Step 4: Test Your Landing Page

Open the URL from Step 3 in your browser. You should see:
- Your AI landing page with the download button
- The download button should work and deliver `YourAI_StarterKit.zip`

## Step 5: Update the Gift Card PDF

Once you have your final GitHub Pages URL, the gift card PDF can be updated with that URL printed on the front page (as requested — text only, not a hyperlink).

Provide the URL and I'll regenerate the gift card with it included.

---

## Notes

- GitHub Pages is **free** and **always on**
- Your AI landing page is now permanently hosted
- The ZIP file stays with the repository (no additional hosting needed)
- You can update the files anytime by pushing new commits to GitHub
- The landing page is public and searchable — perfect for sharing with others who want their own private AI
