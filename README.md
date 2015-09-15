# flexbox-challenge

This demo illustrates a way of achieving a specific challenging layout via flexbox.
The original source of the challenge is [this thread](https://lobste.rs/s/fudw9z/the_future_of_layout_with_css_grid_layouts/comments/tmghsh#c_tmghsh).

[View the Demo](http://adripofjavascript.com/flexbox-challenge/index.html)

The requirements of the layout:

> The chunks were site logo, navigation links, copyright footer, and article body text.
>
> On the desktop layout, logo and navigation are in a left-hand sidebar, with logo at the top and navigation stretched to fill all the remaining space. Body is in the “other column”, and footer is below both the sidebar and the body, stretching across everything. Everything is relative to the whole page, no viewport-based positioning or sizing, except probably the width of the sidebar, but don’t worry about that for the sake of the exercise.
>
> On the mobile layout, there’s only one column. From top to bottom, the elements are logo, body, navigation, and footer. Navigation is below body because there’s a fair number of links; mobile Wikipedia does this, and it works well there.
>
> The example was separating these cases using a media query based on something like a 400px threshold for viewport width, but that isn’t particularly essential; the point is only to try to do them with pure css.
>
> I’m not sure whether the preferred document order for accessibility would be logo, body, navigation, footer, … the other thing that occurs to me is logo, navigation, body, footer. Feel free to pick one and try to make it happen, for bonus points.