# Static Web Site Starter Kit

This repo contains a simple starting kit that will help you to develop static web sites. You can view the contents of this [repo hosted on netlify](https://simplewebkit.netlify.com/).

[![Netlify Status](https://api.netlify.com/api/v1/badges/55ba53f0-e914-459e-ad50-9aaea57e1043/deploy-status)](https://app.netlify.com/sites/simplewebkit/deploys)

<br>
<br>

## Before You Start

If using VSCode download and install the [Live Sass Compiler](https://marketplace.visualstudio.com/items?itemName=ritwickdey.live-sass) extension. To learn how to configure the extension take a look at the [settings documentation hosted on git](https://github.com/ritwickdey/vscode-live-sass-compiler#live-sass-compiler)

This kit uses SCSS as a preprocessor for your CSS so need to be comfortable using SCSS. If your not familure with using SCSS a good place to start is [Learning SCSS Basics](https://sass-lang.com/guide).

<br>
<br>

## Kit Folders

We hope that the kit files and folders are easy to understand by there file/directory name. Below you will find a directory tree for the kit. After which you can find the description of each directory and what it contains.

```bash
├── index.html
├── css
├── fonts
├── img
├── js
└── scss
```

**css** <br>
The files outputed from the scss folder. Depending on how you are compiling your SCSS you may have to change the output diretory to match the path to the root folder's css directory

**fonts** <br>
If your using self hosted you can place your font outlines in this directory. There is one self hosted font already in use ProductSans-Regular. This font added from scss/typography/\_typography.scss using the @fontface rule.

**img** <br>
Used for locally hosted media assets. If your building a static site you are better off using an image service like cloudinary. Most modern hosting platforms Google Firebase, Netlify all provide a way of hosting images to speed up your site.

**js** <br>
If your using javascript for the site we suggest using this folder.

**scss** <br>
This folder contains the scss files for the site. The folder is structured in a way to hel organize your site css. To find out more about how this directory is structured read the section on the kits scss.

<br>
<br>
<br>

## Index HTML

When starting a project open the index.html file and remove the html shown below.

```html
<header class="page-header">
  <img src="img/logo-1.svg" alt="" />
  <h1>magoglys</h1>
  <p>web kit for the static pages</p>
</header>
```
<br>
<br>
<br>

## The SCSS Folder <br>
The kit uses SCSS, and as such compiles the SCSS to the CSS folder in a file called style.min.css. If you want to rename this you will have to open the scss folder and rename style.scss to your preffered name. We have included a directory tree of the contents of the scss folder and what follows is a description of what each folder contains and how it is integrated in to the css build.
```scss
├── style.scss
├── typography
├── functions
├── mixins
├── pages
├── reboot
├── ui
└── variables
```

**typography** <br>
This folder contains the typography settings for the site. The kit assumes that you will be using self hosted fonts. The @font-face rule is used to load self hosted fonts from the site roots fonts folder. Some base settings have been applied.

**functions** <br>
Thero nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. At nulla pariatur. Excepteur sint occaecat is nostrud exercitation ullamco laboris nisi ut aliquip ex ea

**mixins** <br>
Ercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat is nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in repre

**pages** <br>
Do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non pro

**reboot** <br>
Consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat

**ui** <br>
Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

**variables** <br>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
