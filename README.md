Lista 1 - Busca
=========================
Welison Lucas Almeida Regis - 2019.1

Lieverton Santos Silva - 2019.1

## PROPOSTA
Propõe-se nessa atividade utilizar **algoritmos de busca aplicados em um _dataset_ do jogo FIFA 19 (.csv)** a fim de recuperar os dados dos jogadores através do seu identificador exclusivo (ID).

**Buscas** utilizadas:
*    **Binária**;
*    **Ternária**;
*    **Sequência indexada**;
*    **Binária indexada**.

O trabalho avaliou a **performance dos diferentes algoritmos para diferentes tamanhos de _inputs_ randômicos**, gerando **gráficos** e explorando as informações prestadas contidas no _dataset_.

_Dataset_ dos jogadores do FIFA 19:  [dataset - FIFA](https://www.kaggle.com/karangadiya/fifa19).

## DEPENDÊNCIAS
Para executar este projeto são necessárias algumas dependencias, para a instalar siga o passo a passo:

1. Primeiramente abra o terminal:
```
Ctrl+Alt+t
```

2. Insira as linhas de comando, uma de cada vez, no terminal e tecle ENTER:

```
$ python3 -m pip install --upgrade 
$ python3 -m pip install jupyter
$ pip install matplotlib --user
$ pip install pandas --user
```

**Observação:** caso seja necessário utilize o comando `sudo`.
## ACESSO À APLICAÇÃO
Para testar a aplicação, execute os seguintes passos:
1. Faça uma cópia do repositório para o seu computador em um lugar de sua preferência.
	* Através do "git", faça um "git clone":

```
    $ git clone https://github.com/EDAII/Lista1_WelisonRegis_LievertonSilva
```

2. Entre na pasta do projeto:
```
    $ cd Lista1_WelisonRegis_LievertonSilva
```

3. Execute o projeto com o jupyter notebook:
```
    jupyter notebook lista1_algoritmos_busca.ipynb
```
Caso deseje visualizar uma versão já processada do código, acesse: [Algoritmos Busca](https://github.com/EDAII/Lista1_WelisonRegis_LievertonSilva/blob/master/lista1_algoritmos_busca.ipynb).

## FUNCIONAMENTO
Com o notebook aberto, execute cada célula por vez:

```
    shift + ENTER
``` 

Ao final será apresentado gráficos que descrevem a eficiência dos algoritmos de busca citados para um determinado _dataset_.