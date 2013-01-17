Clean CSS: Coding for a better tomorrow
===================

This is a set of guiding principles to help your CSS code save the world. Or a little less ambitiously, to save us all a bit of time.

Classitis is your friend
===================

Base classes and modifier classes will make life easier down the road.
Good:
    .button {background:rgb(150,150,150); border: 1px solid rgb(200,200,200)} 
    .button .active{background:rgb(190,190,190)}

IDs are not your friend. They will steal your lunch money, and key your car. Avoid them like the plague.

Names are good
==================

Names should be lower case like this:
.button

and use hyphens when needed like this:
.animal-cat

UPPERCASE looks wacky... just say no. camelCase classes are crazy looking, don't let the camel in the tent.

De Colores
==================

rgb() baby. Prefer rgb() syntax over hex. It is cleaner and more easily dealt with in your head.

EMs for Typography & As much as possible
=========================================

EMs only for font related sizes. EMs should be preferred for all sizes where it is possible. Keeps everything focused on the content as far as rendering is concerned.

EMs in media queries are a very good idea: http://css-tricks.com/zooming-squishes/ they also allow you code around ideal line length.

Mobile First. Always.
=============================

Mobile first styles. Use Media Queries to modify for larger screens not to adapt down to smaller screens. This puts the emphasis on core experience and provides performance gains when downloading resources for mobile.

It's just the right thing to do. Media queries should be added where the design breaks, not at every screen breakpoint too. This will make your life easier.

The Long and Short of it
================================

When at all possible use the shorthand variations of styles.

So...

font: normal normal 16px/1.2 sans-serif;

is preferred over

font-family:sans-serif;
line-height: 1.2em;

If you aren't sure of the short hand look it up on Mozilla Developer Network... or if it is really confusing use the long hand.
