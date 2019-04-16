`cd` (acrônimo de _change directory_, trocar o diretório em inglês) nos permite navegar entre os diretórios do computador. Por exemplo, se no diretório atual existem os subdiretórios `drama`, `comedia` e `suspense`...

```bash
$ ls -l
drwxrwxr-x 2 dh dh 4096 oct 24 13:31 drama # observe o d inicial, o que significa que é um diretório
drwxrwxr-x 2 dh dh 4096 oct 24 13:31 comedia
-rw-rw-r-- 1 dh dh    0 oct 24 13:29 nem_o_tiro_final.txt
drwxrwxr-x 2 dh dh 4096 oct 24 13:30 suspense
```
...podemos trocar `drama` e depois listar seus arquivos:

```bash
$ cd drama
$ ls
o_livro_dos_seres_imaginarios.txt  ficcoes.txt
```

> Vejamos se você entendeu: troque para o diretório `comedia` e liste seus arquivos.  