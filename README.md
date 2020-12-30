# Docker to run WordPress

## How to use?

1. Clone this repository in your local machine
2. Run the command:

```
sudo docker-compose up
```

3. Find the IP Address of the container:

```
sudo docker inspect <container id> | grep IPAddress
```

4. Example: "IPAddress": "172.19.0.3"

5. Run the IPAddress number in your browser

6. You're all set!
