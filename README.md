MobileHybridApp-Tartanator
==========================

Starter Kit for in-class Training  

### Follows these steps:

1. **Add jQuery mobile code components into `<head>` section**
@index.html:  
`<meta name="viewport" content="width=device-width, initial-scale=1">`  
`<link rel="stylesheet" href="http://code.jquery.com/mobile/1.0rc1/jquery.mobile-1.0rc1.min.css" />`  
`<script src="http://code.jquery.com/jquery-1.6.4.min.js"></script>`  
`<script src="http://code.jquery.com/mobile/1.0rc1/jquery.mobile-1.0rc1.min.js"></script>`  

2. **Mark up the rest of the page into div blocks**
@index.html:  
`<div data-role="page">`  
`....<div data-role="header">`      
`....</div>`  
`....<div data-role="content">`    
`....</div>`  
`....<div data-role="footer">`  
`........<h4>Bring forrit the tartan!</h4>`  
`....</div>`  
`</div>`  
_check your progress_

3. **Insert list items into content**
@index.html:  
`<ul data-role="listview" data-inset="true">`  
`....<li><a href="aboutus.html">About us</a></li>`  
`....<li><a href="findevent.html">Find an Event</a></li>`  
`....<li><a href="tartans.html">Popular Tartans</a></li>`  
`.</ul>`  
_check your progress_

4. **Enhance Footer**    
@tartans/tartans.css:  
Add a css rule `[data-role="footer"] {text-align: center; padding: 5px 0;}` to center the footer text and give it some paddings  
@index.html:  
Link in the stylesheet with `<link rel="stylesheet" href="tartans/tartans.css" />`    
Remove `<h4>` from footer text  
Modify footer tag with `data-position="fixed" data-theme="c"` to fix its position and change color scheme    
_check your progress_  

5. **Add thumbnail image to tartan list**
@tartans.html:  
Replace `<ul data-role="listview">..</ul>` with code snippet from extras/tartan-list.txt  
_check your progress_  

6. **Add Filter to tartan list**
@tartans.html:  
Insert `data-filter="true"` to `<ul data-role="listview">`  
_check your progress_  

7. **Add a footer toolbar**
@index.html:  
Insert `<div data-role="navbar">..</div>` into footer and add list items inside like this  
`<div data-role="footer" data-position="fixed">`   
`....<div data-role="navbar">`  
`....<ul>`  
`........<li><a href="index.html">About</a></li>`  
`........<li><a href="findevent.html">Events</a></li>`  
`........<li><a href="tartans.html">Tartans</a></li>`  
`....</ul>`  
`....</div>`  
`</div>`  
Notice that we've removed `data-theme` from footer tag and no more attribute in `<ul>`  
Do not forget to remove `<ul>..</ul>` from content  
_check your progress_  

8. **Put icon in toolbar**
@index.html:  
Add `data-icon` attribute to `<a>` of each button  
and Hilight active button with `class="ui-btn-active"` like this  
`<li><a href="index.html" data-icon="info" class="ui-btn-active">About</a></li>`  
`<li><a href="findevent.html" data-icon="star">Events</a></li>`   
`<li><a href="tartans.html" data-icon="grid">Tartans</a></li>`  
_check your progress_  

9. **Add Tag Line to the landing page**
@index.html:  
Fix header position with `data-position="fixed"`  
and append the following snippet below header  
`<div data-role="header" data-theme="b" class="forrit">Bring forrit the tartan!</div>`  
_check your progress_  

10. **Implement new footer navbars and Fix header position in the other pages**
@findevent.html, tartans.html:  
Make sure to assign the `ui-button-active` class to the correct `<a>` for each page  
_check your progress_  

 