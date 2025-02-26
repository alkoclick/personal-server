Syncthing in the container complains if you edit the config via GUI and try to save, some kind of permissions issue? IDK

```
WARNING: Failed to save config: rename /var/syncthing/config/.syncthing.tmp.567659478 /var/syncthing/config/config.xml: device or resource busy
```

Either way, we can just edit the raw XML. 

New device: Just add the entry to the devices stanza

Sharing a folder: 
* add an entry to folders
* ensure that the devices point to the devices you wanna share with
* accept the connection on the other side
