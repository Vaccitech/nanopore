# Install MinKnow
When updating minKnow you may have to uninstall and reinstall.
This can be a fiddly process, see [here](https://community.nanoporetech.com/support/articles/234). Steps to check are:
- uninstall minknow
- uninstall microsoft visual c++
- move needed data out of c://data
- delete c://data
- delete minknow and mkw out of %appdata%
- delete any previously downloaded minknow versions
- Remove files with pending file rename operations

1. Search for regedit and run 

2. Navigate (on left) to HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\

3. On the right should be a file called PendingFileRenameOperations

4. If you click this a window will open telling you which program is causing the installation to be blocked.

5. Delete these files
