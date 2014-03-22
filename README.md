SaberMod Unofficial Manifest
===========

I'm trying to make it easier for folks to build SaberMod toolchains.

All you have to do is run:

  repo init -u https://github.com/Cl3Kener/sm-manifest.git -b 4.9.0 

followed by

  repo sync

in the directory of your choice on the Ubuntu running computer of your choice.


Once you have all components locally go to build directory and run either of the 4.9 scripts.  

"androideabi" is for ROM compile and "eabi" is for kernel compile.  


When you finished running the script you will find a toolchain located in home/user/tmp/ (or ~/tmp for short) labeled either arm-eabi-4.9 or arm-linux-androideabi-4.9 (or something close, names subject to change but you'll be able to tell which is which) depending on which script you ran.

This is your new SaberMod Toolchain!

Enjoy!
