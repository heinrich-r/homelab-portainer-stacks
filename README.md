# homelab-portainer-stacks
Collection of docker-compose recipes for my HomeLab.

**Note**: All stacks have been merged into a single `docker-compose.yml` file in the root directory.

- [Watchtower](#watchtower)
- [Heimdall](#heimdall)
- [PiHole](#pihole)
- [Plex](#plex)
- [Tautulli](#tautulli)
- [n8n](#n8n)
- [Obsidian](#obsidian)
- [Postgres](#postgres)
- [Redis](#redis)

*More Coming soon..*

---

## Unified Configuration

All services are defined in the root `docker-compose.yml`.
Configuration is managed via the `.env` file (see `.env.example`).

### **Watchtower** <a name="watchtower"></a>
A process for automating Docker container base image updates.
[GitHub link](https://github.com/containrrr/watchtower)

### **Heimdall** <a name="heimdall"></a>
An application dashboard for all your web applications.
[GitHub link](https://github.com/linuxserver/Heimdall)

### **Pi-hole** <a name="pihole"></a>
Network-wide Ad Blocking
[GitHub link](https://github.com/pi-hole/docker-pi-hole)

### **Plex** <a name="plex"></a>
Media hosting server
[Web link](https://www.plex.tv/your-media/)

### **Tautulli** <a name="Tautulli"></a>
Media hosting server
[GitHub link](https://github.com/Tautulli/Tautulli)

### **n8n** <a name="n8n"></a>
Workflow Automation Tool
[Web link](https://n8n.io/)

### **Obsidian** <a name="obsidian"></a>
Knowledge base
[Web link](https://obsidian.md/)

### **Postgres** <a name="postgres"></a>
Relational Database
[Web link](https://www.postgresql.org/)

### **Redis** <a name="redis"></a>
In-memory Data Structure Store
[Web link](https://redis.io/)
