# XPS-9700-Ubuntu

to purge existing nvidia drivers in case we can't even show basic gui:

`sudo apt-get purge nvidia*`

to install correct nvidia drivers:

`sudo add-apt-repository ppa:graphics-drivers/ppa`

`sudo apt-get update`

`sudo apt-get install nvidia-driver-520`

to install vulkan

`sudo apt install vulkan-tools`
