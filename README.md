# Front-end Sass Boilerplate

This does not include support for moving assets like images, but you could duplicate the `copy:html` and `watch:html` scripts as a basis to include other assets.

## Project Structure

src/
- sass/
- - style.scss
- index.html

## Project Scripts

**`npm install`**

> Run install of node dependencies

**`npm start`**

> Run 11ty with hot reload at localhost:8080, including reload based on Sass changes

**`npm run build`**

> Production build includes minified, autoprefixed CSS

Use this as the "Publish command" if needed by hosting such as Netlify.

## Contributing

You should only need to run `npm start` to work on this project. There is a pre-commit hook that is automatically configured which will run the production build before you commit and push to the repo.
