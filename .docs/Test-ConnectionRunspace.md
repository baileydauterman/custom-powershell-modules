# Test-ConnectionRunspace

Remotely sends a command to kickoff SCCM actions

## Syntax
```
Test-ConnectionRunspace
    [-ComputerName]
```

## Examples

For one machine
```
Test-ConnectionRunspace -ComputerName computer01
```

for multiple machines
```
Test-ConnectionRunspace -ComputerName $Computers.Name
```