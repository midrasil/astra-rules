**Armas** são equipamentos utilizados para atacar, normalmente em um [Confronto](../Cenas%20e%20Conflitos/A%C3%A7%C3%B5es/Confrontar.md).

Cada arma é descrita pelos seguintes campos:

| Campo | Descrição |
|---|---|
| **Nome** | o nome da arma |
| **Dano** | modificador fixo (1, 2, 3…) somado ao dano em um Confronto |
| **Tipo de Dano** | o tipo de dano causado pela arma — Corte, Perfurante, Contusão, Fogo etc. (ver [Tipos de Dano](#tipos-de-dano)) |
| **Empunhadura** | como a arma é empunhada (ver [Empunhadura](#empunhadura-opcional)) |
| **Alcance** | o alcance, em quadrados, no qual a arma pode atingir seus alvos |
| **Outras Propriedades** | as Propriedades de Uso da arma (ver [Uso](#uso-opcional)) |
| **Maestria** | o efeito que só quem domina a arma usa (ver [Maestria](#maestria-opcional-no-m%C3%A1ximo-uma-por-arma)) |
| **Material** | a categoria do material da arma (ver [Material](#material-obrigat%C3%B3rio-um-por-arma)) |
| **Carga** | quanto ocupa da Carga máxima |
| **Valor** | o custo da arma |

O **Dano** de uma arma corresponde ao **bônus da arma** aplicado em um Confronto, somado à Margem de Sucessos (ver [Confrontar](../Cenas%20e%20Conflitos/A%C3%A7%C3%B5es/Confrontar.md)).

As armas disponíveis no núcleo estão em [Catálogo de Armas](Cat%C3%A1logo%20de%20Armas.md).

## Desarmado

Todo personagem possui uma arma natural, o **Desarmado**: socos, chutes, cotoveladas e o próprio corpo.

| Campo | Valor |
|---|---|
| **Dano** | +0 |
| **Tipo de Dano** | Contusão |
| **Alcance** | 1 |
| **Carga** | 0 |

O Desarmado é de Origem **Natural** e Material **Orgânico**: está **sempre disponível**, não precisa ser equipado e não ocupa as mãos. Além disso, não pode ser removido, vendido ou perdido. Quando o personagem ataca sem nenhuma arma em mãos, ele usa o Desarmado.

Por padrão, o dano do Desarmado é **superficial** (ver [Gravidade do Dano](../Personagens/Vida.md#gravidade-do-dano)). Como seu Dano é +0, um empate em um Confronto desarmado não causa dano. Capacidades podem modificar essas características quando seu efeito disser expressamente.

## Propriedades

As **Propriedades** de uma arma são organizadas em cinco categorias. Toda arma tem exatamente uma **Origem** e um **Material**; as propriedades de **Empunhadura**, **Uso** e **Maestria** são opcionais e podem ser combinadas conforme a entrada da arma.

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

- **Leve** — arma ágil e equilibrada. Não tem efeito próprio; algumas Capacidades exigem armas Leves, como [Ambidestro](../Compet%C3%AAncias/Ambidestro.md).
- **Duas mãos** — arma que exige ser empunhada com as duas mãos para ser utilizada.
- **Flexível** — arma que pode ser usada com uma mão ou com as duas. Empunhada com as duas mãos, recebe **+1 de Dano**.
- **Acoplada** — arma presa ao corpo ou à armadura, que não ocupa a mão e não pode ser alvo da Manobra [Desarmar](../Cenas%20e%20Conflitos/A%C3%A7%C3%B5es/Manobras.md#desarmar). Ela só ataca quando a mão em que está acoplada não segura nada. Cada mão tem no máximo uma arma Acoplada.

### Uso (opcional)

- **Pesado** — Ataques realizados com esta arma utilizam **Força no lugar de Agilidade**, mantendo a Perícia determinada pela forma do Ataque. Uma arma Pesada corpo a corpo utiliza **Força + Lutar**; uma arma Pesada de disparo utiliza **Força + Atirar**. Essa substituição é obrigatória, não acrescenta dados nem Dano. Pesado modifica somente Ataques: não altera as Reservas de Manobras realizadas com a arma. Uma Capacidade que estabeleça expressamente o Atributo do Ataque sempre prevalece sobre Pesado.

- **Arremesso (valor)** — arma que pode ser lançada como um Ataque à distância. A Propriedade acompanha sempre um valor, que indica o **Alcance de arremesso** da arma, medido em quadrados — por exemplo, **Arremesso (6)** indica que a arma pode ser lançada a até 6 quadrados. Ataques de arremesso utilizam **Força + Arremessar**, salvo substituição explícita. O campo **Alcance** da arma continua valendo para seu uso corpo a corpo. Em um [Confronto](../Cenas%20e%20Conflitos/A%C3%A7%C3%B5es/Confrontar.md), a arma pode ser utilizada para **Aceitar o Confronto** contra um atacante à distância, desde que ele esteja dentro do Alcance de arremesso.

- **Versátil (tipo de dano)** — arma que tem um segundo Tipo de Dano, indicado na Propriedade. O atacante escolhe qual usar a cada Ataque. Por exemplo, uma arma Perfurante com **Versátil (Corte)**.
- **Não letal** — o dano da arma é sempre **superficial** (ver [Gravidade do Dano](../Personagens/Vida.md#gravidade-do-dano)). Para causar dano agravado com ela, o atacante sofre **-2 dados** no Ataque.
- **Manobra (Reposicionar, Derrubar ou Desarmar)** — a arma pode ser usada para realizar a [Manobra](../Cenas%20e%20Conflitos/A%C3%A7%C3%B5es/Manobras.md) indicada até o **Alcance** da arma, em vez de exigir contato físico. A Manobra não recebe bônus da arma e conserva sua Reserva própria; inclusive, a propriedade Pesado não altera essa Reserva.
- **Munição (tipo)** — arma de disparo que lança a munição indicada, como **Munição (flechas)** (ver [Catálogo de Itens](Cat%C3%A1logo%20de%20Itens.md)). Cada disparo gasta **1 munição**, seja ao iniciar um Confronto, seja ao Aceitar o Confronto; sem munição, a arma não dispara. Sacar a munição faz parte do Ataque. No Ataque, vale o **Material da munição**, não o da arma. Ao fim da Cena, se houver tempo para procurar, o personagem recupera **metade da munição gasta**, arredondada para baixo.
- **Recarga** — a arma dispara no máximo **uma vez por Rodada**.
- **Investida** — se o personagem se moveu pelo menos **3 quadrados em linha reta** até o alvo neste Turno, logo antes do Ataque, o Ataque recebe **+1 de Dano**.
- **Guarda** — enquanto empunha a arma, o personagem recebe **+1 dado** ao [Esquivar](../Cenas%20e%20Conflitos/A%C3%A7%C3%B5es/Confrontar.md#esquivar). Duas armas com Guarda não somam.

### Maestria (opcional, no máximo uma por arma)

A **Maestria** é um efeito característico do modelo da arma, que só se revela nas mãos de quem a domina. Ela pertence à arma, mas só pode ser utilizada por um personagem que **domine** aquela arma (ver [Domínio de arma](#dom%C3%ADnio-de-arma)). Quem não a domina usa a arma normalmente, sem a Maestria.

Cada arma possui no máximo **uma Maestria**. Uma Maestria pode criar efeitos ao vencer um Ataque, modificar uma interação específica ou representar uma vantagem que não cabe nas categorias estruturais anteriores.

Técnicas aprendidas pelo personagem continuam pertencendo às **Capacidades**. A Maestria descreve o que a arma faz nas mãos de quem a domina; uma Capacidade descreve o que o personagem sabe fazer.

Uma Maestria que diga **ao vencer um Ataque** não é ativada em caso de empate. Quando o efeito exige abrir mão de uma parte do dano, o atacante decide depois de vencer e antes de calculá-lo.

- **Letal** — ao vencer um Ataque, cada par de dados que mostrem **10** na rolagem do atacante soma o **Dano da arma** mais uma vez ao dano causado.
- **Varredura** — ao vencer um Ataque corpo a corpo, o atacante pode abrir mão da Margem. O alvo original sofre somente o Dano da arma, e um segundo alvo à escolha do atacante sofre o mesmo Dano como dano superficial. O segundo alvo precisa estar ao alcance da arma e adjacente ao alvo original; ele não realiza outra rolagem para responder.
- **Debilitante (Abalado)** — ao vencer um Ataque, o atacante pode abrir mão do Dano da arma. O alvo sofre somente a Margem e fica [Abalado](../Condi%C3%A7%C3%B5es/Abalado.md).
- **Debilitante (Lento)** — ao vencer um Ataque, o atacante pode abrir mão do Dano da arma. O alvo sofre somente a Margem e fica [Lento](../Condi%C3%A7%C3%B5es/Lento.md).
- **Embalo** — ao vencer um Ataque, o próximo Ataque do atacante contra o mesmo alvo, até o fim do seu próximo Turno, recebe **+1 dado**. Os bônus de Embalo não se acumulam.
- **Raspão** — quando o alvo vence o Ataque, ele ainda sofre **metade do Dano da arma**, arredondada para cima, como dano superficial. Não vale se o atacante não obteve nenhum Sucesso.
- **Deslocar** — ao vencer um Ataque, o atacante pode mover o alvo **1 quadrado** em qualquer direção, sem outra rolagem, seguindo os limites de [Reposicionar](../Cenas%20e%20Conflitos/A%C3%A7%C3%B5es/Manobras.md#reposicionar).
- **Perfurar** — ao vencer um Ataque, a [Absorção Efetiva](../Resist%C3%AAncia%20e%20Vulnerabilidade/Resist%C3%AAncia%20e%20Vulnerabilidade.md#absor%C3%A7%C3%A3o-efetiva) do alvo é reduzida em **1**, até no mínimo 0.

Módulos e cenários podem adicionar novas propriedades, origens, materiais e armas ao catálogo do núcleo.

## Domínio de arma

Dominar uma arma é conhecê-la a ponto de extrair dela sua **Maestria**.

- Quando uma **Perícia de Ataque** (Lutar, Atirar ou Arremessar) chega a **5**, o personagem passa a dominar **uma arma específica** à sua escolha que use essa Perícia.
- Cada arma a mais custa **3 XP** (ver [Progressão](../Personagens/Progress%C3%A3o.md#custos-de-experi%C3%AAncia)) e exige **5** em uma das Perícias que a arma utiliza.
- O domínio é da **arma**, não do efeito: dominar o Machado de Batalha não concede a Maestria de outra arma com o mesmo efeito.
- Quem domina uma arma usa sua Maestria em **qualquer Ataque** feito com ela, qualquer que seja a Perícia do Ataque.
- O Ataque **Desarmado** não tem Maestria.
- Personagens do Narrador dominam as armas que o Narrador indicar.

## Tipos de Dano

O **Tipo de Dano** indica a natureza do ferimento causado — uma informação separada da **gravidade** do dano (ver [Gravidade do Dano](../Personagens/Vida.md#gravidade-do-dano)).

A lista inicial de tipos de dano é:

- **Físicos:** Corte, Contusão, Perfurante
- **Elementais:** Fogo, Gelo, Elétrica, Ácido, Veneno
- **Mágico:** Mágico

Cada fonte de dano define seu Tipo de Dano — por exemplo, uma espada causa Corte, uma maça causa Contusão e uma magia de fogo causa Fogo. Catálogos e módulos podem adicionar novos tipos de dano.

---

← [Voltar para Equipamentos](Equipamentos.md)
