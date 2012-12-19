
aciTypewriter - Typewriter effect with jQuery

Features:

- possibility to apply the effect not only on text content but also to other
  objects like images, etc.;

- supports any tag within the area to which it's applied so that the text
  contents may contain any formatting;

- the DOM structure changes but only at the text nodes level and at the end
  it returns to its original state;

- the effect can be applied at a word or character level with a fade-in
  animation;

- simultaneously multiple effects can be run and with different settings
  (different display speed for example);

- supports several callback functions that allow chaining multiple effects so
  that at the end of a area the effect can move to the next;

- not only allows the inclusion of image objects etc. to be displayed only when
  the entire text contents - up to object - was already shown, but allows
  elements like li, table etc. to be hidden where otherwise might be
  partially displayed;

- allows the use of jQuery selectors at initialization to specify various
  elements that contribute to effect so that it can adapt to each case
  as required.

Simple usage:

$('body').ready(function(){

    $(document).aciTypewriter({autoStart:true});

});

aciTypewriter jQuery Plugin v1.0
http://acoderinsights.ro

Copyright (c) 2012 Dragos Ursu
Dual licensed under the MIT or GPL Version 2 licenses.

Require jQuery Library http://jquery.com

Date: Fri Dec 14 23:05 2012 +0200
