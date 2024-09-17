IP-Fabric path for VMManager 6

Install patch:

```
wget -O /opt/ispsystem/vm/netshield-ip-fabric.yaml "https://raw.githubusercontent.com/netshield-uk/ip-fabric/refs/heads/main/netshield-ip-fabric.yaml";
vm add-patch -p netshield-ip-fabric -f /opt/ispsystem/vm/netshield-ip-fabric.yaml;
```

Remove patch:

```
vm remove-patch -p netshield-ip-fabric;
rm -rf /opt/ispsystem/vm/netshield-ip-fabric.yaml;
```

---------
P.S Уважаемая компания Ispsystem поднимите жопу и сделайте настройку BGP из панели. Добавить кнопку для ebgp-multihop не трудно. 