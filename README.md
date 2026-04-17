# O que é o MFetch?

É um fetch que estive criando enquanto estava entediado, eu usei como inspiração os projetos neofetch e fastfetch, com o intuito de ser algo mais leve que só mostre as informações sobre o dispositivo usando em base o sistema inteiro, sem precisar de bibliotécas ou ser estiloso demais... No caso é um fetch que eu havia criado para ser minimalista e leve, como foi dito.

# O que o Mfetch mostra?

| Titulo | Objetivo | 
|-------------|-------------|
| User | Nome do user no sistema |
| OS | Sistema operacional do sistema |
| Kernel | Versão do Kernel |
| Packages | Lista de pacotes dpkg ou pacotes flatpak |
| Arquitetura | Arquitetura do dispositivo |
| Uptime | Quanto tempo o computador está ligado |
| Date | Data de hoje |
| CPU | CPU do dispositivo |
| Resolution | Resolução do dispositivo |
| RAM | Memória RAM do dispositivo |
| Wifi/Ethernet | Conexão tanto wifi quanto a cabo |
| Tor | Se está conectado a rede tor (Via systemd) |
| Battery | Bateria |
| Shell | Shell do sistema operacional |
| Disk | Disco rígido (HD ou SSD) |

# Compatibilidade:

Desenvolvido para Linux Desktop e funciona melhor em sistemas baseados em Debian/Ubuntu com systemd e ferramentas comuns instaladas.

Aviso de alerta: Até pode funcionar parcialmente em outras distros Linux, mas alguns recursos podem não estar disponíveis dependendo do sistema (No caso necessitaria de ferramentas como: NetworkManager, dpkg, xrandr, systemd).

Aviso Principal: Não funciona em Windows.
