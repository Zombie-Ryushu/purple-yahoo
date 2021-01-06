# purple-yahoo

## Getting started
1. Ensure that pidgin is installed, i.e. `sudo apt-get install pidgin`
1. `sudo apt-get install libglib2.0-dev` (probably others too, pidgin-dev?)
1. Grab a pidgin source version, i.e. `wget https://sourceforge.net/projects/pidgin/files/Pidgin/2.13.0/pidgin-2.13.0.tar.gz/download`
1. `tar xzf download`
1. Change into your pidgin directory, i.e. `cd pidgin-2.13.0`
1. Then change into the libpurple plugins directory `cd libpurple/plugins`
1. Then clone this repo, i.e. `git clone https://github.com/cml37/purple-yahoo.git`
1. `cd purple-yahoo`
1. `make`
1. `cp ./libs/libyahoo.so ~/.purple/plugins`
1. Fix the above procedure since I am sure it is lacking
