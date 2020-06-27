
# scsswebkit  
A [scsswebkit](https://scsswebkit.netlify.com/) workflow for building static websites using SCSS. You must have SCSS enabled on your system or from within your code editor. If using VSCode download and install the [Live Sass Compiler](https://marketplace.visualstudio.com/items?itemName=ritwickdey.live-sass) extension.  The site entry point index.html contains a link to the css folder and the path to style.min.css. You can change the scss output file and name in your config or plugin extension config.
  
[![Netlify Status](https://api.netlify.com/api/v1/badges/0d8fa354-61e8-4de3-ada5-50e557271446/deploy-status)](https://app.netlify.com/sites/scsswebkit/deploys)  
  
## Before You Start
Before starging you should be familure with [SASS Basics](https://sass-lang.com/guide). Make sure to visit the [VSCode Live Sass Plugin](https://github.com/ritwickdey/vscode-live-sass-compiler/blob/master/docs/settings.md) on github and configure the plugin to usage preferance. Also it is helpful to have an understanding of how to use [BrowserList](https://github.com/browserslist/browserslist) as you can use it with the Live Sass Plugin.  
  
## style.scss
Open the style.scss file. Remove the starting styles for the site entry point.
```html
 body {
    width: 100%;
    height: 100vh;
    background: rgb(40, 38, 53);
    text-align: center;
    color: #fff;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}

img {width: calc(298px - 8vw);}

span {display: block;font-size: calc(2.5rem - 0.5vw);line-height: 1.125rem;}

figcaption {font-size: calc(1.5rem - 0.5vw);}
```

    
## scss folders
Each folder contains an _index.scss partial. Inside the index.scss partial you can place @import statements to each of the files you want to included. The style.scss file contains links to each folder. Remove and add what you need. Here is a short description of each folder and its contents.
<dl>
  <dt>function</dt>
   <dd>for your scss functions</dd>
  <dt>includes</dt>
   <dd>constains scss versions of the mini reset and the bootstrap reboot.scss</dd>
  <dt>mixins</dt>
   <dd>your mixins</dd>
   <dt>pages</dt>
   <dd>your site page styles</dd>
   <dt>typography</dt>
   <dd>your site base typography</dd>
   <dt>ui</dt>
   <dd>common user interface element that you build</dd>
   <dt>var</dt>
   <dd>variable declarations used in your site</dd>
</dl>  


 
