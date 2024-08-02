# Ngrok on docker

With this repository you can quicly set up multiple ngrok tunnels in one docker container.

## How to build and run

Your must create an account on [ngrok website](https://ngrok.com) then you should be able to generate your own authToken.
Once you copied your authToken you can copy the file *ngrok.yml.example* to "ngrok.yml.example/" or just rename it. Finally you can paste your authToken in this file. You can also edit the ports you want to tunnel in this file.

You can now run *docker-compose up -d* and you check on http://localhost:4040/ that everything works fine.

