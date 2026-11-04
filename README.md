# Planetic Labs website

The organization website at https://planetic-labs.github.io/.

A static, responsive page introducing Planetic Labs as an open source software company and showcasing public projects. Featured projects are Plupo and Beacon. Plupo has an MIT license; Beacon is linked as a public project without a license claim. Links to other repositories do not imply a particular license or release status.

Edit `website/index.html` and `website/style.css`. There is no build step, JavaScript, analytics, third-party font, or package installation. Preview with `python3 -m http.server 8081 --directory website`.

GitHub Pages deploys `website/` automatically on relevant pushes to `main`, or via the **Publish Planetic Labs website** workflow. Pages uses GitHub Actions as its publishing source.

The root `robots.txt` allows crawling and advertises the organization and Plupo sitemaps. It applies to every project under `planetic-labs.github.io`; preserve existing project access when changing it. The Plupo website remains in its own repository.

The page includes canonical/social metadata and Organization JSON-LD. Add new project descriptions only from verified public information. Do not publish private projects or infrastructure details.
