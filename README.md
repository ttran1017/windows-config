# Komorebi + YASB + WHKD Setup
To set up this configurationL

1. Install Komorebi (w/ WHKD) & YASB
```sh
winget install LGUG2Z.komorebi
winget install LGUG2Z.whkd
winget install --id AmN.yasb
```

2. Set `KOMOREBI_CONFIG_HOME` environment variable to .config
```sh
SETX KOMOREBI_CONFIG_HOME C:\Users\<username>\.config\komorebi
```

3. Copy repo to .config repo
```sh
git clone https://github.com/ttran1017/windows-config.git C:\Users\<username>\.config
```

4. Run YASB and activate Komorebi