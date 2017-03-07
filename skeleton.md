#Skeleton

##What happens to the layout when you resize the screen to less than 550 px.
##How do you think that works?

At less than 550px the elements shift from a side-by-side multi-column layout
to a single file top-to-bottom full width small-device-friendly layout.

The main CSS styles define a single column, 'full-width' (though in this case
80%) layout for small devices.
At widths of 550px or greater, a <code>@media</code> query with a <code>min-width</code>
of <code>550px</code> will alter the width of the elements so they can sit
side-by-side by taking up only a part of a row and making use of the greater
screen real estate.
