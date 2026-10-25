# VideoPlyr

**A demo hub for HTML5 video players and Google Drive video playback integrations.** This backup copy preserves the source history while migrating links and hosting metadata to the `sh20raj-backup` namespace.

[![GitHub Pages](https://img.shields.io/badge/demo-GitHub%20Pages-222?logo=github)](https://sh20raj-backup.github.io/VideoPlyr/)
[![Pages deployment](https://github.com/sh20raj-backup/VideoPlyr/actions/workflows/pages.yml/badge.svg?branch=main)](https://github.com/sh20raj-backup/VideoPlyr/actions/workflows/pages.yml)

## Live demos

- **VideoPlyr demo hub:** https://sh20raj-backup.github.io/VideoPlyr/
- **DrivePlyr demo:** https://sh20raj-backup.github.io/DrivePlyr/
- **DrivePlyr20 source/templates:** https://github.com/sh20raj-backup/DrivePlyr20

## Features

- Multiple HTML5 player demos in one place.
- Examples for integrating the Sopplayer CDN distribution.
- Responsive demo layouts and standalone player pages.
- GitHub Actions workflow for publishing the static demo to GitHub Pages.

## Sopplayer CDN

Use the version-pinned backup CDN in new integrations:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/sh20raj-backup/Sopplayer@v2.0.0/sopplayer.min.css">
<video class="sopplayer" controls preload="auto">
  <source src="YOUR_VIDEO_URL.mp4" type="video/mp4">
</video>
<script src="https://cdn.jsdelivr.net/gh/sh20raj-backup/Sopplayer@v2.0.0/sopplayer.min.js"></script>
```

Replace `YOUR_VIDEO_URL.mp4` with your own media URL. For deterministic builds, keep the explicit `@v2.0.0` version pin.

## Deployment

The workflow at [`.github/workflows/pages.yml`](.github/workflows/pages.yml) deploys the repository's static files to GitHub Pages whenever `main` changes and supports manual dispatch. Monitor [workflow runs](https://github.com/sh20raj-backup/VideoPlyr/actions) for the latest result.

> GitHub Pages serves static files; PHP templates require a PHP-capable server and do not execute on Pages.

## Related projects

- [Sopplayer](https://github.com/sh20raj-backup/Sopplayer) — HTML5 player library and CDN assets.
- [DrivePlyr](https://github.com/sh20raj-backup/DrivePlyr) — Google Drive proxy player demos.
- [DrivePlyr20](https://github.com/sh20raj-backup/DrivePlyr20) — PHP player templates.

## License

Refer to the repository's existing license file, if present.
