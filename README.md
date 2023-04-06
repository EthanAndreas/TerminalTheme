# Terminal theme

## For ubuntu
Install oh-my-posh
```bash
sudo wget https://github.com/JanDeDobbeleer/oh-my-posh/releases/latest/download/posh-linux-amd64 -O /usr/local/bin/oh-my-posh
sudo chmod +x /usr/local/bin/oh-my-posh
```
Add in .bashrc in <user> directory 
```bash
eval "$(oh-my-posh --init --shell bash --config $HOME/.theme/turquoise.omp.json)"
```

## For windows, add in $PROFILE
Install oh-my-posh
```pwsh
winget install JanDeDobbeleer.OhMyPosh -s winget
```
```pwsh
oh-my-posh init pwsh --config "C:\Users\ethan\.theme\turquoise.omp.json" | Invoke-Expression
```
