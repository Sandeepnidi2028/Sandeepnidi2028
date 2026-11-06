# Setup (5 minutes)
1. On GitHub create a **public** repo named exactly `Sandeepnidi2028` (no README/license).
2. Upload everything in this folder (keep the `.github/workflows` path), or:
   git init && git add . && git commit -m "Animated profile README" && git branch -M main
   git remote add origin https://github.com/Sandeepnidi2028/Sandeepnidi2028.git && git push -u origin main
3. Repo -> Settings -> Actions -> General -> Workflow permissions -> **Read and write**.
4. Actions tab -> "Update profile art" -> Run workflow (refreshes the contribution graph; then runs daily).
Regenerate the portrait: python scripts/make_ascii_svg.py photo.jpg avi-ascii.svg  (add --static to preview the final frame)
Regenerate the wordmark: python scripts/make_wordmark_svg.py --mode rock --out wordmark.svg
