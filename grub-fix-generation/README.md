# grub-fix-generation

This small script fixes the invalid generation of the <i>initrd</i> line(s) in file <b>/boot/grub/grub.cfg</b>.
The problem concerns programs in packages <b>grub</b> and <b>os-prober</b>.
They generate incorrect initrd line, lacking one of the two required parameters for some operating systems.

When this problem gets fixed upstream, you should reinstall packages 'grub' and 'os-prober'
and uninstall this script.
