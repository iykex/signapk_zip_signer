SignApk ZIP Signer tool
======================

What it does?
------------
This Batch based tool is made for signing .zip files.
(usually .zips that are supposed to be flashed via custom recovery like TWRP, CWM or PhilZ on your android device)

How to use it?
-------------
To get started with SignApk ZIP Signer you have to move a .zip file you want to sign to the `Input` folder.
Then just double-click on `Signer.exe` and choose `Start signing` from option menu.
You can also choose if you want to generate Md5 checksum which is sometimes required.
This process will take some time but it depends on the size of a .zip file you are signing.
When it's done, program will automatically open `Output` folder and there you will find your signed .zip file.

Notes
----
ATTENTION! This ZIP Signer is built to work on any path, but to avoid any possible breackage
please don't use .zip files with spaces or special characters in name; use only letters [a-Z]
numbers [0-9] and usual signs [- or _], and stay away from [!@~`%$#*&(){}[]<>/....] or other like these.
My tool doesn't have restrictions on placement. For me it worked in last partition, in sub-subfolder, without problems.
This tool can't run under administrator privileges.

The changelog (notable new features and changes)
-----------------------------------------------

### v1.0.0 (Aurora)
* Initial SignApk ZIP Signer tool release
