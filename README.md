# config for startship-prompt
- Install startship prompt
```powershell
winget install --id Starship.Starship
```

- Open Powershell as Administrator
- Delete ~/.config/startship.toml file if it exist
- Create .config folder and startship.toml file
```powershell
mkdir -p ~/.config
```

- cd into the config directory
```powershell
cd ~/.config
```

- Open CMD
- Create a symlink to ~/.config/startship.toml from startship-promp/startship.toml
```powershell
cd C:\Users\<USER>\.config
```
```powershell
mklink starship.toml C:\SLinks\starship-prompt\starship.toml
```