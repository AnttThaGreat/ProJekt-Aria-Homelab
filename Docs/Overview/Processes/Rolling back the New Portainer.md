# My Dashboard broke w/update
2023-06-05

### What happened?
Apparently, on the days that i have Proxmox scheduled to do back ups, it also does package updates on the nodes themselves. During the package update last night, something caused Dashy to revert back to the default layout. void of all personalization all links and password saves, everything. Immediately i became alarmed because i wouldnt be able to access my various services. (without digging around in router settings and notebooks for ip addresses and port numbers)

### How i fixed it.
Since ive became aware of the importance of backups, i have been keeping some applications backup up automatically. admittedly not as often as i should. i simply rolledback to a snapshot i created when i moved my container instance of Portainer to a VM.




