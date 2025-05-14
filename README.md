If you're trying to delete a file and your computer isn't letting you, it's most likely because
another program is currently trying to use the file or corrupted. This can occur even if you don't
see any programs running. Deleting these files is usually a matter of forcing the program that's
using the file to close.

1. Close any open programs and try deleting the file again.

2. Press the “**Windows key**” + “**R**” and type “**cmd**” to open the Command Prompt.

3. Type “**cd C:\path\to\file**” and press Enter. Replace C: with the actual drive letter and
   path\to\file with the address of the folder. For back to previous folder type “**cd..**”

4. Type “**dir**” and press Enter to see a list of files. Make note of the exact filename and
   extension of the file you want to delete.

5. Try deleting using the file's short name. Sometimes odd characters can cause problems with
   deleting the file. Using the file's "short name" or DOS-compatible name.
 
 5.1 Type “**dir /x**” for the short name of the file (i.e **FILENA~1.XYZ**)
     and directory (i.e **FILENA~1**).
 
 5.2 **Delete File:** Type “**del FILENA~1.XYZ**” and press Enter. This will attempt to delete the
     file that you specify. Make sure to include the full name and extension.(Application, zip,
     image, video etc)
 
 5.3 **Delete Directory:** Type “rmdir /s directoryName(or FILENA~1)” and press Enter.
     Sometimes, deleting the folder will allow you to delete the file that it contains. Keep in
     mind that deleting a folder will delete all of its contents.( Folder type )

7. Confirm permanent delete by type **“(Y/N)”** , **Y** -“yes” or **N** -“no”.

8. Finally..delete the corrupted file or folder.!!
