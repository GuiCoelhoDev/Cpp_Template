# Template - C++

# Compilando

- excluir a pasta build antes de colocar os comandos de compilação abaixo
``` bash
# Linux
$ ./compile.sh -l

# Windows
$ ./compile.sh -w
```

# Executando

./cpp_template

## Analisadores 

## [Cppcheck 1.83](http://cppcheck.sourceforge.net) como analisador estático

Instalação no Linux

```
$ sudo apt-get install cppcheck
```

## [Valgrind](https://www.valgrind.org/) como analisador dinâmico

Instalação no Linux

```
$ sudo apt-get install valgrind
```

Executando com mais detalhes sobre vazamento de memória

``` bash
$ valgrind –leak-check=full ./prog
```