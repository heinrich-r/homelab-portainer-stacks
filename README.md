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

[Docker Compose](watchtower/docker-compose.yaml)


### **Heimdall** <a name="heimdall"></a>
An application dashboard for all your web applications.

[Github link](https://github.com/linuxserver/Heimdall)

[Docker Compose](heimdall/docker-compose.yaml)

Environment variables:
> PUID
> GUID
> TZ (example: Africa/Johannesburg)
> PORT


### **Pi-hole** <a name="pihole"></a>
Network-wide Ad Blocking

[Github link](https://github.com/pi-hole/docker-pi-hole)

[Docker Compose](pihole/docker-compose.yaml)

Environment variables:
> TZ (example: Africa/Johannesburg)
> WEBPASSWORD (example: randomPassword)
