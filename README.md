1. npm i -D webpack webpack-cli

2. update scripts -
   scripts : {
   "build":"webpack"
   }
3. npm run build

4. install loaders
   npm i -D sass style-loader css-loader sass-loader

5. install html plugin
   npm i -D html-webpack-plugin

6. adding template.html

7. update scripts -
   scripts:{
   "dev":"webpack serve"
   }

   it will ask to download "webpack-dev-server"

8. adding sourcemap for debugging

9. adding babel
   npm i -D babel-loader @babel/core @babel/preset-env

10. adding webpack analyzer
    npm i -D webpack-bundle-analyzer
