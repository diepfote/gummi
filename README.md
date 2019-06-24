[![travis-ci.com](https://api.travis-ci.com/florianbegusch/gummi.svg)](https://travis-ci.com/florianbegusch/gummi)
# Gummi - Customized for power users
Addtions to the [original Gummi](https://github.com/alexandervdm/gummi) include but are not limited to:
* commenting functionality
* cut/duplicate/delete line support
* reopening previously open files

### Screenshot

![Alt text](/../screenshots/screenshots/gummi-065-main.png?raw=true "gummi 0.6.5 main")

### Building

Building Gummi requires a working C compiler and some dependencies to be installed beforehand. For detailed instructions and our list of dependencies, please refer to the [documentation](https://github.com/alexandervdm/gummi/wiki/Installing-Gummi#compile-from-source).

Once these prerequisities are completed, run

    ./autogen.sh    
    ./configure
    make

### Installing
##### Any Linux
After finishing the build process, run

    sudo make install

##### Arch Linux
On Arch Linux use the AUR package

    yaourt -S gummi-gtk2-git

### Contact
To contact the original owner, please refer to the project's [github page](https://github.com/alexandervdm/gummi).  
To contact me, please use the email address provided on my [github profile](https://github.com/florianbegusch).
