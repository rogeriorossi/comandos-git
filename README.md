# COMANDOS Git
Comandos utilizados pelo Git para subir arquivos para o GitHub


### Primeira vez
| COMANDO | DESCRICAO |
| --- | --- |
| `git init` | Inicia o repositorio git local |

### Comandos

| COMANDO | DESCRICAO |
| --- | --- |
| 1. `git add .` | Adicina os arquivos alterados para fazer upload |
| 2. `git commit -m "mensagem"` | Comita os arquivos no repositorio local |
| 3. `git remote add <apelido> <caminho do diretorio no github>` | Cria uma conexão entre o local e o diretorio do git hub. **Só vai ser usado uma vez** |
| | Ex.: `git remote add origin https://github.com/rogeriorossi/dreamsky.git` |
| 4. `git push -u origin main` | Envia os arquivos modificados ou criados para o github |

### Outros Comandos

| COMANDO | DESCRICAO |
| --- | --- |
| `git status` | mostra o status dos arquivos novos ou alterados |
| `git reset` | volta a condição enates do ultimo commit |
