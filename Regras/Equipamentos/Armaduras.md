**Armaduras** são equipamentos utilizados para proteger o personagem.

Cada armadura é descrita pelos seguintes campos:

| Campo            | Descrição                                                           |
| ---------------- | ------------------------------------------------------------------- |
| **Nome**         | o nome da armadura                                                  |
| **Categoria**    | Leve, Média ou Pesada (ver [Categorias](#categorias))                         |
| **Força mínima** | a Força necessária para vestir a armadura sem perder Movimentação   |
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

Resistências e Vulnerabilidades a [Tipos de Dano](Armas.md#tipos-de-dano) específicos podem aumentar ou reduzir essa absorção (ver [Resistência e Vulnerabilidade](../Resist%C3%AAncia%20e%20Vulnerabilidade/Resist%C3%AAncia%20e%20Vulnerabilidade.md)).

## Categorias

Toda armadura tem uma **Categoria**, que define o seu custo.

| Categoria | Absorção | Ao Esquivar | Força mínima |
|---|---|---|---|
| **Leve** | 1 | sem penalidade | — |
| **Média** | 2 a 3 | -2 a -3 dados | 2 |
| **Pesada** | 4 a 5 | -4 a -5 dados | 3 |

- **Esquivar:** com armadura Média ou Pesada, a Reserva de Esquivar perde dados iguais à **Absorção da armadura**. A Absorção base do personagem e as Resistências não contam.
- **Força mínima:** com Força abaixo da Força mínima da armadura vestida, o personagem tem **-2 de Movimentação**.

## Propriedades

As **Propriedades** representam características especiais de uma armadura. A lista inicial de propriedades é:

- **Resistência a [Tipo] (valor)** — a armadura concede [Resistência](../Resist%C3%AAncia%20e%20Vulnerabilidade/Resist%C3%AAncia.md) ao [Tipo de Dano](Armas.md#tipos-de-dano) indicado. O valor é somado à [Absorção Efetiva](../Resist%C3%AAncia%20e%20Vulnerabilidade/Resist%C3%AAncia%20e%20Vulnerabilidade.md#absor%C3%A7%C3%A3o-efetiva) contra aquele Tipo — por exemplo, uma armadura com **Absorção 2** e **Resistência a Corte (1)** tem Absorção Efetiva 3 contra Corte e 2 contra os demais Tipos.
- **Vulnerabilidade a [Tipo] (valor)** — a armadura deixa o portador [vulnerável](../Resist%C3%AAncia%20e%20Vulnerabilidade/Resist%C3%AAncia%20e%20Vulnerabilidade.md) ao Tipo de Dano indicado. O valor é subtraído da [Absorção Efetiva](../Resist%C3%AAncia%20e%20Vulnerabilidade/Resist%C3%AAncia%20e%20Vulnerabilidade.md#absor%C3%A7%C3%A3o-efetiva) contra aquele Tipo — por exemplo, as armaduras de metal têm **Vulnerabilidade a Elétrico (1)**: uma Cota de Malha com Absorção 4 fica com 3 contra Elétrico.

Catálogos e módulos podem adicionar novas propriedades e definir os valores específicos de cada armadura.
