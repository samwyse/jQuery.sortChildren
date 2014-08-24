jQuery.sortChildren
===================
This is a very good jsquery sorting plugin written by Rodney Rehm.  The code currently resides in a [gist](https://gist.github.com/978520), which isn't a CDN.  By providing it via jsdelivr, I hope to make it more popular.

By default, this plugin uses locale.compare for text comparisons, but provides a way to specify other ways to specify keys.  It uses the Schwartzian Transform to reduce the work it does when comparing items to a bare minimum.  For details, see the author's [blog](http://blog.rodneyrehm.de/archives/14-Sorting-Were-Doing-It-Wrong.html).
