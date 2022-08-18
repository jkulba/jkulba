# Manjaro Development Environment Setup, 2022


## James Kulba, August 18, 2022


## Manjaro Image Installation

My preference is the Gnome window toolkit.  Use the following URL to download the latest ISO image.

[https://manjaro.org/downloads/official/gnome/](https://manjaro.org/downloads/official/gnome/)

Burn the ISO to a USB drive larger than 4GB.


## DotNet SDK


```
sudo pacman -S dotnet-sdk dotnet-runtime
```


Check the version using the following command:


```
dotnet -version
```


Check the location of dotnet using the following command:


```
whereis dotnet
dotnet: /usr/bin/dotnet /usr/share/dotnet
```



## DotNet Tools


```
https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-tool-search
```



## VS Code

_Install from AUR - ‘visual-studio-code-bin’_


## Azure Functions Core Tools

_Install from AUR - ‘azure-functions-core-tools-bin’_


## Azure CLI

_Install from AUR - ‘azure-cli’_


## GitHub CLI

_Install from AUR - ‘github-cli’_


## Docker

_Install from AUR - ‘docker”, “docker-compose’_


## PlantUML

_From the command-line I attempted to _


## Enable Printing

[https://wiki.manjaro.org/index.php?title=Printing](https://wiki.manjaro.org/index.php?title=Printing)

Snapd

[https://snapcraft.io/install/snap-store/manjaro#install](https://snapcraft.io/install/snap-store/manjaro#install)


## Git

The git client was pre-installed 


## Git Flow

_Install from AUR - ‘gitflow-avh’ and ‘gitflow-zshcompletion-avh’_


## OpenJDK


```
sudo pacman -S jre11-openjdk-headless jre11-openjdk jdk11-openjdk openjdk11-doc openjdk11-src
```



### Confirm default java JDK


```
jim@ultra1  ~  archlinux-java status
Available Java environments:
  java-11-openjdk (default)
  java-18-openjdk
```



### Set default java JDK


```
sudo archlinux-java set java-11-openjdk
```

