---
layout: default
title: "Adding SUTD Network Printers on Ubuntu(Gnome)"
permalink: /adding_sutd_network_printers_gnome/
---

# About
Since the Pi Lab only has instructions for adding the networked printers on MacOS and Windows, heres documentation for adding the printers on Ubuntu and other Linux Distros

Screenshots are from GNOME Desktop Environment so you might have to look around for the correct buttons and dialog if you are on a different Desktop Environenment

These steps are referenced from the MacOS instructions provided in the Pi Lab

# Steps for adding Pi Lab Printers to Ubuntu
1. Go to Settings
2. On the sidebar, scroll down and click on **Devices**. This should bring up a new sidebar
![](select_devices.png)
3. On the new sidebar, click on **Printers**
![](select_printers.png)
4. You will see a list of available printers
5. Ignore it and scroll all the way down until you see **Additional Printer Settings** (on the bottom right). Click on it
![](select_additional_printer_settings.png)
6. A new window called **Printers - Localhost** or something along those lines should appear
7. Click on the  **+ Add** button (most likely on the top left of the window)
![](select_add.png)
8. The window to configure a new printer should open
9. Click on **Network Printer** to expand the dropdown
![](select_network_printer.png)
10. Select **LPD/LPR Host or Printer**
![](select_LPD_printer.png)
11. Under **Host** enter `sct-ps-x` and under **Queue** enter one of the following. Once done, click **Forward** at the bottom of the page
  + `Mono-A4` for Black/White A4 Size Prints
  + `Mono-A3` for Black/White A3 Size Prints
  + `Color-A4` for Color A4 Size Prints
  + `Color-A3` for Color A3 Size Prints
  > There are more printers for A2, A1 and A0 printing but those likely require proprietary drivers
![](enter_host.png)
12. You will now be prompted to choose a driver. Select **Select printer from database** and choose **Generic**. Once done, click **Forward**
![](select_driver1.png)
13. Under **Models**, select **Postscript** (on the left side) and under **Drivers** select **Generic Post Script Printer** (on the right side). Click **Forward** when done
  > There may be several similar options, choose the one that is recommended by the system
![](select_driver2.png)
14. You will now be asked to name the printer as well as provide a description and a location. Fill these in however you like but here is a sample
![](enter_name.png)
15. Click **Apply** to add your new printer
16. **PROFIT**
