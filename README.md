# Get Latest Galaxy Buds Manager

https://github.com/ThePBone/GalaxyBudsClient/releases

# Create launcher

## Copy file to generic path

```bash
sudo cp GalaxyBudsClient_Linux_64bit_Portable.bin /usr/share/galaxybuds/GalaxyBudsClient_Linux_64bit_Portable.bin
```


## Create Launcher file

Create file to /usr/share/applications/galaxybuds.desktop

```
[Desktop Entry]
Version=1.0
Type=Application
Terminal=false
Name=Galaxy Buds
GenericName=Galaxy Buds
Path=/usr/share/galaxybuds
Exec=/usr/share/galaxybuds/GalaxyBudsClient_Linux_64bit_Portable.bin
Icon=sounds
Categories=AudioVideo;Player;Recorder;
StartupWMClass=Buds
StartupNotify=true
```
