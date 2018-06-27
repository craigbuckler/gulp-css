# gulp-css
Using Gulp.js for CSS tasks


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

## Usage
Run in live-reloading development mode:

```bash
gulp
```

Navigate to `http://localhost:8000/` or the `External` URL reported if accessing from another device. Further instructions are shown on the index page.


## Build production CSS
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
