**Armas** são equipamentos utilizados para atacar, normalmente em um [Confronto](../Cenas%20e%20Conflitos/A%C3%A7%C3%B5es/Confrontar.md).

Cada arma é descrita pelos seguintes campos:

| Campo | Descrição |
|---|---|
| **Nome** | o nome da arma |
| **Descrição** | uma descrição breve da arma |
| **Dano** | modificador flat (1, 2, 3…) somado ao dano em um Confronto |
| **Tipo de Dano** | o tipo de dano causado pela arma — Corte, Perfurante, Contusão, Fogo etc. (ver [Tipos de Dano](#tipos-de-dano)) |
| **Propriedades** | Origem, Material e as características especiais da arma (ver [Propriedades](#propriedades)) |
| **Alcance** | o alcance, em quadrados, no qual a arma pode atingir seus alvos |
| **Carga** | quantos slots a arma ocupa |
| **Valor** | o custo da arma |

O **Dano** de uma arma corresponde ao **bônus da arma** aplicado em um Confronto, somado à Margem de Sucessos (ver [Confrontar](../Cenas%20e%20Conflitos/A%C3%A7%C3%B5es/Confrontar.md)).

As armas disponíveis no núcleo estão em [Catálogo de Armas](Cat%C3%A1logo%20de%20Armas.md).

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

Por padrão, o dano do Desarmado é **superficial** (ver [Gravidade do Dano](../Personagens/Vida.md#gravidade-do-dano)). Como seu bônus de dano é +0, um empate em um Confronto desarmado não causa dano. Capacidades podem modificar essas características quando seu efeito disser expressamente.

## Propriedades

As **Propriedades** de uma arma são organizadas em cinco categorias. Toda arma tem exatamente uma **Origem** e um **Material**; as propriedades de **Empunhadura**, **Uso** e **Especial** são opcionais e podem ser combinadas conforme a entrada da arma.

### Origem (obrigatória, uma por arma)

- **Fabricada** — arma feita para ser usada como arma. É a origem padrão.
- **Improvisada** — objeto comum usado como arma.
- **Natural** — arma que faz parte do corpo, como punhos, garras, presas ou caudas. Está sempre disponível: não precisa ser equipada, não ocupa as mãos e não pode ser alvo da Manobra [Desarmar](../Cenas%20e%20Conflitos/A%C3%A7%C3%B5es/Manobras.md#desarmar). O [Desarmado](#desarmado) é Natural.

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

O Material é considerado junto ao Tipo de Dano ao aplicar [Resistências, Vulnerabilidades e Imunidades](../Resist%C3%AAncia%20e%20Vulnerabilidade/Resist%C3%AAncia%20e%20Vulnerabilidade.md). As Resistências e Vulnerabilidades ao Tipo e ao Material são somadas no cálculo da Absorção Efetiva; Imunidade a qualquer um deles ignora todo o dano. Por enquanto, esses valores de Material são definidos diretamente nos personagens e criaturas.

### Empunhadura (opcional)

- **Leve** — arma ágil e equilibrada.
- **Duas mãos** — arma que exige ser empunhada com as duas mãos para ser utilizada.
- **Flexível** — arma que pode ser usada com uma mão ou com as duas. Empunhada com as duas mãos, recebe **+1 de Dano**.
- **Acoplada** — arma presa ao corpo ou à armadura, que não ocupa a mão e não pode ser alvo da Manobra [Desarmar](../Cenas%20e%20Conflitos/A%C3%A7%C3%B5es/Manobras.md#desarmar). Ela só ataca quando a mão em que está acoplada não segura nada. Cada mão tem no máximo uma arma Acoplada.

### Uso (opcional)

- **Pesado** — Ataques realizados com esta arma utilizam **Força no lugar de Agilidade**, mantendo a Perícia determinada pela forma do ataque. Uma arma Pesada corpo a corpo utiliza **Força + Lutar**; uma arma Pesada de disparo utiliza **Força + Atirar**. Essa substituição é obrigatória, não acrescenta dados nem Dano e não faz Força contribuir novamente para o dano. Pesado modifica somente Ataques: não altera as Reservas de Manobras realizadas com a arma. Uma Capacidade que estabeleça expressamente o Atributo do Ataque sempre prevalece sobre Pesado.

- **Arremesso (valor)** — arma que pode ser lançada como um ataque à distância. A Propriedade acompanha sempre um valor, que indica o **Alcance de arremesso** da arma, medido em quadrados — por exemplo, **Arremesso (6)** indica que a arma pode ser lançada a até 6 quadrados. Ataques de arremesso utilizam **Força + Arremessar**, salvo substituição explícita. O campo **Alcance** da arma continua valendo para seu uso corpo a corpo. Em um [Confronto](../Cenas%20e%20Conflitos/A%C3%A7%C3%B5es/Confrontar.md), a arma pode ser utilizada para **Aceitar o Confronto** contra um atacante à distância, desde que ele esteja dentro do Alcance de arremesso.

- **Versátil (tipo de dano)** — arma que tem um segundo Tipo de Dano, indicado na Propriedade. O atacante escolhe qual usar a cada Ataque. Por exemplo, uma arma Perfurante com **Versátil (Corte)**.
- **Não letal** — o dano da arma é sempre **superficial** (ver [Gravidade do Dano](../Personagens/Vida.md#gravidade-do-dano)). Para causar dano agravado com ela, o atacante sofre **-2 dados** no Ataque.
- **Manobra (Reposicionar, Derrubar ou Desarmar)** — a arma pode ser usada para realizar a [Manobra](../Cenas%20e%20Conflitos/A%C3%A7%C3%B5es/Manobras.md) indicada até o **Alcance** da arma, em vez de exigir contato físico. A Manobra não recebe bônus da arma e conserva sua Reserva própria; inclusive, a propriedade Pesado não altera essa Reserva.

### Especial (opcional, no máximo uma por arma)

Uma Propriedade Especial concede um efeito característico do modelo da arma. Ela pertence à própria arma, não precisa ser adquirida separadamente e pode ser utilizada por qualquer personagem que empunhe a arma.

Cada arma pode possuir no máximo **uma Propriedade Especial**. Essas Propriedades podem criar efeitos ao vencer um Ataque, modificar uma interação específica ou representar uma vantagem que não cabe nas categorias estruturais anteriores.

Técnicas aprendidas pelo personagem continuam pertencendo às **Capacidades**. Uma Propriedade Especial descreve o que a arma faz; uma Capacidade descreve o que o personagem sabe fazer com ela.

Uma Propriedade Especial que diga **ao vencer um Ataque** não é ativada em caso de empate. Quando o efeito exige abrir mão da Margem, o atacante decide depois de vencer e antes de calcular o dano; o alvo sofre somente o Dano da arma, além dos demais efeitos indicados.

- **Letal** — ao vencer um Ataque, cada par de dados que mostrem **10** na rolagem do atacante soma o **Dano da arma** mais uma vez ao dano causado.
- **Varredura** — ao vencer um Ataque corpo a corpo, o atacante pode abrir mão da Margem. O alvo original sofre somente o Dano da arma, e um segundo alvo à escolha do atacante sofre o mesmo Dano como dano superficial. O segundo alvo precisa estar ao alcance da arma e adjacente ao alvo original; ele não realiza outra rolagem para responder.
- **Debilitante (Abalado)** — ao vencer um Ataque, o atacante pode abrir mão da Margem. O alvo sofre somente o Dano da arma e fica [Abalado](../Condi%C3%A7%C3%B5es/Abalado.md).
- **Debilitante (Lento)** — ao vencer um Ataque, o atacante pode abrir mão da Margem. O alvo sofre somente o Dano da arma e fica [Lento](../Condi%C3%A7%C3%B5es/Lento.md).

Módulos e cenários podem adicionar novas propriedades, origens, materiais e armas ao catálogo do núcleo.

## Tipos de Dano

O **Tipo de Dano** indica a natureza do ferimento causado — uma informação separada da **gravidade** do dano (ver [Gravidade do Dano](../Personagens/Vida.md#gravidade-do-dano)).

A lista inicial de tipos de dano é:

- **Físicos:** Corte, Contusão, Perfurante
- **Elementais:** Fogo, Gelo, Elétrica, Ácido, Veneno
- **Mágico:** Mágico

Cada fonte de dano define seu Tipo de Dano — por exemplo, uma espada causa Corte, uma maça causa Contusão e uma magia de fogo causa Fogo. Catálogos e módulos podem adicionar novos tipos de dano.
