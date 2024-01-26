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

### L4DToolZ v1.1.0.2

https://github.com/Accelerator74/l4dtoolz/releases

### ABM: A MultiSlots / SuperVersus Alternative

https://forums.alliedmods.net/showthread.php?p=2477820
https://gitlab.com/vbgunz/ABM

### Left 4 Downtown 2 v0.5.4.2

https://forums.alliedmods.net/showthread.php?t=134032

### L4D AFK Fix: [L4D(2)] 4+ Survivor AFK Fix (1.2) v1.2

https://forums.alliedmods.net/showthread.php?t=132409?t=132409

### L4D2 8+ Players Bugfixes v1.0.2.1

https://github.com/Satanic-Spirit/l4d2_bugfixes 

### Defib_Fix Defib_Fix[Left 4 Fix][28/02/2023] 2.0.1

https://forums.alliedmods.net/showthread.php?p=2647018

### SteamCMD Installation (steamclient.so)

apt install steamcmd
/usr/games/steamcmd

## Usage

### Run in Docker

```
docker run -it -v /mnt/27TB/home/linuxgsm:/home/gsm --net=host -u gsm --entrypoint /bin/zsh -w /home/gsm linuxgsm
```
