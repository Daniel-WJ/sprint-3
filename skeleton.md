## What happens to the layout when you resize the screen to less than 550 px?
The Skeleton CSS uses responsive webpage, meaning the the webpage resizes itself to fit with the device you're using by judging the size of your browser and assuming the device.

## How do you think that works?

This feature works through the use of the min-width CSS property meaning that the webpage changes what is shown or hidden depending on the minimum-width

/* Mobile first queries */

/* Larger than mobile */
@media (min-width: 400px) {}

/* Larger than phablet */
@media (min-width: 550px) {}

/* Larger than tablet */
@media (min-width: 750px) {}

/* Larger than desktop */
@media (min-width: 1000px) {}

/* Larger than Desktop HD */
@media (min-width: 1200px) {}
