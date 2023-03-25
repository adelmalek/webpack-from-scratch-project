# Babel and Webpack

- Babel is simply a translator, who translates your 'fancy' (ES6+) JS code into 'not-so-fancy' (ES5) ones that browser (front-end) or Node.js (back-end) understands.

- If Babel is a translator for JS, you can think of Webpack as a mega-multi-translator that works with all kinds of languages (or assets).
- Front-end has many kinds of assets such as CSS, SASS, images, fonts and is way more complex and dynamic than back-end which only has JS.

- Backend: we use Babel so that we can use the fanciest JS syntax (ES6/7) with Node.js.
- Frontend: we use Webpack (which uses Babel and other things) to compile JS code and many other assets into a few small bundle files that our users can download when they first load our webpage. For example, create-react-app uses Webpack and Babel when creating your app.
