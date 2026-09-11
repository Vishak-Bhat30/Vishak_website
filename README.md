# Vishak K Bhat - Personal Website

Static HTML, CSS, and JavaScript portfolio. No build step is required.

## Local Preview

Open [index.html](index.html) in a browser. Fonts, icons, and scroll animations use external CDNs and require an internet connection.

## Content and Resume

The portfolio content was updated from the August 2026 resume, available at [assets/resume.pdf](assets/resume.pdf).

- Education: Integrated M.Tech. in Mathematics and Computing, IIT (ISM) Dhanbad, May 2026; CGPA 8.85/10, rank 3.
- Experience: Microsoft Research Intern to Research Fellow, interwhen, and updated research and industry results.
- Research: interwhen, Genesis, and the GSoC muon-momentum GNN preprint. Review statuses follow the resume; interwhen's title and author list follow its current arXiv record.
- Projects and achievements: multi-agent question-and-answer competition, Vesuvius ink detection, technical skills, and updated awards.

To update the resume again, replace [assets/resume.pdf](assets/resume.pdf) and update the `?v=2026-08` query on both resume links in [index.html](index.html). Also update the download filename there. The version query helps returning visitors retrieve the new PDF.

## Publish at the Root GitHub Pages Address

Target address: **https://vishak-bhat30.github.io/**

GitHub requires a user-site repository to be named **vishak-bhat30.github.io**. Changing HTML or setting a custom domain does not remove the project path from the current repository's Pages address. A CNAME file is not needed.

1. Review and commit the local changes, then push them to the repository's `main` branch.
2. In the repository's **Settings > General**, rename `Vishak_website` to `vishak-bhat30.github.io`. If that repository already exists in your account, use the existing root-site repository instead of overwriting it.
3. In **Settings > Pages**, select **Deploy from a branch**, with branch **main** and folder **/ (root)**, then save. Keep **Custom domain** empty. The [.nojekyll](.nojekyll) marker preserves this as a plain static site.
4. Update this local clone's remote after the GitHub rename:

	```sh
	git remote set-url origin https://github.com/Vishak-Bhat30/vishak-bhat30.github.io.git
	```

5. Wait for the Pages deployment to succeed, then check the homepage, every subpage, and both resume links at **https://vishak-bhat30.github.io/**. Publication can take up to 10 minutes.

All page, stylesheet, script, image, and resume paths are relative, so they work at both the old project path and the new root address.

**Old links:** GitHub redirects renamed repository URLs, but not GitHub Pages project URLs. Links under `https://vishak-bhat30.github.io/Vishak_website/` may stop working. Update links on your profiles and other sites, or arrange explicit redirects before migration if those old addresses must remain available.

References: [Creating a GitHub Pages site](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site) and [Renaming a repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/renaming-a-repository).
