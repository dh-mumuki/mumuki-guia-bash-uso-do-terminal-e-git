Agora podemos adicionar arquivos. Maaaaais, cuidado, não é o suficiente para colocá-los no diretório, para isso **devemos também incluí-los explicitamente**.  Vamos ver um exemplo: 

```bash
# Estamos no diretório de um repositório ...
$ pwd 
/home/mumuki/auobiografia
# ... que está vazio
$ ls
# Usando o novo comando touch...  
$ touch capitulo1.txt
# ..nós criamos um arquivo vazio
$ ls 
capitulo1.txt
# Agora nós verificamos o status do repositório
$ git status 
On branch master

Initial commit

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	capitulo1.txt

nothing added to commit but untracked files present (use "git add" to track)
```

Preste atenção na seção que diz _Untracked files_: se houver arquivos listados aqui, isso significa que eles devem ser incorporados ao repositório.

> Mover para o diretório `autobiografia`, digitar `git add capitulo1.txt`, depois `git status` e veja se a mensagem muda.




