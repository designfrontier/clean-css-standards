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

