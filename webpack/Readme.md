
mkdir webpack-demo && cd webpack-demo
tnpm init -y
tnpm install --save lodash
tnpm install -g npx
npx webpack
npx webpack src/index.js dist/bundle.js
npx webpack
npx webpack --config webpack.config.js
npm run build
tnpm install --save-dev style-loader css-loader
npm run build
npm install --save-dev file-loader
npm install --save-dev webpack-dev-server
npm start

