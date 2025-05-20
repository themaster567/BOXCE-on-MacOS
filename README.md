This works with some caveats. 
* X-Piratez doesn't work at the moment. There's a problem with one of the tilesets used for the font that causes it to claim the file isn't in an 8-bit colorspace in spite of it just being a few shades of grey and black. All attempts to modify the file to fix it failed.
* You must run xattr -d com.apple.quarantine openxcom.app/ on the .app file for the program to work, as I'm not paying $100 a year to sign the file just so it doesn't get flagged as unsafe by MacOS.
