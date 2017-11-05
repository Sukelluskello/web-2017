## Disobey 2017 web site

This repository contains source code and -data for the Disobey 2017 website.
It's probably not much use to anyone, but might be interesting to look at.

Website uses the Django template engine, and its basic editing features
should work with it. For the layout, site uses jQuery for dynamic DOM manipulation,
and everything else is pretty much just JS.

The fuzz assets are in their original format and converted and compressed with
some shell script magic. (pack_fuzz.sh)
An array of fuzz assets should be then generated via another script (create_fuzzdata.sh)
and the definition generated by this should be then added to the template.

During development, the site was tested on many relevant platforms, such as:
* iPhone 5S
* Firefox & Chrome running on Linux
* Chrome, Safari running on OS X
* Jolla Tablet
* iPad Air
* Caterpillar B15 

directory misc/ contains sources for some puzzle stages.