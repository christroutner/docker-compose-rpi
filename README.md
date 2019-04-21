# docker-compose-rpi
Docker Compose should be able to be installed on a Raspberry Pi with these
commands:

```bash
sudo apt-get install -y python3 python3-pip
sudo pip3 install docker-compose
```

But on more than one occasion, those commands fail. So I created this repository
which holds a binary, executable, compiled copy of Docker Compose that runs on
a Raspberry Pi.

You can [download it here](docker-compose)
