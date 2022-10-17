# homelab-portainer-stacks
Collection of docker-compose recipes for my HomeLab

[Watchtower](#watchtower)
[Heimdall](#heimdall)
[PiHole](#pihole)

*Coming soon..*


---

### **Watchtower** <a name="watchtower"></a>
A process for automating Docker container base image updates.

[Github link](https://github.com/containrrr/watchtower)

[Docker Compose](watchtower/docker-compose.yml)


### **Heimdall** <a name="heimdall"></a>
An application dashboard for all your web applications.

[Github link](https://github.com/linuxserver/Heimdall)

[Docker Compose](heimdall/docker-compose.yml)

Environment variables:
> PUID
> GUID
> TZ (example: Africa/Johannesburg)
> PORT


### **Pi-hole** <a name="pihole"></a>
Network-wide Ad Blocking

[Github link](https://github.com/pi-hole/docker-pi-hole)

[Docker Compose](pihole/docker-compose.yml)

Environment variables:
> TZ (example: Africa/Johannesburg)
> WEBPASSWORD (example: randomPassword)

### **Plex** <a name="plex"></a>
Media hosting server

[Server link](https://www.plex.tv/your-media/)

[Docker Compose](plex/docker-compose.yml)

Environment variables:
> N/A
