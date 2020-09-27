# Run Minecraft server with just Docker!
## Just Docker

```sh
docker run -d -p 25565:25565 --volume /home/developer/minecraft-data:/data --name mc -e EULA=TRUE itzg/minecraft-server

```

## Motivation - KISS
Use `docker-compose` (a Python program, did you
know that?  )  or hipsters, use `docker compose` 
	> Pure Docker!!!

Yes, use a container without the heavier weight orchestration tools, and be good enough for the most of us - `say goodbye to Kubernetes` ;)

### References

Azure Fridays

Scott Hanselman -  Microsoft
Chad Metcalf - Docker

watch the video
[Code to Cloud with Docker and Azure Container Instances | Azure Friday](https://www.youtube.com/watch?v=2D8FTi-Zvt0&feature=youtu.be)

Pure Docker!!!

## Java



