**Armas** são equipamentos utilizados para atacar, normalmente em um [[Confrontar|Confronto]].

Cada arma é descrita pelos seguintes campos:

| Campo | Descrição |
|---|---|
| **Nome** | o nome da arma |
| **Descrição** | uma descrição breve da arma |
| **Dano** | modificador flat (1, 2, 3…) somado ao dano em um Confronto |
| **Tipo de Dano** | o tipo de dano causado pela arma — Corte, Perfurante, Contusão, Fogo etc. (ver [[Armas#Tipos de Dano|Tipos de Dano]]) |
| **Propriedades** | Origem, Material e as características especiais da arma (ver [[#Propriedades]]) |
| **Maestria** | efeito especial da arma para quem a domina, se houver (ver [[#Maestria]]) |
| **Alcance** | o alcance, em quadrados, no qual a arma pode atingir seus alvos |
| **Carga** | quantos slots a arma ocupa |
| **Valor** | o custo da arma |

O **Dano** de uma arma corresponde ao **bônus da arma** aplicado em um Confronto, somado à Margem de Sucessos (ver [[Confrontar]]).

## Desarmado

Todo personagem possui uma arma natural, o **Desarmado**: socos, chutes, cotoveladas e o próprio corpo.

| Campo | Valor |
|---|---|
| **Uso** | Corpo a corpo |
| **Dano** | +0 |
| **Tipo de Dano** | Contusão |
| **Alcance** | 1 |
| **Carga** | 0 |

O Desarmado é de Origem **Natural** e Material **Orgânico**: está **sempre disponível**, não precisa ser equipado e não ocupa as mãos. Além disso, não pode ser removido, vendido ou perdido. Quando o personagem ataca sem nenhuma arma em mãos, ele usa o Desarmado.

Por padrão, o dano do Desarmado é **superficial** (ver [[Vida#Gravidade do Dano|Gravidade do Dano]]). Como seu bônus de dano é +0, um empate em um Confronto desarmado não causa dano.

O Trunfo [[Combate#Artista Marcial|Artista Marcial]] muda o Desarmado do personagem: Dano 2, Propriedade Leve e dano agravado.

## Propriedades

As **Propriedades** de uma arma são organizadas em quatro categorias. Toda arma tem exatamente uma **Origem** e um **Material**; as propriedades de **Empunhadura** e **Uso** são opcionais e podem ser combinadas.

### Origem (obrigatória, uma por arma)

- **Fabricada** — arma feita para ser usada como arma. É a origem padrão.
- **Improvisada** — objeto comum usado como arma.
- **Natural** — arma que faz parte do corpo, como punhos, garras, presas ou caudas. Está sempre disponível: não precisa ser equipada, não ocupa as mãos e não pode ser alvo da Manobra [[Manobras#Desarmar|Desarmar]]. O [[#Desarmado|Desarmado]] é Natural.

### Material (obrigatório, um por arma)

O Material representa uma categoria relevante para as defesas, em vez de distinguir cada matéria-prima comum.

| Material | Engloba |
|---|---|
| **Orgânico** | Corpo, carne, garras, presas, ossos e carapaças |
| **Madeira** | Madeira comum e outros materiais vegetais usados em armas |
| **Pedra** | Rocha, sílex, obsidiana e minerais comuns |
| **Metal comum** | Ferro, aço, bronze, cobre e outras ligas comuns |
| **Prata** | Material especial, com interação própria com as defesas |
| **Meteorito** | Material especial, com interação própria com as defesas |

**Materiais especiais** é uma categoria de organização, não uma opção selecionável. Cada material especial tem sua própria entrada. Toda arma continua tendo exatamente um Material: Prata e Meteorito não contam também como Metal comum.

O Material é considerado junto ao Tipo de Dano ao aplicar [[Resistência e Vulnerabilidade|Resistências, Vulnerabilidades e Imunidades]]. As Resistências e Vulnerabilidades ao Tipo e ao Material são somadas no cálculo da Absorção Efetiva; Imunidade a qualquer um deles ignora todo o dano. Por enquanto, esses valores de Material são definidos diretamente nos personagens e criaturas.

### Empunhadura (opcional)

- **Leve** — arma ágil e equilibrada.
- **Duas mãos** — arma que exige ser empunhada com as duas mãos para ser utilizada.

### Uso (opcional)

- **Arremesso (valor)** — arma que pode ser lançada como um ataque à distância. A Propriedade acompanha sempre um valor, que indica o **Alcance de arremesso** da arma, medido em quadrados — por exemplo, **Arremesso (6)** indica que a arma pode ser lançada a até 6 quadrados. Ataques de arremesso utilizam a Perícia **Atirar**. O campo **Alcance** da arma continua valendo para seu uso corpo a corpo. Em um [[Confrontar|Confronto]], a arma pode ser utilizada para **Aceitar o Confronto** contra um atacante à distância, desde que ele esteja dentro do Alcance de arremesso.

### Personagem (opcional)

- **Predileta** — a arma escolhida pelo Trunfo [[Combate#Arma Predileta|Arma Predileta]]. Quem tem o Trunfo ganha bônus ao usá-la.

Catálogos e módulos podem adicionar novas propriedades, origens e materiais, e definir os valores específicos de cada arma (Nome, Dano, Tipo de Dano, Alcance e demais campos).

## Maestria

A **Maestria** é um efeito especial que uma arma oferece a quem a domina. Cada arma possui **no máximo uma** Maestria, ou nenhuma.

Uma Maestria funciona de forma separada das Propriedades: a arma sempre a apresenta, mas o efeito só pode ser usado por um personagem que possua o [[Trunfos|Trunfo]] correspondente. Sem o Trunfo, a arma funciona normalmente, sem a Maestria.

As Maestrias costumam ser ativadas por resultados de um [[Confrontar|Confronto]], como vencer, empatar ou vencer por uma determinada Margem.

A lista de Maestrias e os Trunfos que as concedem ainda serão definidos.

## Tipos de Dano

O **Tipo de Dano** indica a natureza do ferimento causado — uma informação separada da **gravidade** do dano (ver [[Vida#Gravidade do Dano|Gravidade do Dano]]).

A lista inicial de tipos de dano é:

- **Físicos:** Corte, Contusão, Perfurante
- **Elementais:** Fogo, Gelo, Elétrica, Ácido, Veneno
- **Mágico:** Mágico

Cada fonte de dano define seu Tipo de Dano — por exemplo, uma espada causa Corte, uma maça causa Contusão e uma magia de fogo causa Fogo. Catálogos e módulos podem adicionar novos tipos de dano.
