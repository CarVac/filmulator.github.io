+++
title = "Scrollbars in Filmulator"
template = "blogpage.html"
aliases = ["scrollbars"]
+++

Ever since the user interface was first implemented in Filmulator, the scrolling in various aspects has been... subpar. Scrolling by flicking with the mouse was always fine, but scrolling with the mouse wheel was jerky when scrolling slowly and uncontrollable when scrolling quickly. Friction was too low when mousewheel scrolling because it was tuned for flick scrolling, making long scrolls take seconds to coast to a stop.

On top of that, there were no scrollbars at all, making it unclear to new users what could be scrolled and what could not, and making it impossible to know where you are within the scrollable region.

However, both of these issues have now been remedied.

![Filmulator scrollbar illustration](/images/screenshots/0.9_scrollbars.png)

Scrolling now approximates a fixed distance per click of the scrollwheel, and when mousewheel scrolling the friction is increased so that scrolling is more immediate. Additionally, mousewheel scrolling was fixed in the Lens Selection Box, where it used to occasionally zoom the image view when scrolling rapidly, and mousewheel scrolling was added to the Date Histogram, which before only had flick scrolling.

Additionally, all views that scroll now have scrollbars that indicate where you are in the view and can be dragged to control the position of the view. The scrollbars are narrow and unobtrusive, but when approached with the mouse they expand to make a larger mouse target.

Get the latest nightly builds of Filmulator at the link at the bottom of the [download page](/download).
