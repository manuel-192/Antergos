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

And you don't have to add the pacman key (gpg key) anymore if you already have done so.
<br><br>
Currently (2019-Mar-17) this repo includes the following AUR packages:
- bashdb
- ccrypt
- pacman-aur
- python3-gpg_batch_sign
- repo-add_and_sign
- virtualbox-ext-oracle

Special note: any of the packages here may be removed if the corresponding Antergos packages are made available.
