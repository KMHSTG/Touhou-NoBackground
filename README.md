# **Touhou Project - No Background**

These patches will remove the UI background art during gameplay, from most of the official windows Touhou games. This means that the gameplay area and various UI elements, will sit on top of a black background (similar to the earlier PC-98 Touhou games).

Note that the patches are for the original PC versions. They have not been tested with the Steam versions at all.

## Patching Instructions:

1 - Check input-files.txt for a list of all the supported games/dat files. The patcher will look for those exact filenames, so make sure they match. You can patch any combination of files at the same time (or even the entire list in one go).

2 - Extract "tnbv1.zip".

3 - Put all the dat files you want to patch into the input folder. These files will not get modified, instead the patcher will create new patched versions of them.

4 - Run "Patcher.bat", and wait while it creates the new files. When it has finished, you can grab your original dat files from the input folder, and the patched versions from the output folder.
  
##### NOTE 1: The JP EoSD dat file has japanese characters in the filename, and if you're not using japanese locale, this might prevent you from being able to patch it. So a workaround is included, that can be used for this file if necessary: If you rename the file to "06CM.DAT", the patcher will still be able to find and process it properly. You can then take the patched 06CM.DAT from the output folder, and change the filename back to what it's supposed to be.

##### NOTE 2: The colors and shadows used for the UI elements in Unconnected Marketeers, unfortunately don't work too well on a black background. So that game in particular ends up looking a bit weird, compared to all the other ones.

##### NOTE 3: The patcher zip file can be verified with these hashes:
  
tnbv1.zip

CRC32:&nbsp; 41fe436e  
MD5:  &nbsp; &nbsp;   1c84ed7fa0fb18578fa1a1f29026f769  
SHA-1: &nbsp; 518363234f7fd0eff8c6f24103ac370a33810ec3 

&nbsp;
##

Patches by KMH  
Patcher uses thdat from Touhou Toolkit  
2023-10-21 - Released  
