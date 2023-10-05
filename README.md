# LinuxGSM: Left 4 Dead Dedicated Server Installation Files

## Installation

### Docker Installation

### LinuxGSM Installation

https://docs.linuxgsm.com/

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
