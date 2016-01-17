# SMC Fonts package for chakara OS

This repository contains the CCR PKGBUILDS for the fonts that SMC has released so far. This is derived from AUR repository by Aashik

In addition to individual font packages, it also contains a meta package, available at https://chakraos.org/ccr/packages.php?ID=7491


# Removing old fonts

Chakra hasnt updated Malayalam fonts after 2008. So I suggest to remove those fonts before installing these new fonts 

sudo rm  /usr/share/fonts/TTF/RaghuMalayalamSans2.ttf  /usr/share/fonts/TTF/Dyuthi*  /usr/share/fonts/TTF/Kalyani* /usr/share/fonts/TTF/Meera* /usr/share/fonts/TTF/Rachana* /usr/share/fonts/TTF/suruma* /usr/share/fonts/TTF/AnjaliOldLipi*

# Installing using ccr

To install all fonts in one go, issue this command. 

ccr -S fonts-smc

Additional switches are available to make ccr non interactive, explore if you like to.

You can also install the individual packages. Folllowing commands will install all fonts as well. 

ccr -S fonts-smc-anjalioldlipi

ccr -S fonts-smc-chilanka

ccr -S fonts-smc-dyuthi

ccr -S fonts-smc-keraleeyam

ccr -S fonts-smc-meera

ccr -S fonts-smc-rachana

ccr -S fonts-smc-raghumalayalamsans

ccr -S fonts-smc-suruma

