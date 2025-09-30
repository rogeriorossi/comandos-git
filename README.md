# COMANDOS Git
Comandos utilizados pelo Git para subir arquivos para o GitHub

### Primeira vez
| COMANDO | DESCRICAO |
| --- | --- |
| `git init` | Inicia o repositorio git local |

### Push

| # | COMANDO | DESCRICAO |
| --- | --- | --- |
| 1 | `git add .` | Adicina os arquivos alterados para fazer upload |
| 2 | `git commit -m "mensagem"` | Comita os arquivos no repositorio local |
| 3 | `git remote add <apelido> <caminho do diretorio no github>` | Cria uma conexão entre o local e o diretorio do git hub. **Só vai ser usado uma vez** <br/>Ex.: `git remote add origin https://github.com/rogeriorossi/dreamsky.git`|
| 4 | `git branch -m novo-nome` | Mudar o nome da branch |
| 4 | `git push -u origin main` | Envia os arquivos modificados ou criados para o github |

### Merge
| # | COMANDO | DESCRICAO |
| --- | --- | --- |
| - | `git checkout -b <branch name>` | cria uma nova branch |
| 1 | `git checkout main` | Vai para a branch que receberá os arquivos alterados |
| 2 | `git merge <branch-doadora>` | Coloca o nome da branch que vai enviar os dados. <br/>Ex.: `git merge branch2` |
| 3 | `git add .` | Adiciona os arquivos alterados para fazer upload |
| 4 | `git commit -m "mensagem"` | Comita os arquivos no repositorio local |
| 5 | `git push -u origin main` | Envia os arquivos modificados ou criados para o github |

### Outros Comandos

| COMANDO | DESCRICAO |
| --- | --- |
| `git status` | mostra o status dos arquivos novos ou alterados |
| `git reset` | volta a condição antes do ultimo commit |
| `git clone <diretorio remoto no github>` | Clona o diretório do github para sua máquina local <br/>Ex: `git clone https://github.com/rogeriorossi/comandos-git.git` |
| | |
| `git config user.name "Fulano de Tal"` | Configura o nome em um computador novo. **Só será necessário uma vez** |
| `git config user.email teste@teste.com` | Configura o email em um computador novo. **Só será necessário uma vez** |
