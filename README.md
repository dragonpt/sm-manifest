SaberMod Unofficial Manifest
===========

I'm trying to make it easier for folks to build SaberMod toolchains.

All you have to do is run:

repo init -u https://github.com/Cl3Kener/sm-manifest.git -b 4.9.0 

followed by

repo sync


Once you have all components locally go to build directory and run either of the 4.9 scripts.  

"androideabi" is for ROMs and "eabi" is for kernels.  


When you finished running the script you will find a toolchain located in tmp/ labeled either eabi or androideabi depending on which script you ran.  

This is your new SaberMod Toolchain!

Enjoy!
