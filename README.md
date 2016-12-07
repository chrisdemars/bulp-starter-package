# Bulp Starter Package!

Before your eyes is the starter package for using Bulp. Bulp is a basic gulp build system that supports concatenation, minification, image optimization, and renaming of files. It also comes packed with other goodies such as autoprefixer and uglification as well as browser sync. No more hassles of refreshing the browser everytime you want to see the output of the modified code.

Also within this package is a `src` directory and a `dist` directory for non-compiled and production ready code. The file structure is already set up and includes Boostrap as a starting point, if you are in to that sort of thing. Just add code to your `*.scss` files, `*.html` files, and `*.js` files, run `gulp` in the terminal, and watch MAGIC unfold before your eyes!

## Installation

Clone or download the repo to your local machine.<br>
* `git clone https://github.com/chrisdemars/bulp-starter-package.git PROJECTNAME`

Open the directory with the project.
* `cd PROJECTNAME`

Run npm install.<br>
* `npm install`

Open the project in your favorite editor.<br>
* `atom .`

Open the terminal and run `gulp` so that it starts running before you start making any changes.

* Every time you start working on your project, make sure to run `gulp` so all the files can be watched for changes and the tasks can run against those files.

### Note

In the gulpfile.js, browser sync is calling chrome canary. If you don't have or use chrome canary or chrome at all, you can change it to just google chrome or whatever browser you wish.<br>
```
    browserSync.init({
        server: './',
        browser: "google chrome canary"
    });
```

## Contribute

If you have a great package that can be added or you think something can be tweaked, by all means fork, clone, and submit a PR. I am welcome to everything.
