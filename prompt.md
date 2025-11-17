I have a Docker Swarm running on Portainer. The Swarm has the following nodes:

- Orange Pi 5 (Manager, 10.0.1.45)
- Raspberry Pi 4 (Worker, 10.0.1.45)
- Orange Pi 5 (Worker, 10.0.1.46)
- Orange Pi 5 (Worker, 10.0.1.47)
- Orange Pi 5 (Worker, 10.0.1.48)
- Orange Pi 5 (Worker, 10.0.1.49)
- Orange Pi 5 (Worker, 10.0.1.50)
- Orange Pi 4 (Worker, 10.0.1.51)
- Orange Pi 4 (Worker, 10.0.1.52)

and a Synology NAS with 70TB of space. I'd like to add tenth node. The node is a Macbook Pro M1 (Worker, 10.0.1.89) running Docker via Colima.

How do I add the Macbook Pro M1 to the Swarm, keep the connection alive, and be able to deploy containers to the node?