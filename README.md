# MFetch

## O que é o MFetch?

O MFetch é um fetch tool que desenvolvi enquanto estava entediado. Ele foi inspirado em projetos como Neofetch e Fastfetch, com o objetivo de ser uma ferramenta leve para exibir informações do sistema.

A ideia é ser minimalista, sem dependências externas ou foco em estilização pesada — apenas mostrar informações essenciais do sistema de forma direta.

## Atualização

A versão MFetch V2 agora permite que o user veja informações sobre a WM utilizada, além de ficar um pouco mais leve em hardware antigo e melhorando a compatibilidade.

---

## O que o MFetch mostra?

| Título        | Objetivo |
|--------------|----------|
| User         | Nome do usuário no sistema |
| OS           | Sistema operacional |
| Kernel       | Versão do kernel |
| Packages     | Pacotes instalados (dpkg/flatpak) |
| Arquitetura  | Arquitetura do sistema |
| Uptime       | Tempo de uso do sistema |
| Date         | Data atual |
| CPU          | Processador |
| Resolution   | Resolução da tela |
| RAM          | Uso de memória RAM |
| WiFi/Ethernet| Status da conexão de rede |
| Tor          | Status da conexão Tor (via systemd) |
| Battery      | Nível da bateria |
| Shell        | Shell em uso |
| Disk         | Uso do disco |
| WM           | Informação sobre |
---

## Compatibilidade

O Mfetch foi desenvolvido principalmente para Linux.

## Linux
Compatível com a maioria das distros Linux Desktop, incluindo:

- Debian/Ubuntu ou derivados
- Arch Linux
- Fedora
- OpenSuse

### Suporte parcial
Em algumas funcionalidades do Mfetch, pode não funcionar dependendo do sistema.

- Informação de rede depende do Network Manager
- Informação de resolução depende do xrandr (Ou conhecido como X11)
- Já os status do Tor depende do systemd

Caso queira instalar essas, use:

### Se você for Debian/Ubuntu:

```bash id="dep2"
sudo apt update
sudo apt install -y bash coreutils awk procps util-linux x11-xserver-utils network-manager systemd
```
### Se você for Arch Linux/Manjaro:

```bash id="dep2"
 sudo pacman -S bash coreutils gawk procps-ng util-linux xorg-xrandr networkmanager systemd
```

### Se você for Fedora:

```bash id="dep2"
sudo dnf install bash coreutils gawk procps util-linux xorg-x11-server-utils NetworkManager systemd
```

### Se você usa Termux:
```bash id="dep2"
pkg update
pkg install bash coreutils gawk procps util-linux termux-tools
```
### Se você usa Windows 
❗ Não é compatível com Windows.

A não ser que vocẽ use WSL

## Instalação

```bash id="dep2"
git clone https://github.com/Ex3cutor76-V1/MFetch.git ``
``` 
```bash id="dep2"
cd MFetch/ 
```
```bash id="dep2"
sudo mv mfetch /usr/local/bin/
```
```bash id="dep2"
mfetch 
```
