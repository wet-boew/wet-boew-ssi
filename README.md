# Web Experience Toolkit (WET) - SSI Variant

## Overview

This feature adapts the HTML5 core markup structure for use with Server side includes (SSI) on an Apache web server.

##Benefits

* Helps to minimize the duplication of content and code (such as titles and dates)</li>
* Provides central control of the left and right columns</li>
* Improves consistency by separating content from the template code</li>
* Automates the breadcrumb trail</li>
* Conforms to WCAG 2.0 AA</li>
* Uses WAI-ARIA to enhance accessibility</li>
* Supports Firefox, Opera, Safari, Chrome, and IE 7+ 

##Minimum Requirements

* Build folder from WET 3.0
* Server Side Includes installed on a web server
* Apache 2.x Web Server

##How to install the files

* Make sure that you have the WET 3.0 build folder in your root directory.
* Copy the following directories into a folder created in the root:
 * inc\
 * demos\ssi
* "inc" is a folder with your global include files
* Another &quot;inc&quot; folder for page specific includes is under the demos\ssi folder, as well as a folder for main &quot;menu&quot; based includes. Also,shtm pages are located here.</p>

	* demos\ssi
	* demos\ssi\inc
	* demos\ssi\menu
	* demos\ssi\menu-left-gauche