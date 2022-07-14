# Chave SSH e Tokens :key:

### Chave SSH

- GitHub - Settings - SSH and GPG Keys - New SSH

  - Para gerar a chave = Git Bash.

  ssh-keygen -t ed25519 -c (email)

  cd /c/User/(nome)/.ssh

  ls

  cat id_ed25519.pub - colocar a chave pública no GitHub

  - Para ativar a chave (dentro desse cd /c/User/(nome)/.ssh):

  eval $ (ssh-agent -s)

  ssh -add id_ed25519

  

- Tokens
  - GitHub - Dev Settings - Personal Access Token - Generate new token
  - É necessário salvar o token em algum lugar , pois ele não será mostrado novamente
