1.Download an image. This image is simply a Docker image but stripped down to be convenient. 

`wget bit.ly/fish-container -O fish.tar`{{execute}}

This command downloads an image from the link and names it fish.tar 

2.Make a directory for our container to run, and enter into it

`mkdir fish-container`{{execute}}

3.Unpack our tar file into this directory

`tar -xf fish.tar -C ./fish-container`{{execute}}