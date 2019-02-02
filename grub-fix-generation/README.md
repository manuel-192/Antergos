# grub-fix-generation

This small script fixes the invalid generation of the initrd line in file /boot/grub/grub.cfg.
The problem concerns programs in packages grub and os-prober.
They generate incorrect initrd line, lacking one of the two required parameters.

When this problem gets fixed upstream, you should reinstall packages 'grub' and 'os-prober'
and uninstall this script.
