Download an image. This image simply a Docker image but stripped down to be convenient. 
`wget bit.ly/fish-container -O fish.tar`{{execute}}
This command downloads an image from the link and names it fish.tar 

Make a directory for our container to run, and enter into it
`mkdir fish-container && cd fish-container`{{execute}}

Unpack our tar file into this directory
`tar -xf fish.tar -C ./fish-container`{{execute}}