# ZSH
  - clone o repositório
  - copie o .zshrc para a home
  ```shel
    cp .zshrc ~/
  ```

## Configurando o ambiente
  - instale o zsh `sudo apt install zsh`
  - instale o [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)
  
  via curl
  ```shell
   sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
  ``` 
  
  - O tema usado neste .zshrc é o [spaceship](https://github.com/denysdovhan/spaceship-prompt#installing)
  
  instale o tema, clonando o repositório.
  ```shell
    git clone https://github.com/denysdovhan/spaceship-prompt.git "$ZSH_CUSTOM/themes/spaceship-prompt"
  ```
  
  crie um link simbólico
  ```shell
    ln -s "$ZSH_CUSTOM/themes/spaceship-prompt/spaceship.zsh-theme" "$ZSH_CUSTOM/themes/spaceship.zsh-theme"
  ```
  
  
