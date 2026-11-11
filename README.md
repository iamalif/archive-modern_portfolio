# Historical Portfolio Website

An earlier portfolio website retained as a frontend learning record. It uses HTML, Sass/SCSS and JavaScript to present a multi-page personal site with a toggleable navigation menu.

This is a historical version. Its biography, contact details and project links may be outdated. For current professional information, visit [my GitHub profile](https://github.com/iamalif). My separate [personal website repository](https://github.com/iamalif/alaminalif) is maintained independently.

## Pages

| File | Purpose |
|---|---|
| `dist/index.html` | Home page |
| `dist/about.html` | About page |
| `dist/work.html` | Project gallery |
| `dist/contact.html` | Contact page |

## Viewing the existing site

Download or clone the repository and open `dist/index.html` in a browser. Keep the `dist/css`, `dist/js` and `dist/img` folders in their existing locations.

The repository includes compiled CSS, so viewing these pages does not require installing Node.js dependencies or rebuilding the styles. External Font Awesome icons require internet access.

## Source structure

- `scss/`: Sass source, including configuration, menu and mobile-layout partials.
- `dist/css/main.css`: existing compiled stylesheet.
- `dist/js/main.js`: navigation toggle using DOM selection and CSS class changes.
- `dist/img/`: site images.
- `package.json` and `package-lock.json`: original build configuration and dependency records.

## Original build configuration

The package configuration defines a `sass` command that watches `scss/` and writes compiled styles to `dist/css/`. It specifies `node-sass` version range `^4.13.1`.

This configuration is retained as part of the historical project. It has not been modernised or revalidated for a current development environment. Use the existing compiled pages to inspect the site without rebuilding it.

## Learning focus

HTML page structure, Sass organisation, responsive styling, JavaScript event handling and navigation state.

## Attribution

Third-party icons, imagery and any template or instructional material remain attributable to their respective creators. Retaining this repository does not imply original authorship of every visual asset or design pattern.
