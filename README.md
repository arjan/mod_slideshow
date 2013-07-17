mod_slideshow
=============

Slideshow module for Zotonic.

Show a collection as a media item, each part of the collection being
one slide in a slideshow.

Basically:

* Enable mod_slideshow
* Create a collection
* Add images to the collection.
* Then use the ``{% media collection_id %}`` tag to display the
  slideshow. Make sure you add the lib files z.cycle.js and
  zp-slideshow.css to your template.
