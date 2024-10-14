# ecps-requirements-setup
### What this script do

It will install all required components for correctly run [ESXi-Customizer-PS](https://github.com/VFrontDe-Org/ESXi-Customizer-PS).

Additionally, it downloads ESXi-Customizer-PS.ps1 into the same directory where you run it.

Make sure:

1. Run ecps-requirements-setup.ps1 as Admin
2. Your pc can run powershell scripts

### If you don't know if your pc can run powershell scripts

Open PowerShell as Admin and type 

> Get-ExecutionPolicy

If the result is "Unrestricted" it's all ok, just launch requirements-setup.ps1, if the state is not unrestricted type

> Set-ExecutionPolicy Unrestricted

then launch requirements-setup.ps1
