# grub-fix-generation

This small script fixes the generation of the initrd line, regarding packages grub and os-prober.
Those programs generate incorrect initrd line, lacking one of the two required parameters.

When this problem gets fixed upstream, you should reinstall packages 'grub' and 'os-prober'
and uninstall this script.
