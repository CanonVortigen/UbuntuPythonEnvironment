<h1 class align='center'>Ubuntu Python Environment Setup</h1>

<h3 class align='center'>Installation Ubuntu Python Environment / Pypenv</h3>   

<p>/bin/bash</p>

<h3>Executar comandos a seguir para atualizar os pacotes</h3>

<p>sudo apt-get update && sudo apt-get upgrade -y</p>

<h3>Só o Python</h3>

<p>sudo apt install python3.10-full python3.10-dev -y</p>

<h3>Instalar pacotes a seguir</h3>

<p>sudo apt install git curl build-essential dkms perl wget -y</p>

<p>sudo apt install gcc make default-libmysqlclient-dev libssl-dev -y</p>

<p>sudo apt install -y zlib1g-dev libbz2-dev libreadline-dev libsqlite3-dev llvm</p>
<p>libncurses5-dev libncursesw5-dev xz-utils tk-dev libffi-dev liblzma-dev python3-openssl git</p>
  
# Pyenv

curl -L https://github.com/pyenv/pyenv-installer/raw/master/bin/pyenv-installer | bash

<h3>Seguir instruções do Pyenv</h3>

<h4>Baixar e instalar VS Code: https://code.visualstudio.com/download</h4>

<h4>Abaixo tudo é opcional</h4>
<hr>
<h3>Instalar e configurar ZSH</h3>

<p>sudo apt install zsh -y</p>

<p>chsh -s /bin/zsh</p>

<p>zsh</p>

<h4>Instalar Oh-my-zsh! -> https://ohmyz.sh/</h4>

<h4>sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"</h4>

<h3>Instalar Spaceship Prompt</h3>
<p>https://github.com/spaceship-prompt/spaceship-prompt</p>

<p>git clone https://github.com/spaceship-prompt/spaceship-prompt.git "$ZSH_CUSTOM/themes/spaceship-prompt" --depth=1</p>
<p>ln -s "$ZSH_CUSTOM/themes/spaceship-prompt/spaceship.zsh-theme" "$ZSH_CUSTOM/themes/spaceship.zsh-theme"</p>

<p>Mudar ~/.zshrc -> ZSH_THEME="spaceship"</p>

<p>nano ~/.zshrc</p>   

<h3>Instalar Zsh Autosuggestions</h3>
<p>https://github.com/zsh-users/zsh-autosuggestions</p>
<p>git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions</p>

<h3>Instalar Zsh Syntax Highlighting</h3>
<p>https://github.com/zsh-users/zsh-syntax-highlighting</p>
<p>git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting</p>

<h3>Mudar plugins</h3>
<p>plugins=(git zsh-autosuggestions zsh-syntax-highlighting)</p>

<p>nano ~/.zshrc</p>   

<p>Font optional (https://github.com/pdf/ubuntu-mono-powerline-ttf)</p>

<p>mkdir -p ~/.fonts</p>

<p>git clone https://github.com/pdf/ubuntu-mono-powerline-ttf.git ~/.fonts/ubuntu-mono-powerline-ttf</p>

<p>fc-cache -vf</p>

<h1>REBOOT!!!!!!!!!!!!!!!!!!!!!</h1>
