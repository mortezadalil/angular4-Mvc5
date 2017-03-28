# angular4-Mvc5
Quickstart angular 4 and asp.net mvc 5 

# Compare with Angular quickstart
This repo base on https://github.com/angular/quickstart
1. Change src folder to AngularSrc
2. Add one line to RouteConfig.cs
3. Move tsconfig.json to root and change module value to 'commonjs'.
4. Remove non-essential files.
5. Replace index.cshtml with quickstart index.html (with some changes)(layout set to null for simplifying)
6. minor change on systemjs.config.js

You can compare this quickstart with angular quickstart.
https://github.com/angular/quickstart

Don't forget to run this code inside package console mangert on root path of project.(Or Re-save package.json with vs)
```
npm install
```
