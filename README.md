# st - simple terminal
st is a simple terminal emulator for X which sucks less.  
  
Forked by @atlemagnussen 2019-08-16

## Patches applied
### font2
[patch homepage](https://st.suckless.org/patches/font2/)  
Patch version:  
[font2 20190416-ba72400](https://st.suckless.org/patches/font2/st-font2-20190416-ba72400.diff)

### scrollback
[patch homepage](https://st.suckless.org/patches/scrollback/)  
patch scrollback version:  
[scrollback 20190331-21367a0](https://st.suckless.org/patches/scrollback/st-scrollback-20190331-21367a0.diff)  

patch scrollback-mouse version:  
[scrollback-mouse 0.8.2](https://st.suckless.org/patches/scrollback/st-scrollback-mouse-0.8.2.diff)

### alpha
[patch homepage](https://st.suckless.org/patches/alpha/)  
patch version:  
[alpha 0.8.2](https://st.suckless.org/patches/alpha/st-alpha-0.8.2.diff)

Requirements
------------
In order to build st you need the Xlib header files.


Installation
------------
Edit config.mk to match your local setup (st is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install st (if
necessary as root):

    make clean install


Running st
----------
If you did not install st with make clean install, you must compile
the st terminfo entry with the following command:

    tic -sx st.info

See the man page for additional details.

Credits
-------
Based on Aurélien APTEL <aurelien dot aptel at gmail dot com> bt source code.

