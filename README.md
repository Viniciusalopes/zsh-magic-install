# zsh-magic-install
Script para instalar o zsh, powerline-fonts e oh-my-zsh com tema Agnoster configurado, automaGicamente.

### Finalidade
Este script vai instalar o zsh e o configurador oh-my-zsh, mudar o terminal 
padrão para zsh e setar o tema Agnoster para o usuário que estiver executando
o script.

A instalação depende de alguns programas como wget e git, que serão
instalados caso ainda não estejam no seu sistema.

---
### Filosofia
FUNCIONAR, sem dogmatismos, apegos ideológicos, culturais ou filosóficos de qualquer natureza.

Ah! sem trauma e sem teoria! ;)

---
### Onde funciona?
Até o momento foram testadas e instaladas com sucesso as seguintes distribuições Gnu/Linux:
- Mazon OS 1.4.3-beta - XFCE
- Ubuntu Studio 19.04 - XFCE
- Fedora 30 (Thirty) KDE Plasma
- Slackware 14.2 - XFCE
- Ubuntu 19.04 Gnome
- KDE neon User Edition 5.16
- Debian GNU/Linux 9 (stretch) - Mate
- Linux Mint 19.1 - Cinnamon
- Manjaro Linux 18.0 Illyria - XFCE

(Imagens de todas essas distros no final deste arquivo README)

---
### Dependências
Para que tudo corra conforme programado, é necessário que o sudo esteja instalado e configurado corretamente.

O script instala automaGicamente os pacotes 'wget', 'git', 'fontes powerline', 'zsh' e 'oh-my-zsh'.

---
### Instalação
Faça o download no terminal com o comando:

```# wget -O zsh-magic-install https://raw.githubusercontent.com/Viniciusalopes/zsh-magic-install/master/zsh-magic-install```


Conceda as permissões de execução:

```# chmod +x zsh-magic-install```

Execute o script uma vez para cada usuário que desejar instalar o zsh.

---

Para instalar para o seu usuário do sistema, apenas digite:

```# ./zsh-magic-install```

---

Para instalar para o usuário r00t, então digite:

```# sudo su```

e depois:

```# ./zsh-magic-install```

---

### FIQUE ATENTO:
Durante a instalação o sistema poderá solicitar a senha de r00t além de algumas confirmações como essa:

![do-you-change-to-zsh](https://raw.githubusercontent.com/Viniciusalopes/zsh-magic-install/master/imagens/do-you-change-to-zsh.png)

Para continuar basta confirmar com Y ou S dependendo do programa que estiver solicitando sua resposta.

E seja feliz!
---

Quando a instalação estiver concluída, basta reiniciar a sessão, que as configurações do zsh com o tema Agnoster já estarão prontas.

---

## IMAGENS

### Mazon OS 1.4.3-beta - XFCE
![terminal-mazonos-1-4-3.png](https://raw.githubusercontent.com/Viniciusalopes/zsh-magic-install/master/imagens/terminal-mazonos-1-4-3.png)

### Ubuntu Studio 19.04 - XFCE
![terminal-ubuntu-studio-1904.png](https://raw.githubusercontent.com/Viniciusalopes/zsh-magic-install/master/imagens/terminal-ubuntu-studio-1904.png)

### Fedora 30 (Thirty) KDE Plasma
![terminal-fedora-30-kde.png](https://raw.githubusercontent.com/Viniciusalopes/zsh-magic-install/master/imagens/terminal-fedora-30-kde.png)

### Slackware 14.2 - XFCE
![terminal-slackware-14-2-xfce.png](https://raw.githubusercontent.com/Viniciusalopes/zsh-magic-install/master/imagens/terminal-slackware-14-2-xfce.png)

### Ubuntu 19.04 Gnome
![terminal-ubuntu-19-04-gnome.png](https://raw.githubusercontent.com/Viniciusalopes/zsh-magic-install/master/imagens/terminal-ubuntu-19-04-gnome.png)

### KDE neon User Edition 5.16
![terminal-kde-neon-5-16.png](https://raw.githubusercontent.com/Viniciusalopes/zsh-magic-install/master/imagens/terminal-kde-neon-5-16.png)

### Debian GNU/Linux 9 (stretch) - Mate
![terminal-debian-9-mate.png](https://raw.githubusercontent.com/Viniciusalopes/zsh-magic-install/master/imagens/terminal-debian-9-mate.png)

### Linux Mint 19.1 - Cinnamon
![terminal-mint-19-1-cinnamon.png](https://raw.githubusercontent.com/Viniciusalopes/zsh-magic-install/master/imagens/terminal-mint-19-1-cinnamon.png)

### Manjaro Linux 18.0 Illyria - XFCE
![terminal-manjaro-illyria-18-0-4-xfce.png](https://raw.githubusercontent.com/Viniciusalopes/zsh-magic-install/master/imagens/terminal-manjaro-illyria-18-0-4-xfce.png)


---
### Referências
- powerline/fonts -> https://github.com/powerline/fonts
- robbyrussell/oh-my-zsh -> https://github.com/robbyrussell/oh-my-zsh
- plus.diolinux -> https://plus.diolinux.com.br/t/dica-como-instalar-o-zsh-oh-my-zsh-tema-agnoster-no-ubuntu-e-derivados/7321

---
---
