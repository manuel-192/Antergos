# grub-fix-generation

## Overview

This small script fixes the generator <b>grub-mkconfig</b> that currently generates incorrect <i>initrd</i> line(s) into file <b>/boot/grub/grub.cfg</b> for some operating systems.
The problem concerns programs in packages <b>grub</b> and <b>os-prober</b>.
They may generate initrd lines that lack one of the two required parameters.

When this problem gets fixed upstream, you should reinstall packages 'grub' and 'os-prober'
and uninstall this script.

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
