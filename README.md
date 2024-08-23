# perl-Linux-loadavg

Linux::loadavg
==============

INTRODUCTION

This module is purely for Linux usage only. A similar module
exist for Solaris; Solaris::loadaverage. Actually Linux::loadavg
is a direct derive from Solaris::loadaverage. 

INSTALLATION

To install this module type the following:

   perl Makefile.PL
   make
   make test
   make install

DEPENDENCIES

   None

COPYRIGHT AND LICENCE

Copyright (C) 2007-2024, Niels van Dijke, http://perlboy.net

REMARKS

The author is aware of the existence of another XS getloadavg module:
BSD::getloadavg. This module however can not be swapped out in the way
both Linux::loadavg and Solaris::loadavg can be done. See:
'examples/osdetect.pl'. 

CREDITS

Credits should go to:

Alexander Golomshtok (http://search.cpan.org/~agolomsh/)
  Author of Solaris::loadavg

Dan Kogai (http://search.cpan.org/~dankogai/)
  Author of BSD:::getloadavg package and 'benchmark.pl'

