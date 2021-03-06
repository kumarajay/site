---
title: "Preview"
class_name: docs
full_width: true
---


Codio offers 2 ways to run your application in Preview mode

##Menu
You will find 'Preview' in the menu at the top of the page. This will look for index.html in the root of your project and run it in the preview window. 

##Right-Click
If you want to run a specific file, then right-click the file and select Preview.

##Keyboard
Press the 'Shortcuts' link in the bar at the bottom of the IDE and select Inline Preview tab to see all Preview options.

##Inline or Dedicated Browser Tab
By default, Preview will create an inline preview, as shown in the screenshot below. 

![inline preview](/img/docs/inline-preview.png)

There are 3 icons in the top of the Preview window 

1. **Close** - press the 'x' button
1. **Expand** - press the small arrow icon to expand the preview into its own browser tab
1. **Refresh** - if you have made any changes to you code, you can press the refresh button to reload. 

##Security Issues
Codio runs over https and so the inline preview runs over https, too. If you reference an external script or API, for example like this 

	<script src="http://code.angularjs.org/1.1.5/angular.js">

then you will get a browser error.

To avoid this, you should expand the inline preview into a new browser tab (icon is in the bar above inline preview) and then modify the url from `https://codio.io/xxxx` to `http://codio.io/xxxx`

We will shortly be introducing a better way of managing all this.


