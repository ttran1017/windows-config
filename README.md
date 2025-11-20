# Komorebi + YASB + WHKD Setup
To set up this configurationL

1. Install Komorebi (w/ WHKD) & YASB
```sh
winget install LGUG2Z.komorebi
winget install LGUG2Z.whkd
winget install --id AmN.yasb
```

2. Run setup script
```
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
.\setup.ps1
```

3. Run YASB and activate Komorebi