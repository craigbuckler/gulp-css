# gulp-css
This provides an example Gulp.js project which automates CSS tasks including:

* optimizing images
* compiling Sass .scss files
* handling and inlining assets
* automatically appending vendor prefixes
* removing unused CSS selectors
* minifying CSS
* reporting file sizes
* outputing sourcemaps for use in browser devtools
* live-reloading CSS in a browser when source files change.


## Installation
To install on any Linux, Mac OS or Windows system, ensure [Node.js](https://nodejs.org/) is installed then clone the repository:

```bash
git clone https://github.com/craigbuckler/gulp-css.git
```

Navigate to the folder:

```bash
cd gulp-css
```

Install dependencies:

```bash
npm i gulp-cli -g
npm i
```

Note that module versions have been fixed to guarantee compatibility. Run `npm outdated` and update `package.json` as necessary.


## Usage
Run in live-reloading development mode:

```bash
gulp
```

Navigate to `http://localhost:8000/` or the `External` URL if accessing from another device. Further instructions are shown on the index page.


## Build production CSS
Set `NODE_ENV` to `production` so Gulp tasks produce final code, i.e. remove unused CSS, minify files, and disable sourcemap generation.

Linux/Mac OS:

```bash
NODE_ENV=production
gulp css
```

(or inline `NODE_ENV=production gulp css`)

Windows Powershell:

```powershell
$env:NODE_ENV="production"
gulp css
```

Windows legacy command line:

```cmd
set NODE_ENV=production
gulp css
```
