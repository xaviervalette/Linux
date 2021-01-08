# Routing

## Add a non-persistent route

Default route:
```
sudo ip route add default via <gw>
```
Given route:
```
sudo ip route add <@dest/netmask> via <gw>
```

## Add a persitent route
Given route:
```
sudo nano /etc/network/interfaces
up route add -net <@dest> netmask <netmask> gw <gw>
```
