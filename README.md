create a folder and enter into that folder run below command in cmd prompt it will manage dependencies in development as well as producton.


$ npm init


based on needs we can change package.json

then setting up basic project files and Folder Structure.

then enter below command inside cmd prompt for installing Dependencies


npm install --save @angular/core @angular/common @angular/compiler @angular/compiler-cli @angular/forms @angular/http @angular/platform-browser @angular/platform-browser-dynamic @angular/platform-server @angular/router @angular/upgrade 


for resolving dependencies like production and observables ...etc need to run below command.

npm install --save rxjs zone.js core-js



installing development dependencies for webpack
----------------------------------------
 npm install --save-dev webpack webpack-dev-server angular-router-loader angular2-template-loader awesome-typescript-loader html-loader raw-loader typescript del-cli


install the below package merge configurations

 npm install --save-dev webpack-merge

 npm install --save @angular/animations

install below package and put some code in webpack.config.common.ts


 npm install --save-dev html-webpack-plugin




 inside package.json we need to add a new script  build script
 and run 
 npm run build