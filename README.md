## Tema do LightDM para LXQt

Um tema leve, funcional e bonito para o LightDM webkit2. Este tema é usado para a distribuição BigLinux Community LXQt..

### Dependência

+ lightdm
+ lightdm-webkit2-greeter

### Instalação

Você pode instalar esse tema de duas maneiras.

Pelo Pacman
	
	pacman -Sy lightdm-theme-biglinux-community-lxqt

Pelo Pamac

	pamac install lightdm-theme-biglinux-community-lxqt

Clonando o repositório

	git clone https://aur.archlinux.org/lightdm-theme-biglinux-community-lxqt.git
	cd lightdm-theme-biglinux-community-lxqt
	makepkg -sri

### Desinstalar

	pacman -R lightdm-theme-biglinux-community-lxqt

### Funcionalidades

+ Suporte a multi-usuários
+ Customizações e configurações
+ Permite a navegação por teclado
+ Controla por gestor ao passar o dedo
+ Vanilla Javascript!

### Controla por gestor ao passar o dedo

Por que temos isso? O Linux pode ser instalado em quase qualquer coisa. Sim, mesmo em uma batata. Então existe para me poupar algum tempo se alguém (incluindo eu) decidiu usar este tema em um dispositivo de tela sensível ao toque (como batata de tela sensível ao toque? Quem sabe).

+ Deslizar para cima na tela do recepcionista irá fechá-lo.
+ Deslizar para baixo na tela de login abrirá a tela do recepcionista. ]
+ Deslizar para a esquerda abrirá o painel. 
+ Deslizar para a direita fechará o painel.

### Teclas de Atalhos

O atalho padrão é ALT. Você pode alterá-lo nas configurações. 
+ ATALHO + s abre o painel. 
+ ATALHO + e abre a seleção da sessão. 
+ ATALHO + x abre a seleção de energia. 
+ ATALHO + y abre a seleção da conta. 
+ ESC para fechar ou voltar.

### Cinfigurações e personalizações

+ Cores suportadas `#RGB`, `#RRGGBB`, and `#RRGGBBAA`.
+ Transparências devem ser com  `px` no sufixo.
+ As animmações tem suas velocidades em `s` e `ms`.
+ Você pode configurar as  imagens de fundo como randônicas.

### Alteranndo as configurações do relógio

Existem dois modos do relógio - `24-hour` e `12-hour`. Para editar o relógio um simples clique resolve.

### Observações

+ Você pode adicionar as imagens em `/usr/share/backgrounds/`.
+ Se não houver imagem em `/usr/share/backgrounds/` vai dar erro.
+ Para exibir a imagem de perfil tem que configurar no `mugshot`.
+ É permitida a tradução das mensagens de boas-vindas.

### Créditos

<span>Background image by <a href="https://unsplash.com/@korpa?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Jr Korpa</a> on <a href="https://unsplash.com/s/photos/cherry-blossoms-purple?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span>
