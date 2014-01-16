apt-cyg
=======

A command-line software installer for Cygwin.
Original version is available in http://code.google.com/p/apt-cyg/.

Recently, Cygwin mirror sites change their directory structure,
and original apt-cyg doesn't work on them anymore.

In this repository, an updated version of apt-cyg which can be used for
the new Cygwin mirror site strucuture is available.


## Installation

    $ git clone git@github.com:rcmdnk/apt-cyg.git
    $ cp apt-cyg/apt-cyg /bin/
    $ rm -rf apt-cyg # if the local repository is not necessary

## Usage
13/08/2013 update:
This version can be used exactly same way with original apt-cyg.
Architecture will be set automatically.

If you want to specify mirror site, put x86 (for 32 bit machine) or x86_64 (for 64 bit machine) at the end of URL

    $ apt-cyg update -m ftp://mirror.mcs.anl.gov/pub/cygwin/x86_64/


[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/rcmdnk/apt-cyg/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

