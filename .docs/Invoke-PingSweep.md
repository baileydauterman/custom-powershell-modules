# Invoke-PingSweep

Sends a mass ping sweep across a specified subnet

## Syntax
```
Invoke-PingSweep
    [-Start]
    [-Stop]
    [-AddMembers]
```

## Examples

Returns path stats for C:\
```
Invoke-PingSweep -Start 192.168.1.0 -Stop 192.168.1.255
```

Ping sweep 192.168.1.0/24 and add null members to the output object of TrackingInfo and Uptime
```
Invoke-PingSweep -Start 192.168.1.0 -Stop 192.168.1.255 -AddMembers @(TrackingInfo, Uptime)
```