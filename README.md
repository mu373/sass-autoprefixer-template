# sass-autoprefixer-template
Compile SCSS to CSS with vendor prefixes

## Dependencies
- [`sass`](https://github.com/sass/sass): Compile SCSS
- [`autoprefixer`](https://github.com/postcss/autoprefixer): Automatically add vendor prefixes (PostCSS plugin)
- [`PostCSS`](https://github.com/postcss/postcss): required for autoprefixer
- [`watch`](https://www.npmjs.com/package/watch): watch for file changes and run npm scripts

## Usage
- Install dependencies
    - `npm install`
- Make SCSS files in `/scss` directory
- Let it watch for changes and compile
    - `npm run watch:css`