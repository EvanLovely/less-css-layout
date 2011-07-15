BetterLayout with [LESS CSS](http://lesscss.org)
==========================================

Steps
-------

* Download the [LESS Mac Compiler](http://incident57.com/less/) or any other compiler. Add the `/css` folder.
* Open `/css/variables.less` and set these variables:
	* Site Width (Can choose from either a fixed or liquid layout)
	* Site Padding (Takes it away from the width, so your width is actually how wide the site is).
	* Sidebar width with only 1 sidebar, or 2 separate width settings  when 2 sidebars are present.
	* Sidebar Paddings.
	* There is no #main content width setting as all above widths & paddings get subtracted from the site width.
	* **Colors** of the sidebars and main content.
	* Hit save and make sure it compiled

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

* Full WebKit support
* IE Support
	* IE 9
	* IE 8
	* IE 7
* Sidebar Shadows
* Turn php and the includes into a single html file for easy demo purposes
* Get first sidebar after #main for SEO
* Setup menu for changing between sidebar layouts

Massive Thanks
--------------------

* [Martin Rio](http://about.me/axolx)
* [Responsive Web Design](http://www.abookapart.com/products/responsive-web-design)
* [CSS3 PIE](http://css3pie.com)