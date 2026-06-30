# Portfolio auto-refresh

The Social Media gallery is data-driven from `C:\Users\Rishabh\Desktop\harsh\Social media work`.
To add new creatives: drop image files into that folder, then ask Cowork to
"refresh the portfolio". The pipeline will:
 1. Scan the folder for all images (no hardcoding).
 2. Generate optimized web (1080px) + thumbnail (700px) versions into assets/portfolio/social/.
 3. Rebuild the manifest (platform / category / industry) and re-embed window.DD_SOCIAL.
 4. Re-inline index.html and portfolio.html.

Website hero previews: drop a screenshot named <slug>.jpg into a `web/` folder
(e.g. vasoo-bamboo-arts.jpg) and it will replace the branded preview automatically.
