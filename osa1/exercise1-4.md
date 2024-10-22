START PROCESS:

- sudo docker run -it ubuntu sh -c 'while true; do echo "Input website:"; read website; echo "Searching.."; sleep 1; curl http://$website; done'

FIX COMMANDS:

- sudo docker exec -it angry_fermat bash
- apt-get update
- apt-get -y install curl
