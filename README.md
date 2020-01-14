## Commands
`enca file.txt -L czech` - **detect encoding** of the *file.txt*, assume it's in *czech*. 

`enca file.txt -L czech -x utf-8` - **detect and convert encoding** of the *file.txt* to *utf-8*, assume it's in *czech*.  

`dd bs=4M if=os_img.iso of=/dev/sdb status=progress` - **create bootable usb drive** by writing *os_img.iso* to */dev/sdb*, show progress.  

## Hacks
`vim -p $(grep -rl '#warn')` - **open all files containing** "*#warn*" as tabs in vim. search current directory recursively.

## Tools

https://lvc.github.io/pkgdiff/ - An awesome tool for visualizing changes in Linux software packages 

## Websites
`curl `[http://wttr.in/](http://wttr.in/) - **get weather in ASCII** using your terminal or browser.  

[https://github-forks.abumalick.com/](https://github-forks.abumalick.com/) - **find maintained forks** of your favorite GitHub repos.

## Facts

Python searches `/usr/local/lib/python...` before `/usr/lib/python...` - it had caused me problems.

`getopts` is a (POSIX) shell builtin that can parse simple arguments.   
`getopt` is an external command (GNU and BSD variants) that can parse all kinds of arguments. 

## Design

Many tools are bound to a single directory - this greatly simplifies usage of the tool by reducing the amount of possibilities. (`Makefile`, `Dockerfile`, `Rakefile`, etc.) 
