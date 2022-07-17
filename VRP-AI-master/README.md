# Problema de Roteamento de Veículos

Este código tem como objetivo encontrar uma solução para o Problema de Roteamento de Veículos (PRV, ou VRP em inglês).
Para isso, usamos Distâncias Euclidianas e o Algoritmo de Economias (Savings). 

## Uso
Dependências: <br>
```
$ python3
```

<br>

Para rodar o código use: <br>
```
$ python3 main.py
```

<br>

Deste modo o código irá rodar esperando dados do teclado, se quiser entrar com um arquivo de texto que está na pasta Instancias, use o seguinte comando: <br>
```
$ python3 main.py < instancias/vrpnc<numero>.txt
```
<br>

<br>
Após rodar, o código irá ler os dados e calcular as distâncias e as economias automaticamente! <br>
Após finalizado os cálculos, por padrão, serão impressos na tela as rotas e o custo total. Existem outras funções para imprimir dados na tela, basta fazer a chamada das mesmas dentro do método "start" no arquivo "vrp.py"
<br>

## Desenvolvedor

* Felipe Homrich Melchior - UNIPAMPA - [Perfil GitHub](https://github.com/homdreen)