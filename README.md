#Description
This repo is forked from xkegs v0.91 for X86_64 Fedora. It runs fine under 3.15.6-200.fc20.x86_64. See original source: http://kegs.sourceforge.net/

#Prerequisite
   Install xorg-x11-fonts-misc package

#Compile
..*cd src
..*rm vars; ln -s vars_linuxppc vars
..*make

#ROM and hd image
   unzip misc folder package file to repo root folder

#Run
   ./run.sh
