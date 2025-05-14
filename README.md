# Basfetch
## Descripton
build and install any cpp project with cmake

## Usage
```bash
basfetch -t https://github.com/laserpants/dotenv-cpp.git
```
## Options
    -t, --temp            Git repository will be installed in temporary directory and will be deleted after installing
    -o, --output DIR      Git repository will be cloned to DIR. DON'T USE WITH -t OPTION
    -h, --help            Show help message

## How to install?
this util is part of bastard-apt-repository

for installation gide checkout https://github.com/frobe11/bastard-apt-repository

<!-- 
## Создать DEB пакет
```
dpkg-deb --build ../basfetch
mv ../basfetch.deb ./basfetch.deb
``` -->
