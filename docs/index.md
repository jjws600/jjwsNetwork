**Our Website**: <https://jjws.cf/jjwsnetwork>  

Changelog
==
* [Website Changelog](https://jjws600.github.io/jjwsNetwork)
* [Server Changelog](https://jjws600.github.io/jjwsNetwork/servers)

## Website Changes:

### v1.0.7-b
*Uploaded to master*

#### **Changed**:
* Instead of transitioning the background image using height, I changed it to a transformY instead via recommendation from a lighthouse link
#### **Fixed**:
* Firefox not respecting <br> so i am switching to margin-top on the next element (caption -> discord button)


### v1.0.6-b-dev

#### **Added**:
init.js instead of inline javascript (probably will be compiled into one file at )
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
