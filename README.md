# Launch Putty via HTML #

Use this .reg. and .bat file to automatically launch [Putty](http://www.putty.org/) via ssh:// urls on Windows.  Thanks to a post from [cdelacroix](https://stackoverflow.com/users/570553/cdelacroix) @ [StackExchange](https://stackoverflow.com/questions/17670067/html-code-to-open-putty-client-from-browser) article for all the details.

### Files ###
* putty_ssh.bat
* README.md
* ssh.reg

### Steps ###

1. Update putty_ssh.bat so it contains the correct path to putty.exe
2. Copy putty_ssh.bat to its new home, e.g. C:\Program Files\Putty\
3. Update ssh.reg so it contains the path to putty_ssh.bat
4. Run the .reg file to add contents to the Windows Registry

This will automatically launch putty via ssh:// URLs. Note: if WinSCP or other tool is already registered to handle these URLs, that will take precedence.
