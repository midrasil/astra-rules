**Armas** são equipamentos utilizados para atacar, normalmente em um [Confronto](../Cenas%20e%20Conflitos/A%C3%A7%C3%B5es/Confrontar.md).

Cada arma é descrita pelos seguintes campos:

| Campo | Descrição |
|---|---|
| **Nome** | o nome da arma |
| **Descrição** | uma descrição breve da arma |
| **Dano** | modificador flat (1, 2, 3…) somado ao dano em um Confronto |
| **Tipo de Dano** | o tipo de dano causado pela arma — Corte, Perfurante, Contusão, Fogo etc. (ver [Tipos de Dano](#tipos-de-dano)) |
| **Propriedades** | Origem, Material e as características especiais da arma (ver [Propriedades](#propriedades)) |
| **Maestria** | efeito especial da arma para quem a domina, se houver (ver [Maestria](#maestria)) |
| **Alcance** | o alcance, em quadrados, no qual a arma pode atingir seus alvos |
| **Carga** | quantos slots a arma ocupa |
| **Valor** | o custo da arma |

O **Dano** de uma arma corresponde ao **bônus da arma** aplicado em um Confronto, somado à Margem de Sucessos (ver [Confrontar](../Cenas%20e%20Conflitos/A%C3%A7%C3%B5es/Confrontar.md)).

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

Por padrão, o dano do Desarmado é **superficial** (ver [Gravidade do Dano](../Personagens/Vida.md#gravidade-do-dano)). Como seu bônus de dano é +0, um empate em um Confronto desarmado não causa dano.

O Trunfo [Artista Marcial](../Personagens/Trunfos/Combate.md#artista-marcial) muda o Desarmado do personagem: Dano 2, Propriedade Leve e dano agravado.

## Propriedades

As **Propriedades** de uma arma são organizadas em quatro categorias. Toda arma tem exatamente uma **Origem** e um **Material**; as propriedades de **Empunhadura** e **Uso** são opcionais e podem ser combinadas.

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

- **Arremesso (valor)** — arma que pode ser lançada como um ataque à distância. A Propriedade acompanha sempre um valor, que indica o **Alcance de arremesso** da arma, medido em quadrados — por exemplo, **Arremesso (6)** indica que a arma pode ser lançada a até 6 quadrados. Ataques de arremesso utilizam a Perícia **Atirar**. O campo **Alcance** da arma continua valendo para seu uso corpo a corpo. Em um [Confronto](../Cenas%20e%20Conflitos/A%C3%A7%C3%B5es/Confrontar.md), a arma pode ser utilizada para **Aceitar o Confronto** contra um atacante à distância, desde que ele esteja dentro do Alcance de arremesso.

- **Versátil (tipo de dano)** — arma que tem um segundo Tipo de Dano, indicado na Propriedade. O atacante escolhe qual usar a cada Ataque. Por exemplo, uma arma Perfurante com **Versátil (Corte)**.
- **Não letal** — o dano da arma é sempre **superficial** (ver [Gravidade do Dano](../Personagens/Vida.md#gravidade-do-dano)). Para causar dano agravado com ela, o atacante sofre **-2 dados** no Ataque.
- **Manobra (Reposicionar, Derrubar ou Desarmar)** — a arma pode ser usada para realizar a [Manobra](../Cenas%20e%20Conflitos/A%C3%A7%C3%B5es/Manobras.md) indicada até o **Alcance** da arma, em vez de exigir contato físico. A Manobra não recebe bônus da arma.

As Propriedades são traços simples da arma: como ela é empunhada, que tipo de dano causa e como pode ser usada. Capacidades especiais pertencem às [Maestrias](#maestria).

### Personagem (opcional)

- **Predileta** — a arma escolhida pelo Trunfo [Arma Predileta](../Personagens/Trunfos/Combate.md#arma-predileta). Quem tem o Trunfo ganha bônus ao usá-la.

Catálogos e módulos podem adicionar novas propriedades, origens e materiais, e definir os valores específicos de cada arma (Nome, Dano, Tipo de Dano, Alcance e demais campos).

## Maestria

A **Maestria** é uma técnica que o personagem domina com uma arma específica. Ela não pertence à arma: é o personagem quem escolhe qual Maestria aplica à sua arma ao adquirir o [Trunfo Maestria com Arma](../Personagens/Trunfos/Combate.md#maestria-com-arma).

Cada cópia do Trunfo vale para **uma** arma Predileta do personagem e lhe dá **uma** Maestria. Qualquer Maestria pode ser escolhida para qualquer arma. Se a arma Predileta for perdida, a Maestria passa para a substituta junto com a Predileta, no mesmo prazo.

Toda Maestria é ativada ao **vencer um Ataque** com a arma. Em empate ela não ativa. Cada Maestria diz o que mais é preciso e se tem custo.

### Lista de Maestrias

- **Golpe Tático** — ao vencer o Ataque, o personagem pode **abrir mão da Margem**: causa só o Dano da arma e aplica ao alvo o efeito de uma destas Manobras, à sua escolha: [Reposicionar](../Cenas%20e%20Conflitos/A%C3%A7%C3%B5es/Manobras.md#reposicionar), [Derrubar](../Cenas%20e%20Conflitos/A%C3%A7%C3%B5es/Manobras.md#derrubar) ou [Desarmar](../Cenas%20e%20Conflitos/A%C3%A7%C3%B5es/Manobras.md#desarmar). O alvo não faz outra rolagem para resistir.
- **Embalo** — ao vencer o Ataque, o personagem ganha um acúmulo de [Embalo](../Condi%C3%A7%C3%B5es/Embalo.md) contra aquele alvo. Cada acúmulo dá **+1 dado** nos Ataques contra o mesmo alvo.
- **Varredura** — ao vencer o Ataque, o personagem também causa o **Dano da arma**, como dano **superficial**, em outro alvo adjacente ao primeiro.
- **Golpe Letal** — funciona como um acerto crítico: ao vencer o Ataque, cada **par de 10** da rolagem do atacante soma o **Dano da arma** mais uma vez ao dano.
- **Golpe Debilitante** — ao vencer o Ataque, o personagem aplica ao alvo, à sua escolha, a condição [Lento](../Condi%C3%A7%C3%B5es/Lento.md) ou [Abalado](../Condi%C3%A7%C3%B5es/Abalado.md), até o começo do seu próximo Turno.

## Tipos de Dano

O **Tipo de Dano** indica a natureza do ferimento causado — uma informação separada da **gravidade** do dano (ver [Gravidade do Dano](../Personagens/Vida.md#gravidade-do-dano)).

A lista inicial de tipos de dano é:

- **Físicos:** Corte, Contusão, Perfurante
- **Elementais:** Fogo, Gelo, Elétrica, Ácido, Veneno
- **Mágico:** Mágico

Cada fonte de dano define seu Tipo de Dano — por exemplo, uma espada causa Corte, uma maça causa Contusão e uma magia de fogo causa Fogo. Catálogos e módulos podem adicionar novos tipos de dano.
