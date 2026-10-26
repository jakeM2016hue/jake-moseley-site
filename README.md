# Jake Moseley — Personal Homepage

A one-page personal site built with Bootstrap 5.3 and the Grayscale theme from Start Bootstrap. It's hosted on AWS Amplify from this GitHub repository.

## Folder layout

```
index.html               the page
css/                     Bootstrap 5.3 CSS files, the theme's styles.css, and custom.css (my tweaks)
js/                      Bootstrap 5.3 JS files and the theme's scripts.js
assets/img/              photos (free stock images bundled with Start Bootstrap templates)
assets/favicon.ico
LICENSE-grayscale-template.txt   MIT license for the Start Bootstrap templates
```

`index.html` loads `css/bootstrap.min.css`, `css/styles.css`, `css/custom.css`, and `js/bootstrap.bundle.min.js` by relative path. Keep `index.html` in the repo root, next to the `css` and `js` folders. If those paths break, the page shows up unstyled.

## Hosting

Connect this repo in the AWS Amplify console. The default build settings work as-is, because this is a plain static site with no build step. Every commit to the connected branch redeploys the site within a minute or two.
