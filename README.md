# The MiSTer Database For Alternative Versions Of Core 

This is a database for the MiSTer project that downloads alternative versions of several cores that contain features not found in the main version.  These cores are added to the "Other" folder.

To use it simply copy and paste the below to the bottom of your downloader.ini file (found at: /media/fat/downloader.ini )

```ini
[ajgowans/alt-cores]
db_url = https://raw.githubusercontent.com/ajgowans/alt-cores/db/db.json.zip
```

 ## Currently Included Cores

 Sega Genesis +
 
 Playstation 2x
 
 Nintendo 64 2x


  ## Additional Information

  The Sega Genesis core is the old core that was replaced by the Nuked Mega Drive core.  It is less accurate, but contains some features not present in the new core.  This core         points to a "Genesis" folder from the OSD when selecting roms (not "MegaDrive" like the new core).    
  

  The N64 "80mhz" core, and The PSX 2X core, are overclocked compared to the offical cores in Main, and original hardware.  This can lead to improved FPS in some games, but also can lower stability in others and can introduce bugs.  If you are using these then anticipate you may come across issues.



  Issues with these cores likely won't be addressed because they are either out of spec of the original hardware or no longer maintained.
