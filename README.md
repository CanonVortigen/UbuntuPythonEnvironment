<div class align='center'>
  
  <h1>Ubuntu Python Environment Setup</h1>

  <h3>Installation Ubuntu Python Environment / Pypenv</h3>     
  <p>/bin/bash</p>  
  <hr>
  
  <h3>Run following commands to update packages</h3>  
  <p>sudo apt-get update && sudo apt-get upgrade -y</p>
  <hr>
  
  <h3>Install these python packages</h3>  
  <p>sudo apt install python3.10-full python3.10-dev -y</p>
  <hr>
  
  <h3>Install the following packages</h3>  
  <p>sudo apt install git curl build-essential dkms perl wget -y</p>  
  <p>sudo apt install gcc make default-libmysqlclient-dev libssl-dev -y</p>  
  <p>sudo apt install zlib1g-dev libbz2-dev libreadline-dev libsqlite3-dev llvm</p>
  <p>sudo apt install libncurses5-dev libncursesw5-dev xz-utils tk-dev libffi-dev liblzma-dev python3-openssl git</p>
  <hr>
    
  <h3>Pyenv</h3>  
  <p>curl -L https://github.com/pyenv/pyenv-installer/raw/master/bin/pyenv-installer | bash</p>
  <p>Follow Pyenv instructions</p>
  <hr>
  
  <h3>Baixar e instalar VS Code: https://code.visualstudio.com/download</h3>
  <hr>
  
  <h3>Below everything is optional</h3>
  <hr>
  
  <h3>Install and configure ZSH</h3>  
  <p>sudo apt install zsh -y</p>  
  <p>chsh -s /bin/zsh</p>  
  <p>zsh</p>
  <hr>
  
  <h3>Instalar Oh-my-zsh! -> https://ohmyz.sh/</h3>  
  <p>sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"</p>
  <hr>
  
  <h3>Install Spaceship Prompt</h3>
  <p>https://github.com/spaceship-prompt/spaceship-prompt</p>
  <p>git clone https://github.com/spaceship-prompt/spaceship-prompt.git "$ZSH_CUSTOM/themes/spaceship-prompt" --depth=1</p>
  <p>ln -s "$ZSH_CUSTOM/themes/spaceship-prompt/spaceship.zsh-theme" "$ZSH_CUSTOM/themes/spaceship.zsh-theme"</p>  
  <p>Change ~/.zshrc -> ZSH_THEME="spaceship"</p>  
  <p>nano ~/.zshrc</p>  
  <hr>
  
  <h3>Install Zsh Autosuggestions</h3>
  <p>https://github.com/zsh-users/zsh-autosuggestions</p>
  <p>git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions</p>
  <hr>
  
  <h3>Install Zsh Syntax Highlighting</h3>
  <p>https://github.com/zsh-users/zsh-syntax-highlighting</p>
  <p>git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting</p>
  <hr>
  
  <h3>Change plugins</h3>
  <p>plugins=(git zsh-autosuggestions zsh-syntax-highlighting)</p>
  <p>nano ~/.zshrc</p>     
  <p>Font optional (https://github.com/pdf/ubuntu-mono-powerline-ttf)</p>  
  <p>mkdir -p ~/.fonts</p>  
  <p>git clone https://github.com/pdf/ubuntu-mono-powerline-ttf.git ~/.fonts/ubuntu-mono-powerline-ttf</p>  
  <p>fc-cache -vf</p>
  <hr>  
  <h1>REBOOT!!!!!!!!!!!!!!!!!!!!!</h1>
  <hr>
</div>




