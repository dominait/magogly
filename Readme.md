# CSS Static Web Site Starter Kit
A [simple starter kit](https://simplewebkit.netlify.com/) for building static websites. This kit doesn't leverage any tools or task runners and does not implement any build tools. This webkit is suggested for those with basic HTML/CSS knowledge.  
  
  [![Netlify Status](https://api.netlify.com/api/v1/badges/55ba53f0-e914-459e-ad50-9aaea57e1043/deploy-status)](https://app.netlify.com/sites/simplewebkit/deploys)

## Starting A Project
When starting a project open the index.html file and remove the html and css shown below. 
### Uncomment CSS Files  
The kit contains a css reset and a copy of bootstraps reboot.css. Neither of these files is linked to the index.html document. If you want to use a reset or the reboot uncomment the link elements in the &lt;head&gt;
```html
    <!-- <link rel="stylesheet" href="css/reboot.css"> -->
    <!-- <link rel="stylesheet" href="css/reset.css">  -->
    <link rel="stylesheet" href="css/style.css">
```

 


### Remove Styles
```html
<!-- Remove Styles -->
    <style>
        body {
            width: 100%;
            height: 100vh;
            background: tomato;
            text-align: center;
            color: #fff;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
        }
        img {width: calc(298px - 8vw);}
        figcaption {font-size: calc(1.5rem - 0.5vw);}
    </style>
```
### Remove Markup
```html
 <!-- Remove Markup -->
    <figure>
        <figcaption>website starter kit</figcaption>
        <img src="img/starter.svg" alt="">
    </figure>
```
 

## Features
<dl>
  <dt>CSS Mini Reset</dt>
   <dd>simple reset of all elements, uses systemUI font stack and adjust box model on all elements</dd>  
   <dt>CSS Reboot</dt>
   <dd>
   Reboot css taken from the bootstrap framework. The file is not linked to the index.html document.  
   </dd>  
</dl>
