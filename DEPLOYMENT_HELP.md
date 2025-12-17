# How to Fix Missing Images

The images are missing from your website because the `assets` folder has not been uploaded to your hosting provider (GitHub or Vercel).

## Option 1: GitHub Web Upload
1. Go to your repository on GitHub.com.
2. Click **Add file** > **Upload files**.
3. Drag and drop the **entire `assets` folder** from your computer into the upload area.
4. Commit the changes.

## Option 2: Vercel CLI / Drag & Drop
- If using Vercel dashboard, ensure you are deploying the entire `hackvip` folder, not just the HTML file.

## Why did this happen?
The code expects to find images at `./assets/logo.jpg`, etc. If you only uploaded `index.html`, the code cannot find the images.
