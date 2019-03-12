# Prebuilt AUR packages for Antergos users.

This repo includes certain hand picked packages for Antergos users. The packages are built using the AUR PKGBUILD definitions.
<br>
You may write to https://forum.antergos.com about any issues with this repo.
<br><br>
How to use this repo? Check these [instructions](https://github.com/manuel-192/Antergos/blob/master/Antergos-packages/README.md)
with the following modifications:
- the repo info is slightly different:
<pre>
[mgit-aur]
Server = https://github.com/manuel-192/Antergos/raw/master/Antergos-packages-aur
SigLevel = Required
</pre>
- the above repo definition needs to be placed before the <b>[antergos]</b> repo definition.

And you don't have to add the pacman key (gpg key) anymore if you already have done so.
<br><br>
Currently (2019-Mar-12) this repo includes the following AUR packages:
- yad
- yay
- inxi

Special note: any of the packages here may be removed when the corresponding Antergos packages are made available.
