# O que é o Multipass?

Multipass é um leve gerente de VM para Linux, Windows e macOS. Foi projetado para desenvolvedores que querem um ambiente novo do Ubuntu com um único comando. Ele usa KVM no Linux, Hyper-V no Windows e HyperKit no macOS para executar o VM com sobrecarga mínima. Ele também pode usar o VirtualBox no Windows e macOS. O Multipass buscará imagens para você e as manterá atualizadas.

Uma vez que ele suporta metadados para nuvem-init, você pode simular uma pequena implantação em nuvem em seu laptop ou estação de trabalho.

## Instalar o  Multipass

Primeiramente nesse tutorial sera utilizado o Virtual box , mais lembrando que ele funciona com o KVM no linux , Hyper-V no windows e HyperKit no macOS
```
https://www.virtualbox.org/
```
No Linux está disponível como um snap:
```
https://snapcraft.io/multipass
```
```
https://snapcraft.io/docs/installing-snapd
```

No Windows 
```
https://multipass.run/download/windows
```
Para macOS, você pode baixar os instalador no link ou usar Homebrew:
```
https://multipass.run/download/macos
```
```
brew cask install multipass
```
Lista Imagens disponiveis (10/10/20)
```
$ multipass find
Image                       Aliases           Version          Description
core                        core16            20200818         Ubuntu Core 16
core18                                        20200812         Ubuntu Core 18
16.04                       xenial            20200922         Ubuntu 16.04 LTS
18.04                       bionic            20200922         Ubuntu 18.04 LTS
20.04                       focal,lts         20200921.1       Ubuntu 20.04 LTS
appliance:adguard-home                        20200812         Ubuntu AdGuard Home Appliance
appliance:lxd                                 20200812         Ubuntu LXD Appliance
appliance:mosquitto                           20200812         Ubuntu Mosquitto Appliance
appliance:nextcloud                           20200812         Ubuntu Nextcloud Appliance
appliance:openhab                             20200812         Ubuntu openHAB Home Appliance
appliance:plexmediaserver                     20200812         Ubuntu Plex Media Server Appliance
```

Inicie uma instância
```
$ multipass launch 20.04 --name maneger
```

Execute comandos nesse caso, tente executar bash (logout ou ctrl-d para sair)
```
$ multipass exec maneger -- bash
 ```

Confira as instâncias em execução
```
$ multipass ls
Name                    State             IPv4             Image
maneger                 Running           N/A              Ubuntu 20.04 LTS
```

# More information
https://multipass.run/docs





# php-apache-mysql
dockerfile php-apache &amp; mysql


