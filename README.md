# AI Engineering Toolbox

A GitHub Pages-ready static website that catalogs modern AI engineering tools across:

- RAG frameworks
- vector databases and hybrid search
- agent frameworks and orchestration
- document parsing and ingestion
- model serving and routing
- evaluation and observability
- guardrails and protocols

## Deploy on GitHub Pages

### Option 1: Deploy from the repository root
1. Create a new GitHub repository.
2. Upload `index.html`, `.nojekyll`, and this `README.md` to the root.
3. On GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select your branch (usually `main`) and folder `/ (root)`.
6. Save.

### Option 2: Deploy from `/docs`
1. Put `index.html` and `.nojekyll` inside a `/docs` folder.
2. In **Settings → Pages**, choose the same branch and set the folder to `/docs`.

## Notes
- This site is fully static and does not require a build step.
- `.nojekyll` is included so GitHub Pages serves the site as plain static files.
- You can edit the tool list directly inside the `tools` JavaScript array in `index.html`.

## Easy customization ideas
- Add pricing badges
- Add “open source only” or “cloud only” filters
- Add a comparison page per category
- Add screenshots or logos
- Split data into a separate `tools.json` file
