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
Para macOS, você pode baixar os instaladores no link ou usar Homebrew:
```
https://multipass.run/download/macos
```
```
brew cask install multipass
```













`multipass launch --name nome_da_sua_vm`

https://multipass.run/



# php-apache-mysql
dockerfile php-apache &amp; mysql
