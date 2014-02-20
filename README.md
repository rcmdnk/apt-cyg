apt-cyg
=======

:warning:

The original author is now actively including updates:
[transcode-open/apt-cyg](https://github.com/transcode-open/apt-cyg).

All updates in this repository are already adopted in there.
Therefore, it is better to use above.

- - -

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

