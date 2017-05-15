#teacozy

Some comments on implementation details:

- I decided against a reset.css and just set the values to get the desired effects in Chrome and Firefox. I learned a lot about what user agent stylesheets do and will likely take an adapted version of normalize.css as a basis for future projects.

- To ensure that the onpage links jump to the right place I chose a top-border for the #mission and #locations sections and a padding for the #featured-tea.

- My images have an ARIA-role of "presentation" to let screenreaders skip them but also an alt-text to be displayed in case the image does not load successfully.

-  I scaled down the gallery images' source files to their size as specified in the mock using gimp. Also the logo.

- I did not crop the background image files but used positioning to get the desired details to show.
