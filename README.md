Still very alpha and waaay unfinished but first "theme" sorta POC'd

https://walktownnet.web.app

This repo gives some vague idea of 

- the number of files that need to be provided for a theme
- sorta proof that existing files can be honored, or not stomped on

The nightmare scenario would be something like copying style.css, changing two lines of code, and then whoever was maintaining style.css couldn't effect any improvements because it had already been copypasted via a fork into a theme. So far, this scenario has been avoided except:

- home.njk - as expected
- with-sidebar.njk - as expected