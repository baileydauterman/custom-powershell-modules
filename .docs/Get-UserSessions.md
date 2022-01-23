# Get-UserSessions

Gets the user sessions on a remote machine

## Syntax
```
Get-UserSessions
    [[-ComputerName] <string[]>]
```

## Examples

for local machine
```
Get-UserSessions
```

for remote machine
```
Get-UserSessions -ComputerName computer01
```

for remote machines
```
Get-UserSessions -ComputerName $computers.Name
```