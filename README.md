# READ ME

This is a [RANCID](http://shrubbery.net/rancid/) driver for
[Arista Networks'](http://aristanetworks.com) devices.

Arista support is already present in RANCID, but this is where
"bleeding-edge" development is done.

## Using the "bleeding-edge" verison yourself

If you want to use this version, first download the RANCID
source from [the RANCID web site](http://shrubbery.net/rancid/),
and extract it.  Then copy the `*.in` files from
the Arista-Rancid `bin/` directory into the RANCID source
tree, and build RANCID as usual.

### Can't I just copy the files into my existing installation?

Yes, you might get away with just editing the `#!` line
and making arrancid executable and copying it.  If this goes
wrong, though, please try the "build RANCID" method before
asking for help.
