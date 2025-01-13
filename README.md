Build tools
The theme includes a custom Webpack file, which can be used to quickly recompile and minify theme assets while developing or for deployment. You'll need to install Node.js before using Webpack.

Once Node.js is installed, run npm install to install the rest of AdminKit's dependencies. All dependencies will be downloaded to the node_modules directory.

npm install
Now you're ready to modify the source files and generate new dist/ files. AdminKit uses webpack-dev-server to automatically detect file changes and start a local webserver at http://localhost:8080.

npm start
Compile, optimize, minify and uglify all source files to dist/ folder:

npm run build
CDN support
All files included in the @adminkit/core npm package are available over a CDN.

CSS:

<link rel="stylesheet" href="https://unpkg.com/@adminkit/core@latest/dist/css/app.css">
Javascript:

<script src="https://unpkg.com/@adminkit/core@latest/dist/js/app.js"></script>
