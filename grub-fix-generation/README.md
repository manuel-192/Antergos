# grub-fix-generation

## Overview

This small script fixes the generator <b>grub-mkconfig</b> that currently generates incorrect <i>initrd</i> line(s) into file <b>/boot/grub/grub.cfg</b> for some operating systems.
The problem concerns two packages: <b>os-prober</b> (for the most part) and also <b>grub</b>.
Together they cause generation of initrd lines that may lack one of the two required parameters.

When this problem gets fixed upstream, you should reinstall packages 'grub' and 'os-prober'
and uninstall this package.

Note: installing this package installs also a special version of file /usr/bin/update-grub. If you already have that file, then it is backed up first (with suffix .bak.\<date\>).

## Usage
Run the script (required only once!):
<pre>
sudo grub-fix-generation
</pre>
and re-generate grub.cfg:
<pre>
sudo grub-mkconfig -o /boot/grub/grub.cfg
</pre>
Check that the initrd lines in /boot/grub/grub.cfg are valid now.

## See also
https://github.com/manuel-192/antergos-m
