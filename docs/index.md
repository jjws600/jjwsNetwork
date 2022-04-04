**Our Website**: <https://jjws.link/jjwsnetwork>  

* [Website Changelog](https://jjws600.github.io/jjwsNetwork)
* [Server Changelog](https://jjws600.github.io/jjwsNetwork/servers)

jjwsNetwork website changelog:
==

### v2.0.0-dev

#### Changes:
 * Complete rewrite mostly in bootstrap, using PHP includes per page if anyone was curious.
 * This new site has mostly cosmetic differences but the responsiveness of the design is HIGHLY improved, which is obviously due to bootstrap..
#### To-Do:
 * The next few versions will probably be me taking the pieces of bootstrap that i'm using and moving them into a custom css file to remove the massive file size of the bootstrap css.

---

### v1.1.1

#### **Planned changes**:
  * Make noscript transparent
  * Fix background image scaling again - make bg-small scale like bg-large does

### v1.1.0
*Deployed*

#### **Added**:
  * text-size-adjust in addition to the -webkit-text-size-adjust
  * charset to css (not sure if necessary but cant hurt...)
  * https://meyerweb.com/eric/tools/css/reset/reset.css

#### **Fixed**:
  * ID new-line was defined twice, moved to CLASS new-line
  * 'filter' should be listed after '-webkit-filter'.
  * footer form css was inline, moved to init.css

### v1.0.9

#### **Fixed**:
  * bg-small aspect ratio is now back to normal

#### **Removed**:
  * .js files, back to inline JS now.

#### **Changed**:
  * an external request from a _GET link to a _POST form.
  * jjwsLink link is now a <button>

### v1.0.8
*Deployed*

#### **Added**:  
  * manifest.json for PWA installing, and home screen support.
  * Service worker registered

#### **Fixed**:
  * bg-small aspect ratio not fixed, background is scaling on the x axis, making squashed image

### v1.0.7

#### **Changed**:
* Moved to v1.0.7 instead of -b as beta is no longer in effect, full site release (coming-soon page) has commenced [ready for production rc1/rc2 cleared, production copy pushed to server]
* jjwsLink now adds a message to my homepage saying that its not ready yet
* Instead of transitioning the background image using height, I changed it to a transformY instead via recommendation from a lighthouse link

#### **Fixed**:
* Firefox not respecting line breaks so i am switching to margin-top on the next element (caption -> discord button)


### v1.0.6-b-dev

#### **Added**:
* init.js instead of inline javascript (probably will be compiled into one file at )

#### **Fixed**:
* Version changelog link now opens in new tab

#### **Removed**: 
* Old PHP Footer code in favour of javascript
* nojs.php inlined

#### **Changed**:
* Moved from PHP variables to Javascript ones
* Cleaned up Javascript version code
* Added target="_blank" & rel="noreferrer" to all links (to open in new tab)


### v1.0.5-b-dev

#### **Added**:
* Donate button that links to paypal.me/jjws600

#### **Fixed**:
* Margin bottom was too high on 1080p, displayed scroll bar with no extra content, this was moved to a media query for small devices to have a good experience at the bottom of the content


## In between v1.0.2-b and v1.0.5-b, changes were not noted.


### v1.0.2-b:

#### **Added**:
* Javascript console logging for;
  * Version Number
  * Copyright Information

#### **Fixed**:
* Site manifest has been renamed to manifest, and enabled to use credentials if necessary. [Such as on development server].
* Scrollbar was able to be utilized on 1080p displays, to move slightly, adjusted padding on discord widget to fit on 1080p screen.

#### **Improved**:
* Title element has been more appropriately placed in document structure.

### v1.0.1-b:

#### **Added**:
* Footer link now resolves to unfinished [jjws.cf](https://jjws.cf)
* Version number in footer is now a link to this page.

#### **Fixed**:
* Copyright symbol had incorrect spacing

#### **Improved**:
* Spacing at top of page has been decreased to stop user not being able to see all of discord widget on 1080p Desktop.

### v1.0.0-b: 

#### **Added**:
* Discord Widget.
* Discord Server Buttons
* --BETA: Github Changelog Page--

#### **Fixed**:
* Responsiveness and general bug fixed.
* Caption and image banner were misplaced when on small screen, changed back to old system of 0px top margin, and placed caption appropriately.
* Footer had a % as the padding measurement which caused scaling issues, fixed by changing to px.

#### **Improved**:
* Updated to new Server Banner.
