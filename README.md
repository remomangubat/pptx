# Exploring Career Opportunities in Tech — Slides

## Build locally (outputs PPTX and PDF to dist/)
1. npm install
2. npm run build

PPTX: dist/exploring-careers-in-tech-for-informatics.pptx  
PDF: dist/exploring-careers-in-tech-for-informatics.pdf

Alternative one-off:
npx @marp-team/marp-cli --allow-local-files --pptx slides/exploring-careers-in-tech-for-informatics.marp.md -o dist/exploring-careers-in-tech-for-informatics.pptx

## GitHub Actions
- Commit these files to main.
- Go to the Actions tab → Build slides → see the latest run.
- Download the artifact named “slides-pptx-and-pdf” to get the PPTX and PDF.