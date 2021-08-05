Steps:
* Create a project folder
* In terminal (at project folder location), run:
`npm init -y` to create a package.json file
* run:
`npm install --save-dev sass` to install sass as a dev dependency
* add this script to package.json:
`"sass": "sass --watch scss:dist/css"` you can also remove the default test script
* create a folder called _dist_ to put all files that will be deployed (html, css, etc.)
* inside _dist_, create a _css_ folder
* create a .gitignore file in project root and add *node_modules* so they aren't tracked by git. (not needed to track this)
* create a _scss_ folder in project root (for all sass files)
* create a sass file (ex. _main.scss_) inside the _scss_ folder

* To compile your sass file(s), in terminal, run:
`npm run sass`
* To stop npm sass from watching changes, in terminal press _Ctrl-C_
