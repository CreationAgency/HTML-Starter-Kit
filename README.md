# HTML-Starter-Kit
Template for simple HTML/SASS builds

## Prerequisites
- Install Node.js (https://www.npmjs.com/get-npm)

## Features
- [SASS](https://sass-lang.com/) with preset mixin libraries
- [Susy2 Framework](http://susy.readthedocs.io/)
- [Mappy Breakpoints](https://github.com/zellwk/mappy-breakpoints)
- [Autoprefixer](https://github.com/postcss/autoprefixer)
- [Linting](https://github.com/okonet/lint-staged)
- [BrowserSync](https://browsersync.io/)

## Start Here
1. Run the command `npm install` at the root of the project to install all project dependencies.

2. Run the command `npm run start` to initiate the project and have [browsersync](https://browsersync.io/) watch your files for you.

2. [Generate Favicons](https://realfavicongenerator.net/) and replace the Favicons section in the header of the file `build/index.html` with the generated code. Don't forget to also add the icons to the project.

3. Setup [OG tags](https://realfavicongenerator.net/social/) for social sharing and replace the Favicons section in the header of the file `build/index.html` with the generated code. Don't forget to also add the image to the project.

4. Build your HTML structure in the file `build/index.html`.

5. Add custom fonts to the file `src/scss/common/_fonts.scss`.

6. Update the file `src/scss/common/_variables.scss`
- Choose [color names](http://chir.ag/projects/name-that-color/) and choose [semantic colors](http://sass-lang.com/styleguide/color) for the areas on the site.
- Set the default fonts.

7. Update the file `src/scss/common/_scaffolding.scss` to override the default html tag styles.

8. Add the styling for your HTML content in the files `src/scss/layouts/_header.scss`, `src/scss/layouts/_content.scss` and `src/scss/layouts/_footer.scss`.