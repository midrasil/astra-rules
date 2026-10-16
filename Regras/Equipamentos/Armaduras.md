**Armaduras** são equipamentos utilizados para proteger o personagem.

Cada armadura é descrita pelos seguintes campos:

| Campo            | Descrição                                                           |
| ---------------- | ------------------------------------------------------------------- |
| **Nome**         | o nome da armadura                                                  |
| **Descrição**    | uma descrição breve da armadura                                     |
| **Absorção**     | quantos pontos de dano agravado são convertidos em dano superficial |
| **Propriedades** | características especiais da armadura                               |
| **Carga**        | quantos slots a armadura ocupa                                      |
| **Valor**        | o custo da armadura                                                 |

## Absorção

A **Absorção** de uma armadura indica **quanto dano agravado recebido é convertido em dano superficial**.

Ao sofrer dano de um ataque, o personagem converte para superficial um número de pontos de dano agravado igual à sua Absorção — nunca mais do que o próprio dano agravado recebido. A Absorção total é a soma da **Absorção base** do personagem e da Absorção das armaduras equipadas. A Absorção base pode ser aumentada ou reduzida por efeitos, mas nunca fica abaixo de 0.

Por exemplo: uma armadura com **Absorção 2** sofre um ataque que causa **3 de dano agravado**. São convertidos **2 pontos** em dano superficial, e apenas **1 ponto** permanece agravado.

Dano que já é superficial não é afetado: a armadura apenas reduz a quantidade de dano que permanece agravado.

Resistências e Vulnerabilidades a [[Armas#Tipos de Dano|Tipos de Dano]] específicos podem aumentar ou reduzir essa absorção (ver [[Resistência e Vulnerabilidade|Resistência e Vulnerabilidade]]).

## Propriedades

As **Propriedades** representam características especiais de uma armadura. A lista inicial de propriedades é:

- **Resistência a [Tipo] (valor)** — a armadura concede [[Resistência]] ao [[Armas#Tipos de Dano|Tipo de Dano]] indicado. O valor é somado à [[Resistência e Vulnerabilidade#Absorção Efetiva|Absorção Efetiva]] contra aquele Tipo — por exemplo, uma armadura com **Absorção 2** e **Resistência a Corte (1)** tem Absorção Efetiva 3 contra Corte e 2 contra os demais Tipos.

Catálogos e módulos podem adicionar novas propriedades e definir os valores específicos de cada armadura.
