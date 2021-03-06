What Week Is It?
================

Version 2.2
-----------

Something for Southampton uni that tells you what week it is.

For an actual working example (and possibly this software's only
practical use): http://whatweekisit.soton.ac.uk/

Pat and I became rather frustrated that the uni's timetabling
system runs on a week system but real life runs on a date system
and there appears to be no quick and easy way to determine which
week of the academic year we're currently in. As I've just
released the open data for the university's academic sessions
until the year 2020, I felt this was an appropriate way of
showing it off.

Installing it is a little hasslesome, you need to have
the Fatfree Framework, Chris's Graphite library and
ARC2 (a dependency of Graphite) although all these are
available through git, so I've added them as submodules.
Directory paths are a lot better in this version. Docs
for installing and configuring are in the /docs
directory.

To actually use it, go to / on the server. That's it. If you
want feed caching, the ./var/feeds directory needs to be writable
by the web server.

Updates
-------
This is now at version 2.2. I'll probably have to make it conform
to the University branding guidelines for it to become an official
supported service, but other than that I don't intend to add any
more features - there's already far too many for a silly little
page that is only supposed to tell you what week it is. However,
if you find a bug that prevents it from functioning, I'm totally
happy to continue supporting it, I'm just not adding any extra
functionality.
