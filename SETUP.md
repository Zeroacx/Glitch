# ZEROACX profile setup

1. Open your `Zeroacx/Zeroacx` profile repository.
2. Upload everything from this package to the repository root.
3. Commit and push.
4. Open the profile README.
5. Go to **Actions → Update profile graphics → Run workflow** once.
6. After that, the workflow refreshes the contribution SVG daily.

No Python packages are required.

For local testing:
```bash
python3 scripts/render_heatmap_svg.py
```

The initial `contrib-heatmap.svg` is a visual demo. The GitHub Action replaces it with your contribution data.
