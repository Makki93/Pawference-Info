# Pawference Info

Public website, support and privacy information for Pawference.

- Website: https://makki93.github.io/Pawference-Info/
- Support: https://makki93.github.io/Pawference-Info/support.html
- App privacy: https://makki93.github.io/Pawference-Info/app-privacy.html
- Website privacy: https://makki93.github.io/Pawference-Info/privacy.html
- All apps: https://makki93.github.io/
- Shared operator information: https://makki93.github.io/impressum.html

The application repository remains private. This repository contains only the
public static website files. GitHub Pages publishes the root of `main`;
`.nojekyll` disables Jekyll. No JavaScript, tracking, external fonts or package
dependencies are used. The app icon comes from the private application repository.

## Editing and publishing

The versioned website source is `site/` in the private `Pawference` repository.
Edit that source, inspect desktop and mobile layouts and validate navigation.
Then run its `scripts/publish_site.sh`, which copies only the explicitly allowed
public files into this sibling checkout (`src/Pawference-Info`) and publishes
them on `main`. Keep this README in the public repository. Do not copy app
source, internal documentation or signing files here.

This repository was previously named `pawference-site`. The shared overview
repository `Makki93.github.io` maintains redirects for the old page URLs, which
installed app builds and App Store Connect metadata may still reference.
