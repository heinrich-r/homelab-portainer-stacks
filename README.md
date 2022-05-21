# homelab-portainer-stacks
Collection of docker-compose recipes for my HomeLab

1. [Watchtower](#watchtower)
2. [Heimdall](#heimdall)

*Coming soon..*

- [Grafana & Prometheus](https://grafana.com/)
- [Apache Guacamole](https://guacamole.apache.org/)
- [PiHole](https://pi-hole.net/)
- [Buildkite Agent](https://github.com/buildkite/agent)


---

### **1. Watchtower** <a name="watchtower"></a>
A process for automating Docker container base image updates.

[Github link](https://github.com/containrrr/watchtower)

[Docker Compose](watchtower/docker-compose.yaml)


### **2. Heimdall** <a name="heimdall"></a>
An application dashboard for all your web applications.

[Github link](https://github.com/linuxserver/Heimdall)

[Docker Compose](heimdall/docker-compose.yaml)

Environment variables:
> PUID
>
> GUID
>
> TZ
>
> PORT