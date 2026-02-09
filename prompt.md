I have a Docker Swarm running on Portainer. The Swarm has the following nodes:

- Orange Pi 5 (Manager, 10.0.1.45)
- Raspberry Pi 4 (Worker, 10.0.1.46)
- Orange Pi 5 (Worker, 10.0.1.47)
- Orange Pi 5 (Worker, 10.0.1.48)
- Orange Pi 5 (Worker, 10.0.1.49)
- Orange Pi 5 (Worker, 10.0.1.50)
- Orange Pi 4 (Worker, 10.0.1.51)
- Orange Pi 4 (Worker, 10.0.1.52)
- Macbook Pro M1 (Worker, 10.0.1.89)

and a Synology NAS with 70TB of space. I'd like to add tenth node. The Macbook Pro M1 is running Docker via Colima. The node is using `caffeinate` to keep the machine awake. The node is availability is "Active" but the node status is "Down". How do I keep the node alive?
