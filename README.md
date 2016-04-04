# knittington-64-bit-ubuntu-modified-make.sh
This is a modified make.sh file to get knittington running on my ubuntu 64bit system

Follow these instruction before:

1/Install: 
  libsdl1.2debian
  libsdl1.2-dev
  libsdl2-dev
  libfreeimage3
  libfreeimage3-dev

2/ Download the knittington-master zip file :https://github.com/stg/knittington

3/ Replace the linux-gui-make.sh file by the new one here

4/ execute in the terminal:
   ./linux-gui-make.sh

chmod u+x linux-gui-make.sh 
if you get a "permission denied" message

5/ THan go to the file knittington-master/bin-linux and execute:
   $./gui

And knittington should work!
Thanks to Gratefull Frog for the help! https://github.com/gratefulfrog
