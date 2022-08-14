# KeyboardLayouts

This repository contains keyboard layouts for the [Microsoft Keyboard Layout Creator (MSKLC)](https://www.microsoft.com/en-us/download/details.aspx?id=102134).

This tool is no longer supported by Microsoft, but still works under Windows 10. 

However you will have to either:
* Enable 8.3 format filenames before installing it (which I don't recommend)  
  or

* Copy the file in the program directory  
  `c:\\Program Files (x86)\\Microsoft Keyboard Layout Creator 1.4\\`  
  into a directory whose path only uses names in 8.3 format (and no spaces), e.g.  
  `C:\\MSKLC\\`

  and run the application from that directory.

If you want to regenerate a keyboard layout which is already installed, you will have to:
 - go to the language settings and
   - select a different keyboard layout
   - remove the custom keyboard layout
 - go to "Add or Remove Programs"
   - unistall the custom keyboard layout

When you build the keyboard installation, it is always build to `users\\<user name>\\documents\\<layout name>`.

If the new or modified keyboard layout does not appear to work, restarting windows may help.

*Note: An alternative to the Microsoft Keyboard Layout Creator is [KbdEdit](http://www.kbdedit.com/). 
If you want to create your own keyboard layout, you might prefer
to try this tool.*