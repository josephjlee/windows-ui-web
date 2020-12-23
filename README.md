<h2 align="center"> 

  <img src="kitchen-sink/_md_preview/app_preview_readme_title_flat__.png" width="440" /> 

</h2>






<meta name='keywords' content='Windows10,MetroUI,framework,html,css,js'>
<meta name='description' content='Build Windows 10 look and feel web apps or electron apps using html,css & js'>
<meta name='author' content='Vivek Verma'>


<p align="center">
	




  <img alt="Netlify" src="https://img.shields.io/netlify/4a7e4c36-524a-4cd6-b1bf-e535ec5c7d07?label=build&logo=github&style=flat-square">

	
  <a href="https://github.com/virtualvivek/Windows10&#95;framework/blob/master/LICENSE">
    <img src="https://img.shields.io/badge/License-MIT-darklime.svg?style=flat-square&color=blue"
      alt="License: MIT" />
  </a>
  


  <a href="https://github.com/virtualvivek/Windows10&#95;framework">
    <img src="https://img.shields.io/badge/Release-v2.0-green.svg?style=flat-square&color=darklime"
      alt="Release" />
  </a>
  
</p>



<h2 align="center">Build Windows Apps with Convinience</h2>

<h3 align="center"><a href="https://windows10framework.github.io/">windows10framework.github.io</a></h3>

<p align="center">
	Build full featured Windows 10 look & feel UI apps or Electron apps using <b>Html</b>, <b>CSS</b> & <b>JavaScript</b>. Comes with rich native like components, icon sets. Used as fast prototyping tool for Windows environment platforms. <br>	
</p>

	

<h2 align="center">
  <a href="https://windows10framework.github.io"><img src="kitchen-sink/_md_preview/app_preview_button_watch_demo.png" width="250" /></a>

  <img src="kitchen-sink/_md_preview/app_preview_button_store.png" width="250" />

  <img src="kitchen-sink/_md_preview/app_preview_button_electron.png" width="250" />
</h2>



## Stunning Set Of UI Elements

<h1 align="center">
	<img src="kitchen-sink/_md_preview/md_glance_forms.png" width="850" />
	<img src="kitchen-sink/_md_preview/md_glance_advance.png" width="850" />
</h1>
<p align="center">
Provides you with the rich UI Components that to completely matches the latest Windows environment that accelerates your productivity to build your hybrid windows app.
</p>
<br>

## Build Universal Windows or Web Apps
Create apps that run fluently on every device

<h1 align="center">
	<img src="kitchen-sink/_md_preview/app_preview_responsive.gif" width="200" />
</h1>

# Documentation

  * [Form Elements](src/core/docs/forms/README.md)
  * [Progress Controls](src/core/docs/progressControls/README.md)
  * [Icons](src/core/docs/icons/README.md)
  * [Bottom Sheet](src/core/docs/bottomSheet/README.md)
  * [Alerts](src/core/docs/alerts/README.md)
  * [Notifications](src/core/docs/notifications/README.md)
  

<p align="center">
<a href="src/core/docs/forms/README.md"><img src="src/core/docs/root_md_preview/docs_forms.png" width="250" /></a>
<a href="src/core/docs/progressControls/README.md"><img src="src/core/docs/root_md_preview/docs_progress_controls.png" width="250" /></a>
<a href="src/core/docs/icons/README.md"><img src="src/core/docs/root_md_preview/docs_icons.png" width="250" /></a>
<a href="src/core/docs/bottomSheet/README.md"><img src="src/core/docs/root_md_preview/docs_bottomsheet.png" width="250" /></a>
<a href="src/core/docs/alerts/README.md"><img src="src/core/docs/root_md_preview/docs_alerts.png" width="250" /></a>
<a href="src/core/docs/notifications/README.md"><img src="src/core/docs/root_md_preview/docs_notifications.png" width="250" /></a>
</p>

<br>
<h1>Getting Started</h1>

### Code container template
<h3>View <a href="templates/screen-main.html">App template</a></h3> 

```htm
body 
├── app-container
    ├── app-nav-wrap
	├── nav
	    ├── app-back | app-name
	    ├── ul
	    	├── li tab1
		├── li tab2
	    ├── /ul
         ├── /nav
     ├── /app-nav-wrap
     
  ├── app-content-wrap
  
      ├── app-section-1
      	  ├── app-section-container
      ├── /app-section-1
      
      ├── app-section-2
      	  ├── app-section-container
      ├── /app-section-2
      
  ├── /app-content-wrap
├── /app-container
/body
```
<br>



### Configure App Preferences
Customize app `preferences` including `drop shadows`,`dark mode` etc.. using `appConfig.js` file <br>
<b>./src /core /app-config /<a href="src/core/app-config/appConfig.js">appConfig.js </a></b>


```js
let BlurEnabled = true;  //'true' get drop shadows for components
let AlertStyle = 'Win10';  //'Win8','Win10'
let ShowDarkModeSwitch = true;  //'true' get display a switch for dark/light mode
let NightMode = false;  //'true' get dark mode when app mounted
```


<br>

### Configure App Color, Font Family or ScrollBars
You can customize entire app `accent color`, `font family`, more using `appConfig.css` file <br>
<b>./src /core /app-config /css /<a href="src/core/app-config/css/appConfig.css">appConfig.css</a></b>


```css
:root {	--AppColor: #2D7D9A; } /*Customize Entire App Color You Like*/

body {
    font-weight: 400;
    font-family: Segoe UI, sans-serif;  /*Customize with your own font family*/
    .... }
```

<br>

## Find this framework useful? :heart:
Support it by joining [stargazers](https://github.com/virtualvivek/Windows10-framework/stargazers) for this repository. :star:

<br>

## License

	MIT License

	Copyright (c) 2020 Vivek Verma

	Permission is hereby granted, free of charge, to any person obtaining a copy
	of this software and associated documentation files (the "Software"), to deal
	in the Software without restriction, including without limitation the rights
	to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
	copies of the Software, and to permit persons to whom the Software is
	furnished to do so, subject to the following conditions:

	The above copyright notice and this permission notice shall be included in all
	copies or substantial portions of the Software.

	THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
	IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
	FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
	AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
	LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
	OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
	SOFTWARE.
