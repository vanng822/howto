

To move volumes, images, ... to other location/volume

Move first /var/lib/docker to the volume you want
Create a symbolic link to that new location
ln -s /new/location /var/lib/docker
