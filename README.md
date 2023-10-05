# LinuxGSM: Left 4 Dead Dedicated Server Installation Files

## Installation

### Docker Installation

sudo useradd linuxgsm
su linuxgsm
docker pull ubuntu
docker run -it --entrypoint /bin/sh ubuntu
# In Docker Container
adduser linuxgsm # set id as hosts's linuxgsm user in /etc/{passwd,group}
docker run -it -v /mnt/27TB/home/linuxgsm:/home/gsm --net=host -u gsm --entrypoint /bin/zsh -w /home/gsm linuxgsm


### LinuxGSM Installation

Choose Game Server https://linuxgsm.com/servers/ and follow Dependencies/Installation instructions.
Also read Basic Usage.

### Metamod Installation

https://www.sourcemm.net/

### Sourcemod Installation

https://www.sourcemod.net/

### L4DToolZ Installation

https://github.com/Accelerator74/l4dtoolz/releases

### MultiSlots Installation

https://forums.alliedmods.net/showthread.php?p=1239544

### SteamCMD Installation (steamclient.so)

apt install steamcmd
/usr/games/steamcmd

## Usage

### Run in Docker

```
docker run -it -v /mnt/27TB/home/linuxgsm:/home/gsm --net=host -u gsm --entrypoint /bin/zsh -w /home/gsm linuxgsm
```
