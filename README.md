# css-advanced-natours-udemy1
### SASS (Sass syntax & SCSS syntax)
* => Variables: for reusable values such as colors, font-sizes, spacing, etc;
* => Nesting: to nest selectors inside of one another, allowing us to write less code;
* => Operators: for mathematical operations right inside of CSS;
* => Partials and imports: to write CSS in different files and importing them all into one single file;
* => Mixins: to write reusable pieces of CSS code;
* => Functions: similar to mixins, with the difference that they produce a value that can than be used; 
* => Extends: to make different selectors inherit declarations that are common to all of them;
* => Control directives: for writing complex code using conditionals and loops (not covered in this course).

#### Add package.json file (1st time on new project otherwise npm i)
* => npm init
#### Add saas
* => npm i node-sass --save-dev

#### To compile scss add below to json file (add first scss file then css file)
* => "scripts": {
    "compile:sass": "node-sass sass/main.scss css/style.css"
  },
* => For compiler to keep watching for changes just add -w like below (didn't work for me, installed compiler extension as per solution):
    "scripts": {
    "compile:sass": "node-sass sass/main.scss css/style.css -w"
  },

* => (and then use this command to compile) npm run compile:sass (npm run watch:sass)
