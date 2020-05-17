CS50 Project 0

Mark Wyatt      5/14/2020

This project fulfills the requirements of project 0.  It is the beginnings of an online gallery program.  Since it does 
not have server-side scripting, the functionality is minimal.  The only gallery available is an image gallery and
the create gallery function does not work.  Additionally, all the images from the sample gallery are hard-coded, which
ideally would be automated.

Files:

index.html      This is the launch page.  It includes a "get started" link as well as a header (common to all HTML files)
                that provides a link to the launch page (via the image) and direct links to the "dashboard" and "help" pages.
                Formatting for the header is accomplished with an html table.

dashboard.html  This page asks the user to choose to either "view" a gallery or "create" a gallery.  Again formatting for the
                view and create options are accomplished with a 2x2 html table.

selectgallery.html  This page allows the user to select (via a dropdown form) a gallery to view.  Currently there is only
                    one and it is hard-coded.

viewgallery.html    This page displays the actual gallery of images.  Each image is selectable and will open in a new window.
                    so that it doesn't interfere with the web site's functionality (ability to naviate to other web pages).  Viewgallery.html uses Bootstrap's grid model, along with Bootstrap's card component to label each picture.

creategallery.html  This page is a placeholder for future functionality.  It does use a mobile responsive @media query to change
                    the page text if the window is shrunken.

help.html       This is a standard help page.  It includes an unordered list, an ordered list, and anchor tags to link different
                parts of the page.  This file uses SASS (a variable, nesting for formatting of the lists, and inheritance for alignment
                of the header).

mystyle.css     This is the sole .css file in this project.  It has numerous CSS properties, selectors, including the #id and
                .class selectors.  Every page uses this .css page as it has styling geared for all of the web pages.

mystyle.scss    This is the SASS file that compiles to mystyle.css

galleria.jpg    This is the title image on all html pages.

_scss <dir>     This folder contains mystyle.scss, which compiles to mystyle.css

_css <dir>      This folder contains mystyle.css and other output files from SASS

Galleries <dir> This is the asset folder that contains the galleries of images (sample gallery)