# AdminTools

Hey, thanks for stopping by, this is my collection of System Administration PowerShell scripts to make my life easier.
The project can be found on [GitHub](https://github.com/baileydauterman/AdminTools).
I am a newbie at creating PowerShell Modules, so my current suggestion for running this to get the commands to be available at startup:

```powershell
Add-Content -Path $profile -Value 'Import-Module ".\AdminTools.psm1"'
```