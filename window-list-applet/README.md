window-list-zeripath.sdf-eu.org
===============================

Zeripath's Cinnamon Window List

This applet is a modified version of the original window-list but with features
for controlling maximized windows.

* Clicking on the Window List Button for a focused Maximized window will
  Unmaximize it. Clicking once again will Minimize it.

* Clicking on the Window List Button for a Minimized window will Restore the
  window, clicking once again will Minimize it.

* Double-clicking on the Window List Button for a Maximized window will
  Minimize the window.

* Double-clicking on the Window List Button for a Minimized or Unmaximized
  window will Maximize the window.

These features are very helpful if you wish to turn off titlebars for maximized
windows and have a flipped menu bar. I use this with the cinnamon window
buttons applet and a modified theme which removes the titlebars.

Installation
============

1. Extract the zip into a temporary directory
2. cd into that directory
3. chmod +x install.sh
4. ./install.sh
5. Press ALT-F2, type r, and press ENTER to restart cinnamon.

The install script will replace the default cinnamon window-list with my
version of the applet.

To uninstall the applet:

1. cd into the temporary directory
2. chmod +x uninstall.sh 
3. ./uninstall.sh
4. Press ALT-F2, type r, and press ENTER to restart cinnamon.