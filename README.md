# update-flatpak-aliases
---
A simple barebones bash script that generates aliases for all installed Flatpaks. When triggered, the script automatically gathers the package name of all installed flatpaks and makes aliases for each one with the name of the app.

## Installation 
---
- Place the script inside the `~/local/bin/` directory. Make sure the `PATH` is in your environmental variables.

- Make it executable:
```chmod +x ~/.local/bin/update-flatpak-aliases```
