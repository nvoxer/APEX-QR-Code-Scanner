 # APEX-QR-Code-Scanner
 
Updated functionality of the scanner. Should fix blurry or unreadable codes.  just replace the qsrc.pkgd.min.js file in your Apex environment with the one provided here (build/qsrc.pkgd.min.js)

-updated Html5QrCode library to last version

-added combo box to select cameras from a list

-default to last device in the camera array, usually the main camera

-added zoom for better code readability
 
 ![](https://img.shields.io/badge/ORACLE-APEX-success.svg) ![](https://img.shields.io/badge/Plug--in_Type-Region-orange.svg) ![](https://img.shields.io/badge/Avaiable%20for%20APEX-5.1.3%20or%20above-blue)

![Screenshot](https://github.com/RonnyWeiss/APEX-QR-Code-Scanner/blob/master/screenshot.gif?raw=true)

This Region Plug-in is used to scan codes. If any string has been detected an APEX Item can be set, Dynamic Action can be fired or JavaScript can be executed.
The following formats are supported: QR_CODE, AZTEC, CODABAR, CODE_39, CODE_93, CODE_128, DATA_MATRIX, MAXICODE, ITF, EAN_13, EAN_8, PDF_417, RSS_14, RSS_EXPANDED, UPC_A, UPC_E, UPC_EAN_EXTENSION

If you don't to know how to install this Plug-in in Apex, please take look at the Documentation of Oracle APEX.

To control the QR Code Scanner you can fire events on th QR Code region. The following events are supportet:

apex.region("region_id").pause(); => stop Scanner Video

apex.region("region_id").start(); => start Scanner video

apex.region("region_id").refresh(); => reset the currentValue and the item

apex.region("region_id").setFacingMode(); => change camera

For working Demo just click on:

https://apex.oracle.com/pls/apex/f?p=103428

If you like my stuff, donate me a coffee

[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.me/RonnyW1)

**Important clarification: My work in the development team of Oracle APEX is in no way related to my open source projects or the plug-ins on apex.world! All plug-ins are built in my spare time and are not supported by Oracle!**
