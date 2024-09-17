IP-Fabric path for VMManager 6

Install patch:

```
wget -O /opt/ispsystem/vm/netshield-ip-fabric.yaml "https://raw.githubusercontent.com/netshield-uk/ip-fabric/refs/heads/main/netshield-fabric.yaml";
vm add-patch -p netshield-ip-fabric -f /opt/ispsystem/vm/patch_ip-fabric.yaml;
```

Remove patch:

```
vm remove-patch -p netshield-ip-fabric;
rm -rf /opt/ispsystem/vm/netshield-ip-fabric.yaml;
```