# Antergos installer fixes

Here you'll find scripts that fix known Antergos installer issues. If you encounter installation problems relates to missing packages, this may help.

## Scripts
### fix-packages-xml
- Start the Antergos installer from the USB stick (or ISO on the virtual machine).
- When cnchi (the installer program) window starts, close the cnchi window.
- Give the following commands at the terminal:
<pre>
wget -q -O fix-packages-xml https://github.com/manuel-192/Antergos/raw/master/antergos-installer-fixes/fix-packages-xml
sudo bash fix-packages-xml
</pre>
You can also give your list of packages to remove as parameters to fix-packages-xml.

## Changes:

2019-Apr-05: Added fix-packages-xml.
