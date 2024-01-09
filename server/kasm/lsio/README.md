### Kasm Workspaces
---

*Host your own instance [here](https://docs.linuxserver.io/images/docker-kasm/).*

Kasm Workspaces utilizes containerization to isolate individual user sessions. Each user is provided with a few applications running in their own dedicated container on the server, ensuring separation between the workspace and your device. This approach offers enhanced security, as any potential malicious activity or malware within one user's container is isolated and cannot affect other users or the underlying infrastructure. 

This version uses the image provided by LinuxServer.io

Once it has been set up, login to the admin interface, then go to 'Zones'. Change the following values: upstream auth address = proxy, proxy port = 0
