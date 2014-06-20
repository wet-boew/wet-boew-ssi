# Web Experience Toolkit (WET) - SSI Variant v4.0

## Overview

This feature adapts the HTML5 core markup structure for use with Server side includes (SSI) on an Apache web server.

##Benefits

* Helps to minimize the duplication of content and code (such as titles and dates)</li>
* Provides central control of the secondary column</li>
* Improves consistency by separating content from the template code</li>
* Automates the breadcrumb trail</li>
* Conforms to WCAG 2.0 AA</li>
* Uses WAI-ARIA to enhance accessibility</li>
* Supports Firefox, Opera, Safari, Chrome, and IE 8+ 

##Minimum Requirements

* dist folder from WET v4.0 from a supported theme
* Server Side Includes installed on an Apache 2.x Web Server

##Supported Themes

* WET-BOEW Base
* GC Web Usability
* GC Intranet

##How to install the files

* Make sure that you have the WET v4.0 /dist/ folder from one of the supported themes in your root directory.
* Rename the /dist/ folder (or create a web server alias) according to the theme you have:
** WET-BOEW Base (rename /dist/ to /dist-wet-boew/)
** GC Web Usability (rename /dist/ to /dist-gcwu-fegc/)
** GC Intranet (rename /dist/ to /dist-gc-intranet/)
* Copy the dist-ssi folder from this repository to your root directory.  Do not rename it.