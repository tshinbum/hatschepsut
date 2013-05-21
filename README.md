hatschepsut
===========

System config files for VM which runs supercollider and icecast

1. remove .at from /etc/apt/sources.list. Austrian mirror is not complete (64bit packages)
2. apt-get update
3. apt-get install git
4. clone hatschepsut from github
5. add supercollider*, vim
6. dpkg --get-selections | sed "s/.*deinstall//" | sed "s/install$//g" > /pkglist
7. add icecast and darkice
