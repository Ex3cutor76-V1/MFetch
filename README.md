# MFetch

## O que é o MFetch?

O MFetch é um fetch tool que desenvolvi enquanto estava entediado. Ele foi inspirado em projetos como Neofetch e Fastfetch, com o objetivo de ser uma ferramenta leve para exibir informações do sistema.

A ideia é ser minimalista, sem dependências externas ou foco em estilização pesada — apenas mostrar informações essenciais do sistema de forma direta.

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

---

## Compatibilidade

Desenvolvido para Linux Desktop e funciona melhor em sistemas baseados em Debian/Ubuntu com systemd e ferramentas comuns instaladas.

Pode funcionar parcialmente em outras distribuições Linux, mas alguns recursos podem não estar disponíveis dependendo do sistema (como NetworkManager, dpkg, xrandr e systemd).

❗ Não é compatível com Windows.

## Instalação

`` git clone https://github.com/Ex3cutor76-V1/MFetch.git ``

`` cd MFetch/ ``

`` sudo mv mfetch /usr/local/bin/ ``

`` mfetch ``
