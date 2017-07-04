# Notes

## Stable versions

### Development versions

### Snapshots

#### Appimage

- Download the appimage from http://impagina.org/download
- Make the appimage executable (with a file manager, right click on the file, edit its properties and set its run/execute flag ...)
- Run it by double clicking it

Warning:
- currently you seem to need libpython2 installed on your system
- appimages are for 64 bit systems

### Ubuntu and PPA

- Open the open a terminal window. If you don't know what is the terminal, please read this https://askubuntu.com/questions/38162/what-is-a-terminal-and-how-do-i-open-and-use-it (TODO: explain how to add a ppa source without the terminal)
- type: `sudo add-apt-repository ppa:scribus/ppa`
- if it asks you to import the PPA's key, confirm with the enter key.
- update your software list: `sudo apt-get update`
- Now install scribus 1.5.3: `sudo apt-get install scribus-ng`
- search for scribus in the menu & enjoy.
