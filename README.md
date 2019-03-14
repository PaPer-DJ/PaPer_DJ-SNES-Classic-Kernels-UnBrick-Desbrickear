# PaPer_DJ-SNES-Classic-Kernels-UnBrick-Desbrickear
[ UnBrick INFO ] Original Kernel Releases for All SNES and NES Classic Consoles.


So, you used Hakchi2.30, fucked your console, and now it just shuts down right away... and of course you want to fix it, right?

Well, depending on which system you have, you'll have to find one of these clean kernel backups from your favorite search engine (hint: search for the filename in quotes)

* Super Nintendo / Super Famicom Classic
kernel-dp-shvc-release-v2.0.12-0-gbff4fb3.img
kernel-dp-shvc-release-v2.0.14-0-gd8b65c6.img
kernel-dp-sneseur-release-v2.0.13-0-g9dca6c5.img
kernel-dp-sneseur-release-v2.0.14-0-gd8b65c6.img
kernel-dp-sneseur-release-v2.0.7-0-geb2b275.img
kernel-dp-snesusa-release-v2.0.13-0-g9dca6c5.img
kernel-dp-snesusa-release-v2.0.14-0-gd8b65c6.img
kernel-dp-snesusa-release-v2.0.7-0-geb2b275.img

* Famicom Classic
kernel-dp-hvc-release-v1.0.5-0-g2f04d11.img

* NES Classic (2016 Release)
kernel-dp-nes-release-v1.0.2-0-g99e37e1.img
kernel-dp-nes-release-v1.0.3-0-gc4c703b.img

* NES Classic (2018 Release)
kernel-dp-nes-release-v1.0.7-0-g4ea4041.img

* Shonen Jump Special Edition Famicom Classic
kernel-dp-hvcj-release-v3.0.1-0-gad315e1.img


Then after you have the proper one for your system, you're going to need to download the latest release of Hakchi2 CE from http://github.com/teamshinkansen/hakchi2/releases and extract it to a nice and clean folder.

Then you grab the unfuck hmod from https://hakchi.net/hakchi/hmods/_unfuck.hmod and install it like any other mod, but you'll need to do it through FEL mode (hold reset when powering on the system)

Enter FEL mode once again and select Kernel > Uninstall, this will prompt you for a clean kernel dump (see above).

hakchi should be removed from your system and it will start normally.

At this point, you can re-install hakchi using Hakchi2 CE and everything will work normally.
