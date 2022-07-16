---
title: How to Remove Cortana From Windows
date: 2022-07-16T12:10:23+05:30
draft: false
---
#### open a powershell in administrator mode and copy paste the below powershell snippit
```powershell
Get-AppxPackage -allusers Microsoft.549981C3F5F10 | Remove-AppxPackage
```
