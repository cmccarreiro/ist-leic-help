# Prolog Setup Help

Ajuda para quem quiser instalar e perceber como correr Prolog na sua máquina.

## 1. Fazer download do Prolog

Fazer download da [última stable version do SWI-Prolog](http://www.swi-prolog.org/download/stable).

![alt text](/lp/prolog-setup-help-imgs/prolog-download.JPG "prolog download")

Em princípio, ficas com a aplicação "normal" (SWI-Prolog) e a consola (SWI-Prolog console).

## 2. Criar ficheiro .pl
 
Escreve o teu código no teu editor de texto favorito, guardando-o como <nome-do-ficheiro>.pl

![alt text](/lp/prolog-setup-help-imgs/programa-exemplo-2.JPG "prolog programa exemplo")

## 3. Importar e usar o teu programa

- Abrir a consola (SWI-Prolog console)

- No **Windows** correr:
```?- working_directory(_, "<diretoria>").```

- No **Mac** ou **Linux** correr:
```?- working_directory(_, "/Users/<diretoria>").```

Nota1: Sim, podes usar o teu amigo Ctrl-C; Ctrl-V.

ATENÇÃO: na diretoria deves acrescentar uma \ por cada \ no caminho, tal como no exemplo! (No Mac ou Linux, fazer / por cada /)

- Corres o teu programa assim:
```?- [programa].```

![alt text](/lp/prolog-setup-help-imgs/prolog-console-3.JPG "prolog console exemplo")

A partir deste momento podes escrever a query que quiseres! :)

