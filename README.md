# GIT E GITHUB

Guia prático de GIT para iniciantes.

### Instalação

https://git-scm.com/download

# SCENES

- [X] Você deseja criar pontos na história da produção do seu projeto;
- [X] Você deseja verificar mudanças feitas no seu projeto;

- [X] Você começa uma nova funcionalidade no seu projeto, sem estragar o que já foi feito;
- [X] Você adiciona as novas funcionalidades no sou projeto em produção;
- [X] Você quer deletar a branch da nova funcionalidade, depois de aplicar em sou projeto;


### Comandos terminal GIT

- `git init` // Inicia a linha do tempo;
- `git add landingpage.html` // Adiciona ou atualiza mudanças para irem para linha do tempo; (Adicionar todos arquivos: `git add .` )
- `git commit -m "add landingpage"` // Adiciona um ponto na linha do tempo;
- `git log` // Visualiza os pontos na linha do tempo / commit;
- `git status` // Informa o estado das alterações do nosso projeto;
- `git show` // Apresenta determinados pontos na história; (Apertar "Q" para sair e "Barra de Espaço" para mostrar tudo)
- `git branch freature/cart` // Cria uma linha do tempo paralela com o nome de freature/cart;
- `git checkout freature/cart` // Muda para outra linha do tempo paralela; (Volta para a principal: `git checkout master`)
- `git merge feature/cart` // Junta a linha principal com a paralela;
- `git branch -D feature/cart` // Deleta a linha paralela;
- `git remote add origin git@github.com:lucaslange-ti/teste-git.git` // Linka o diretório com o GIT;
- `git remote -v` // Ver repositórios remotos;



- `git config -local user.name "lucaslange-ti"` // Define o autor;
- `git config --local user.email "lucaslange.ti@gmail.com"` // Define o e-mail;

### Comandos terminal VSC

- `ni teste.txt` -> cria um arquivo sem abrir
- `code -r teste.txt` -> abre um arquivo novo (semelhante a criar)