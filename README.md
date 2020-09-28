# Run a Minecraft Server in a Docker container, with just docker-compose!
## Motivation?
It's just not necessary to go to the complexity and expense to run a small scale 
production grade containerized applicaton.

By following along with this repository I will show you how to use `Docker` and `docker-compose` along with 
some excellent methods advocated by some of the industries leaders in Docker.

What Docker fundamentals you will learn:

1. Running a Minecraft server in Docker on a Linux Server
1. Resiliancy - Keep Game Data/State by mounting a `Persistent Volume` to the server's local hard drive.
of the Docker container restarting due to failure etc )
1. Observability - Monitoring the container metrics and health with Prometheus and Graphana
1. Observability - Capturing logs with the EFK ( Elastic Search, Fluentd, Kibana ) stack
1. Reliability - Using `Traefik` as a Reverse Proxy to `load balance` requests to multiple Minecraft Servers


1. Running a Minecraft server in Docker on a Linux Server
So I setup docker and docker-compose on my CentOS 7 VM running on Digital Ocean.

```sh
mkdir ~/<local-data-dir>
docker-compose -f ./docker-compose-local.yaml up
```
<details><summary><strong> Docker command equivalent ( helpful in troubleshooting ) </strong></summary>
	
	</details>

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



