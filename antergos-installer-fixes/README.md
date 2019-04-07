# Antergos installer workarounds

Here you'll find scripts that fix known Antergos installer issues. If you encounter installation problems relates to missing packages, this may help.

## fix-packages-xml
### Description
Fixes problems with certain missing packages
## Usage
- Start the Antergos installer from the USB stick (or ISO on the virtual machine).
- When cnchi (the installer program) window starts, close the cnchi window.
- Start a terminal program and give the following commands that will also restart the cnchi installer:
<pre>
wget -q -O fix-packages-xml https://github.com/manuel-192/Antergos/raw/master/antergos-installer-fixes/fix-packages-xml
sudo bash fix-packages-xml
</pre>
You can also give your list of packages to remove as parameters to fix-packages-xml.
<br><br>
If you find any new installer issues, please report them at the [Antergos forum](https://forum.antergos.com/category/3/installation).

# Changes:

2019-Apr-05: Added fix-packages-xml.
