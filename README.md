# octoenv
Octoprint setup for Raspberry PI and Magnum3D printers

## Contents

  * __timelapse*__ - scripts for making GoPro timelapses
  * __octo.update__ - update OctoPrint to latest version
  * __octo.run__ - run OctoPrint as daemon
  * __octo.stop__ - stop OctoPrint daemon
  * __mjpg.run__ - run mjpeg-streamer
  * __mjgp.update__ - update jpeg-streamer to latest verison
  
## Installation

__Requires Raspbian Jessie 8 Based__

1. First install essential software
``
sudo apt-get git curl
``

2. Checkout this project into /home/pi folder
``
git clone https://github.com/Magnum3D/octoenv/
``

3. Run ./octo.update from octoenv
4. Run ./mjpg.update from octoenv

