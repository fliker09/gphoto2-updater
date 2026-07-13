gphoto2-updater
===============

This script allows to install the latest development or stable releases of gphoto2 and libgphoto2 based on:
[git repositories](https://github.com/gphoto/)

This script was initially created for Raspbian http://www.raspbian.org and Raspberry Pi http://www.raspberrypi.org currently tested for:
 - Ubuntu 18.04 till 24.04 (26.04 haven't yet tested, but I am pretty sure it should work just fine)
 - Debian 9 till 13

Created and maintained by Gonzalo Cao Cabeza de Vaca and Alexandru Barbovschi.

Special thanks to @scribblemaniac for his support on this project.

How-to use
==========
To download and run the latest script's version just be sure you are connected to the Internet and run:

```
$ wget https://raw.githubusercontent.com/fliker09/gphoto2-updater/master/gphoto2-updater.sh && wget https://raw.githubusercontent.com/fliker09/gphoto2-updater/master/.env && chmod +x gphoto2-updater.sh && sudo ./gphoto2-updater.sh
```

This will download both .env and script files and run the script. Then select between stable and development versions.

### After installation you still see a previous version of gphoto2 and libgphoto2
You probably have another of libgphoto2 installed from some other source, most likely apt. The script does not remove such packages, as they are often used by some other libraries and/or apps. Please restart whatever app or terminal session was using gphoto2 before and try again.

LICENSE AND DISCLAIMER
======================

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.
You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
