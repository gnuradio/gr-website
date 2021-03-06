# Website Update: Goodbye WordPress!

Today we switched over from a static dump of our old WordPress instance to a new website based on markdown files and rendered by a custom Flask application.

This switch was necessary due to continuous severe security vulnerabilities in WordPress and a lack of knowledge about successfully hardening WordPress (if that's even possible at all) among GNU Radio officers.

Our news, blog and event content is now (mostly) generated from the [gr-website repository](https://github.com/gnuradio/gr-website).
The GRCon 2018 website has been ported to the new structure as well. Content from previous GRCons is in the process of conversion.

There are still some bits and pieces missing which will be worked on in the upcoming weeks. Therefore the GNU Radio website might experience more frequent maintenance downtime. We try to keep downtimes as short as possible.

A website overhaul wouldn't have been possible without the great work of the GNU Radio officers Nate Temple and Andrej Rode.
