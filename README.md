retroGallery
============

Gallery jquery plugin for wordpress.

Used at http://www.spillmuseet.no. For a demo look at the bottom of this article:
http://www.spillmuseet.no/2014/03/03/ukens-samler-anders-remi-rusten/

Attach to every gallery node in articles to apply retroGallery to each gallery.

This is how it is done at spillmuseet


$('.gallery').each(function(key, node) {
  $(node).retroGallery();
});