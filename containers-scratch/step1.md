Download an image. This image simply a Docker image but stripped down to be convenient. 
`wget bit.ly/fish-container -O fish.tar`
This command downloads an image from the link and names it fish.tar 

Make a directory for our container to run, and enter into it
mkdir fish-container && cd fish-container

Unpack our tar file into this directory
tar -xvzf . ./fish.tar