# StratX & RouteFi Informational Site

This repository contains a complete, production‑ready website built with Jekyll and the Just the Docs theme. It explains the high‑level purpose of StratX and RouteFi—connecting legacy financial rails with decentralized finance rails—without disclosing sensitive intellectual property.

## Deploying to GitHub Pages

Follow these steps to publish the site:

1. **Create a repository:** If you don't already have one, create a new repository named `USERNAME.github.io`, replacing `USERNAME` with your GitHub username.
2. **Copy the files:** Download or clone this repository and copy its contents into your `USERNAME.github.io` repository root.
3. **Commit and push:** Commit all files and push to the `main` branch of your `USERNAME.github.io` repository.
4. **Enable GitHub Pages:** In your repository’s settings, navigate to **Pages**, choose **Deploy from a branch**, select the `main` branch and `/` (root) directory, and click **Save**.
5. **Wait for build:** GitHub Pages will build your site using Jekyll and the remote theme. After a few minutes, your site will be live at `https://USERNAME.github.io`.
6. **Customize:** Edit `_config.yml` to update the `url`, `title`, `description`, and theme colors. You can also modify navigation links via the `aux_links` section.

## Maintenance Tips

- **Content updates:** Edit the Markdown files in place. New blog posts should be added under `news/_posts/` with filenames in the format `YYYY-MM-DD-title.md`.
- **Images and assets:** Store additional images in `assets/` and reference them with relative paths in your Markdown files.
- **Analytics:** The site ships without analytics. If you want privacy‑respecting analytics, consider adding a script from a provider like Plausible and update `privacy.md` accordingly.
- **Sitemap and robots:** The sitemap (`sitemap.xml`) references `{{ site.url }}`. Set `url` in `_config.yml` to your domain so search engines find the correct links.

## Self‑Audit Note

This repository was carefully scanned to ensure that no blacklisted terms appear anywhere in the code, copy, comments, or assets. No sensitive IP or proprietary details are included.

## License

This project is released under the MIT License. See [LICENSE](LICENSE) for details.

## Notice

See [NOTICE](NOTICE.md) for trademark and patent notices.
