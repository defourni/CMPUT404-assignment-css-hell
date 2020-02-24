Assignment: CSS Hell
====================

You will skin 3 project gutenberg stories with custom CSS.

You will skin 2 versions of a possible professional homepage for your
self with 2 versions of CSS.

Read requirements.org

Read this comic http://theoatmeal.com/comics/design_hell

git clone https://github.com/abramhindle/CMPUT404-assignment-css-hell.git

License/Copyright
=================

Textual content is copyright Abram Hindle (C) 2013 under the CC-BY-SA
4.0 unported license. Attribution should be a hyperlink to the
repository and (C) 2013 Abram Hindle visibile in the text.

Code is licensed under the Apache 2.0 license.

Part 1
=================
All of the HTML files I chose to theme has css embedded directly in the HTML header.
These files had to be modified from embedded css to linking to a common css stylesheet 
(called gutenberg.css in this case) by adding the line:
 <link rel="stylesheet" type="text/css" href="gutenberg.css">

Google Fonts "Cinzel" and "Prata" are imported for with the code:
<style>
   @import url('https://fonts.googleapis.com/css?family=Cinzel|Prata&display=swap');
</style>

Image files were downloaded from the project gutenberg servers and kept locally in a folder "images"
This folder structure was the same in all of the source html files I chose.

For image filename conflicts, the names were manually changed. 
However, this could be done with a folder structure to generalize the process.
If a large number of books were being hosted, there would likely be more filename conflicts.




