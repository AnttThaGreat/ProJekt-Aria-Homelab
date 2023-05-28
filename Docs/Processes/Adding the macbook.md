# Adding the Macbook Pro(2012) to the Cluster.
### 2023-05-26

## Why i want to
I know you are probably thinking, "why would you use a Macbook pro?"
No, well i did at first, which part of the reason that i waited to use it.
Its an old device by many standards, but it was one of the MBPs that still used 
Intel silicon. ive used it before as a second pc dedicated to linux, but that was before i found home-labbing. As per my interest in IT , specifically cybersecurity, i tried out kali
in a vm on my prometheus server the aircrack process took alot resources. 
so i prefered to have a dedicated pc to host the specific vm. Also adding another PC allows me to get hands on with HA (high avalability) for some of my smaller microservices like Dashy or Uptime Kuma.


## Steps I Took

### 1. Proxmox installation.
I started by downloading the latest image for proxmox found [here](https://www.proxmox.com/en/downloadas/category/iso-images-pve) . 
Then installing it on the MBP.
The key presses to access a bootloader open was easy enough to find,
since i really couldnt remember. its "Hold option key,after you here the startup chime". 
thats it.

### 2. Setup/Updates 



Everybody knows to run:

"sudo apt update && sudo apt upgrade"

as soon as you install any debian based distro.
Its like punching a tree soon as you start a new
Minecraft world


### 3. Adding MBP to data center.
Just copied the join cluster info from the main system to the main 





