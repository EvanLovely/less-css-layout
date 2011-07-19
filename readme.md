BetterLayout with [LESS CSS](http://lesscss.org)
==========================================

Steps
-------
* Choose Fixed or Liquid layout and make sure the right style sheet is un-commented in the `<head>`
* Download the [LESS Mac Compiler](http://incident57.com/less/) or any other compiler. Add this folder to the compiler.
* Set these variables in either `variables-liquid.less` or `variables-fixed.less`:
	* Site Width (Can choose from either a fixed or liquid layout)
	* Site Padding (Takes it away from the width, so your width is actually how wide the site is).
	* Sidebar width with only 1 sidebar, or 2 separate width settings  when 2 sidebars are present.
	* Sidebar Paddings.
	* There is no #main content width setting as all above widths & paddings get subtracted from the site width.
	* **Colors** of the sidebars and main content.
	* Hit save and make sure it compiled
* Smile

Features
-----------

* Uses [Faux Columns](http://www.alistapart.com/articles/fauxcolumns/) to make sure that both sidebars and main content's background colors go all the way to the bottom of the site. 
* Instead of images, the background colors are generated from CSS3 Gradients.
* You only have to enter the widths in one spot [DRY](http://en.wikipedia.org/wiki/Don't_repeat_yourself) as LESS passes that in all the right spot to ensure widths, paddings, and meticulously placed CSS3 Gradient stop values (which get the color variables too :) are correct.
* If you add these classes to the body they get these effect:
	* `sidebar-first` : Places the first sidebar on the left
	* `sidebar-second` : Places the second sidebar on the right
	* `two-sidebar` : One sidebar on each side 

To Do
--------

* Old WebKit needs fixed width gradients
* IE Support
	* IE 9
	* IE 8
	* IE 7
* Sidebar Shadows
* Get first sidebar after #main for SEO
* Setup menu for changing between sidebar layouts

Browser Support
---------------

**Gecko**

* Y Left Sidebar - Fixed
* Y Right Sidebar - Fixed
* Y Both Sidebars - Fixed
* Y Left Sidebar - Liquid
* Y Right Sidebar - Liquid
* Y Both Sidebars - Liquid

**Old Webkit**

* N Left Sidebar - Fixed
* N Right Sidebar - Fixed
* N Both Sidebars - Fixed
* Y Left Sidebar - Liquid
* Y Right Sidebar - Liquid
* Y Both Sidebars - Liquid

**New Webkit**

* N Left Sidebar - Fixed
* N Right Sidebar - Fixed
* N Both Sidebars - Fixed
* Y Left Sidebar - Liquid
* Y Right Sidebar - Liquid
* Y Both Sidebars - Liquid

**IE 7**

* N Left Sidebar - Fixed
* N Right Sidebar - Fixed
* N Both Sidebars - Fixed
* N Left Sidebar - Liquid
* N Right Sidebar - Liquid
* N Both Sidebars - Liquid

**IE 8**

* N Left Sidebar - Fixed
* N Right Sidebar - Fixed
* N Both Sidebars - Fixed
* N Left Sidebar - Liquid
* N Right Sidebar - Liquid
* N Both Sidebars - Liquid

**IE 9**

* N Left Sidebar - Fixed
* N Right Sidebar - Fixed
* N Both Sidebars - Fixed
* N Left Sidebar - Liquid
* N Right Sidebar - Liquid
* N Both Sidebars - Liquid

Massive Thanks
--------------------

* [Martin Rio](http://about.me/axolx)
* [Responsive Web Design](http://www.abookapart.com/products/responsive-web-design)
* [CSS3 PIE](http://css3pie.com)