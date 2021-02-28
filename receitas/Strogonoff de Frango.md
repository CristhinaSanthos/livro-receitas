# Strogonoff de Frango :chicken:

# Ingredientes

- 1 quilo de peito de frango 

- 1 tablete de caldo de galinha
- 3 colheres de sopa de óleo
- 2 cxs de creme de leite
- 2 colheres de sopa de molho de tomate
- 2 colheres de sopa de ketchup
- 2 colheres de sopa de mostarda
- Champignon
- Batata pallha e arroz branco p acompanhar
- Alho e cebola para refogar

## Modo de Preparo

1. Refogue o frango picado numa panela com óleo, alho e cebola. Acrescente o caldo de galinha e uma xícara de água. Deixe cozinhar até secar a água. 
2. Acrescente o molho de tomate, o ketchup, a mostarda, o creme de leite e o champignon a gosto.
3. Mexa bem até ficar um creme homogêneo
4. Sirva a seguir



**Negrito**  _italico_  

1. [colocar um ponto lista numerada]
2. 



ver no item ajuda Markdown Reference

______________________________

Git bash dessa aula

user@CristhinaSanthos MINGW64 /c
$ cd workspace

user@CristhinaSanthos MINGW64 /c/workspace
$ ls
livro-receitas/

user@CristhinaSanthos MINGW64 /c/workspace
$ mkdir receitas_2

user@CristhinaSanthos MINGW64 /c/workspace
$ ls
livro-receitas/  receitas_2/

user@CristhinaSanthos MINGW64 /c/workspace
$ cd receitas_2

user@CristhinaSanthos MINGW64 /c/workspace/receitas_2
$ git init
Initialized empty Git repository in C:/workspace/receitas_2/.git/

--- criou pasta oculta do git, onde git versiona os objetos

user@CristhinaSanthos MINGW64 /c/workspace/receitas_2 (master)
$ $ ls -a
./  ../  .git/

user@CristhinaSanthos MINGW64 /c/workspace/receitas_2 (master)
$ cd .git

user@CristhinaSanthos MINGW64 /c/workspace/receitas_2/.git (GIT_DIR!)
$

user@CristhinaSanthos MINGW64 /c
$ cd workspace

user@CristhinaSanthos MINGW64 /c/workspace/livro-receitas (master)
$ cd .git

user@CristhinaSanthos MINGW64 /c/workspace/livro-receitas/.git (GIT_DIR!)
$ ls
HEAD  config  description  hooks/  info/  objects/  refs/

user@CristhinaSanthos MINGW64 /c/workspace/livro-receitas/.git (GIT_DIR!)
$ cd ..

user@CristhinaSanthos MINGW64 /c/workspace/livro-receitas (master)
$ git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Turn this message off by running
hint: "git config advice.addEmptyPathspec false"

user@CristhinaSanthos MINGW64 /c/workspace/livro-receitas (master)
$ git add *

user@CristhinaSanthos MINGW64 /c/workspace/livro-receitas (master)
$ git -m "commit inicial"
unknown option: -m
usage: git [--version] [--help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           <command> [<args>]

user@CristhinaSanthos MINGW64 /c/workspace/livro-receitas (master)
$ git commit -m "commit inicial"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'user@CristhinaSanthos.(none)')

user@CristhinaSanthos MINGW64 /c/workspace/livro-receitas (master)
$ git config --global user.name "CristhinaSanthos"

user@CristhinaSanthos MINGW64 /c/workspace/livro-receitas (master)
$ git commit -m "commit inicial"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'user@CristhinaSanthos.(none)')

user@CristhinaSanthos MINGW64 /c/workspace/livro-receitas (master)
$ git config --global user.email "cristhinasanthos@outlook.com"

user@CristhinaSanthos MINGW64 /c/workspace/livro-receitas (master)
$ git commit -m "commit inicial"
[master (root-commit) 95294a1] commit inicial
 2 files changed, 8 insertions(+)
 create mode 100644 Strogonoff de Frango.md
 create mode 100644 strogonoff.md

user@CristhinaSanthos MINGW64 /c/workspace/livro-receitas (master)
$





Aula 5 user@CristhinaSanthos MINGW64 /c/workspace
$ cd receitas_2

user@CristhinaSanthos MINGW64 /c/workspace/receitas_2 (master)
$ git status
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)

user@CristhinaSanthos MINGW64 /c/workspace/receitas_2 (master)
$ cd ..

user@CristhinaSanthos MINGW64 /c/workspace
$ cd livro-receitas

user@CristhinaSanthos MINGW64 /c/workspace/livro-receitas (master)
$ ls
'Strogonoff de Frango.md'   receitas/   strogonoff.md

user@CristhinaSanthos MINGW64 /c/workspace/livro-receitas (master)
$ mvStrogonoff de Frango.md./receitas
bash: mvStrogonoff: command not found

user@CristhinaSanthos MINGW64 /c/workspace/livro-receitas (master)
$ mvStrogonoff de Frango.md ./receitas
bash: mvStrogonoff: command not found

user@CristhinaSanthos MINGW64 /c/workspace/livro-receitas (master)
$ mv Strogonoff de Frango.md ./receitas
mv: cannot stat 'Strogonoff': No such file or directory
mv: cannot stat 'de': No such file or directory
mv: cannot stat 'Frango.md': No such file or directory

user@CristhinaSanthos MINGW64 /c/workspace/livro-receitas (master)
$ mv 'Strogonoff de Frango.md' ./receitas

user@CristhinaSanthos MINGW64 /c/workspace/livro-receitas (master)
$