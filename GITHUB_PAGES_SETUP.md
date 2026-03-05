# GitHub Pages Setup Instructions

## Configure GitHub Pages for Your JellyFish Lighting Website

Your website files have been successfully pushed to GitHub. Now you need to enable GitHub Pages to make your site live.

### Step-by-Step Instructions:

1. **Open your repository in browser:**
   Visit: https://github.com/Whitehurst87/jellyfish-lighting

2. **Go to Settings:**
   Click on the "Settings" tab in your repository (you may need to click "..." to find it)

3. **Find GitHub Pages section:**
   In the left sidebar, scroll down and click on "Pages"

4. **Configure source:**
   - Under "Source", select "Deploy from a branch"
   - Select "main" or "master" branch (whichever appears)
   - Click "Save"

5. **Wait for deployment:**
   - GitHub will process your site (this may take 2-5 minutes)
   - You'll see a success message when it's ready

6. **Access your live site:**
   Once deployed, you'll see a URL like:
   `https://whitehurst87.github.io/jellyfish-lighting/`

### Alternative: Rename branch to 'main'

If you prefer to use the 'main' branch (recommended), you can:

1. **Rename your branch:**
   ```bash
   git branch -m master main
   git push -u origin main
   ```

2. **Update GitHub Pages source:**
   - Go back to Settings > Pages
   - Change source to "main" branch
   - Save changes

### Verification

After GitHub Pages is configured:
- Visit your live site URL
- Test all functionality (slideshow, contact form, mobile responsiveness)
- Verify images load correctly
- Check that the navigation works properly

### Troubleshooting

- **Site not loading?** Wait 5-10 minutes for GitHub to process
- **Images not showing?** Ensure they're in the correct path
- **Need help?** Check GitHub Pages documentation: https://docs.github.com/en/pages

---

Your JellyFish Lighting website will be live and accessible to customers once GitHub Pages is enabled!