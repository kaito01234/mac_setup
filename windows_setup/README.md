# Windows Setup

## Scoop

https://scoop.sh/

## Setup

```ps
scoop import scoop.json
winget import winget.json
```

## Scoop Usage

```ps
# list
scoop list

# update
scoop update *

# cleanup
scoop cleanup *
```

## WSL2

```ps
# install
wsl --install
wsl --set-default-version 2
wsl --install -d Ubuntu
wsl --set-default Ubuntu

# install
wsl --list --verbose
```
