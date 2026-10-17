# Setup — Faizan GitHub Profile

1. Create a **public** GitHub repository named `faiz1487` under GitHub account `faiz1487`.
2. Upload `README.md`, the five `.svg` files, and `.github/workflows/3d-contributions.yml` to the repository root, keeping the directory structure.
3. Go to **Settings → Actions → General → Workflow permissions** and select **Read and write permissions**, if available.
4. Go to **Actions → 3D Contribution Graph → Run workflow**. Allow a few minutes for the `output` branch and the contribution image to appear.
5. If the contribution image does not render, inspect the workflow logs, verify the generated path and output branch, and update the image URL in README accordingly.
6. Project paths `./mes-project`, `./microservices-aws`, and `./hybrid-ci-cd` require actual directories in this repository; otherwise replace them with live repository URLs.
7. GitHub stats are served by third-party services and may temporarily be unavailable. Animated SVG elements may display statically in some Markdown clients.
8. Commit changes to the default branch. Profile README appears automatically when the repository name matches your GitHub username.

**Note:** This package does not contain the actual DevOps project source code or the referenced resume PDF. Add them separately only if you want to publish them.

## Premium assets

The additional `architecture.svg`, `pipeline.svg`, `projects.svg`, and `roadmap.svg` are self-contained SVGs (no external fonts or images). They render directly on GitHub. Update the text in each SVG if your project scope changes.

The featured project paths in README are placeholders until those project directories exist; do not imply live demos or verified deployments until published. GitHub stats rely on third-party endpoints.
