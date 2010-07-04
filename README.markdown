Slide Show (S9) Template Pack - S6 Blank
========================================

The [S6 Blank](http://github.com/geraldb/s6) package bundled up into 
a Slide Show (S9) template pack.

Note, this template pack includes **no** vector graphics gradient themes "out-of-the-box".
The background is blank (white) and the text color is black.
 
## Try It Yourself - How To Use the Template Pack

If you want to try it yourself, install (fetch) the new template pack. Issue the command:

    $ slideshow -f http://github.com/geraldb/slideshow-s6-blank/raw/master/s6blank.txt

To check if the new template got installed, use the `-l/--list` switch/command:

    $ slideshow -l

Listing something like:

    Installed templates include:
       s6blank.txt (/home/gerald/.slideshow/templates/s6blank/s6blank.txt)

Now you're ready to use it using the `-t/--template` switch. Example:

    $ slideshow -t s6blank.txt tutorial

That's it. 


## Troubleshooting 

Trouble downloading? Do you have a direct internet connection? If not, configure your proxy using
the `HTTP_PROXY` environment variable. Sample:

    HTTP_PROXY=http://234.445.454:4341

Or with user credentials (that is, login and password):

    HTTP_PROXY=http://gerald:topsecret@234.445.454:4341

If all fails, you can always download the template pack on your own (using lets say `git` itself)
and than move the souces into your templates folder (that is, `~/.slideshow/templates`).

## Questions? Comments?

Questions? Comments?
Send them along to the [Free Web Slide Show Alternatives (S5, S6, S9, Slidy And Friends) Forum/Mailing List](http://groups.google.com/group/webslideshow).
Thanks!
