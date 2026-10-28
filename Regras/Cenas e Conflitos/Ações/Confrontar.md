Um **Confronto** ocorre quando um personagem decide atacar outro personagem durante uma Cena Tática.

Ao iniciar um Confronto, o atacante monta uma **Reserva de Dados** de acordo com a forma de Ataque utilizada.

| Forma de Ataque | Reserva padrão |
| --- | --- |
| Corpo a corpo | **Agilidade + Lutar** |
| Arma de disparo | **Agilidade + Atirar** |
| Arma arremessada | **Força + Arremessar** |

A arma, uma Capacidade ou outra regra pode estabelecer um Atributo ou uma Reserva diferente. Capacidades sempre prevalecem sobre as demais substituições.

A propriedade [Pesado](../../Equipamentos/Armas.md#uso-opcional) substitui Agilidade por Força sem trocar a Perícia: uma arma Pesada corpo a corpo utiliza **Força + Lutar**, enquanto uma arma Pesada de disparo utiliza **Força + Atirar**. Ela não acrescenta Força ao dano.

## Combate com Duas Armas

Todo personagem pode usar uma arma em cada mão por padrão. Isso permite manter duas armas com tipos e propriedades diferentes à disposição, mas não concede dados, dano ou Ataques adicionais por si só.

A cada Confronto, atacando ou respondendo, o personagem escolhe qual das duas armas utiliza:

- a **arma principal** é a arma escolhida. Ela define a Reserva, o Dano, o Tipo de Dano e as Propriedades Especiais do Confronto;
- a **arma secundária** é a da outra mão. Ela não tem efeito no Confronto, a menos que uma Capacidade, como as do [Ambidestro](../../Personagens/Compet%C3%AAncias/Ambidestro.md), determine o contrário.

O [Desarmado](../../Equipamentos/Armas.md#desarmado), armas Naturais e [Escudos](../../Equipamentos/Escudos.md) não contam como arma secundária.

## Respondendo ao Confronto

Depois que o atacante declara o Confronto, o personagem alvo deve escolher como irá responder.

Ele pode:

- **Aceitar o Confronto**
- **Defender**
- **Esquivar**

A resposta escolhida determina como o teste será resolvido e quais consequências podem ocorrer.

## Aceitar o Confronto

Ao **Aceitar o Confronto**, o personagem não tenta apenas evitar o Ataque. Ele responde atacando de volta.

Os dois personagens montam suas respectivas Reservas de Dados e realizam uma rolagem oposta.

Quem obtiver mais Sucessos vence o Confronto.

Se o **atacante** vencer, ele causa dano igual a:

> **Margem de Sucessos + Dano da arma**

Se quem **aceitou** o Confronto vencer, o revide causa apenas:

> **Margem de Sucessos**, como **dano superficial**

O Dano da arma não se aplica ao revide.

A **Margem** corresponde à diferença entre a quantidade de Sucessos obtida pelos dois participantes.

Se ambos obtiverem a mesma quantidade de Sucessos, ocorre um empate e **o atacante vence**, mas causa apenas o **Dano da arma** como **dano superficial**.

Para Aceitar o Confronto, o personagem que está respondendo precisa ser capaz de atingir o atacante com a arma utilizada, respeitando a restrição das armas à distância (ver [Alcance e Respostas ao Confronto](#alcance-e-respostas-ao-confronto)).

De forma geral, confrontos entre armas corpo a corpo exigem que ambos estejam dentro do alcance um do outro, enquanto Ataques à distância só podem ser respondidos dessa forma quando o personagem também possuir uma forma válida de atingir o atacante.

## Defender

Um personagem equipado com um **Escudo** pode escolher Defender.

Nesse caso, ele realiza uma rolagem oposta ao Ataque. A Reserva de Dados utilizada é:

> **Força + Lutar**

À Reserva de Dados é adicionada a **Proteção** do [Escudo](../../Equipamentos/Escudos.md).

Se o defensor obtiver mais Sucessos que o atacante, o Ataque é bloqueado e nenhum dos participantes causa dano.

Em caso de empate, o atacante vence, mas causa apenas o **Dano da arma** como **dano superficial**.

Se o atacante obtiver mais Sucessos, ele causa dano da mesma forma que ao vencer quando o alvo Aceita o Confronto: **Margem de Sucessos + Dano da arma**.

Defender não representa um contra-ataque. Mesmo quando vence a rolagem, o personagem apenas impede que o Ataque o atinja.

## Esquivar

Um personagem pode escolher **Esquivar** para tentar evitar completamente o Ataque.

A Reserva de Dados utilizada é:

> **Agilidade + Acrobacia**

Capacidades e outras regras podem substituir essa Reserva. Descrever a Esquiva de outra forma não permite utilizar livremente outro Atributo ou Perícia.

Se o personagem obtiver mais Sucessos que o atacante, ele evita completamente o dano e pode se deslocar imediatamente até:

> **metade de sua Movimentação base**

em uma direção à sua escolha.

Esse deslocamento segue as regras normais de [Movimentação](../../Movimento/Movimenta%C3%A7%C3%A3o.md), como Terreno Difícil e Movimentação Especial, mas não ativa efeitos provocados pela movimentação, como habilidades que punem ou interferem no deslocamento de adversários.

Em caso de empate, o atacante vence, mas causa apenas o **Dano da arma** como **dano superficial**.

Se o atacante obtiver mais Sucessos, ele causa dano da mesma forma que ao vencer quando o alvo Aceita o Confronto: **Margem de Sucessos + Dano da arma**.

Um personagem que esteja impossibilitado de se mover não pode escolher Esquivar.

## Alvo sem Resposta

Quando o alvo não pode responder ao Confronto, seja por estar surpreendido, inconsciente, sem nenhuma resposta válida ou com a Reserva de Dados reduzida a menos de 1 dado, apenas o atacante rola. O resultado do alvo é considerado sempre **1 Sucesso**.

O Confronto é resolvido normalmente com esse valor, incluindo a regra de empate. Se o atacante não obtiver nenhum Sucesso, o Ataque falha e ninguém sofre dano.

## Vantagem Numérica

Quando vários personagens cercam o mesmo inimigo, a vantagem numérica abre brechas na defesa dele.

Ao **iniciar um Confronto** contra um inimigo, o atacante recebe **+1 dado** para cada aliado seu a mais que o lado inimigo naquela luta:

> **Bônus de Vantagem Numérica** = aliados adjacentes ao alvo - (o alvo + aliados do alvo adjacentes a ele)

O atacante conta a si mesmo entre os aliados adjacentes ao alvo. O bônus nunca é negativo.

| Situação | Bônus de cada atacante |
| --- | --- |
| 1 × 1 | +0 |
| 2 × 1 | +1 |
| 3 × 1 | +2 |
| 3 × 2 | +1 |
| 2 × 2 | +0 |

Para contar os lados:

- **Adjacente** inclui as diagonais. Uma criatura que ocupa mais de um quadrado é adjacente a tudo que estiver ao lado de qualquer quadrado que ocupa (ver [Tamanho](../../Personagens/Tamanho.md)).
- O **atacante** também precisa estar adjacente ao alvo.
- Personagens **derrotados** não contam para nenhum dos lados.
- **Personagens de jogadores** são sempre aliados entre si. Cada NPC pertence a um lado, que pode ser hostil, neutro ou aliado do grupo.

A Vantagem Numérica vale **apenas em Ataques corpo a corpo**. Quando o inimigo cercado ataca, os personagens que respondem (Aceitando o Confronto, Defendendo ou Esquivando) não recebem o bônus.

## Atacar Além do Alcance

O **Alcance** de uma arma indica a distância máxima, em quadrados, na qual ela atinge seus alvos sem penalidade.

Ataques à distância, incluindo [armas de arremesso](../../Equipamentos/Armas.md#propriedades), podem atingir alvos além do Alcance normal da arma. Para cada faixa de quadrados do tamanho do Alcance da arma além de seu Alcance normal, o atacante sofre **-2 dados** em sua Reserva de Dados no Ataque.

Uma arma com **Alcance 6** atinge normalmente alvos a até 6 quadrados. Um alvo entre **7 e 12 quadrados** impõe **-2 dados** ao Ataque; entre **13 e 18 quadrados**, **-4 dados**; e assim por diante.

Para armas de arremesso, utilize o **Alcance de arremesso** em vez do Alcance da arma (ver [Arremesso](../../Equipamentos/Armas.md#propriedades)).

Se a perda reduzir a Reserva de Dados a menos de 1 dado, o Ataque não pode ser realizado.

## Alcance e Respostas ao Confronto

A resposta disponível depende da posição dos personagens e do equipamento utilizado.

**Aceitar o Confronto** exige que o personagem seja capaz de atingir o atacante.

**Defender** exige um Escudo, salvo quando uma Capacidade permitir outra forma, como [Aparar](../../Personagens/Compet%C3%AAncias/Aparador.md#n%C3%ADvel-1--aparar) ou [Cobrir Aliado](../../Personagens/Compet%C3%AAncias/Guardi%C3%A3o.md#n%C3%ADvel-1--cobrir-aliado).

**Esquivar** pode ser utilizada sempre que o personagem for capaz de se mover.

Armas corpo a corpo podem iniciar Confrontos contra personagens utilizando armas à distância quando estiverem dentro do alcance necessário.

Da mesma forma, personagens utilizando armas à distância podem iniciar Confrontos contra personagens corpo a corpo, mas estes só podem Aceitar o Confronto caso possuam alcance suficiente para atingir o atacante.

**Restrição das armas à distância:** um personagem não pode Aceitar o Confronto usando uma arma à distância quando o atacante utiliza uma arma corpo a corpo, mesmo que o atacante esteja dentro do Alcance da arma. Contra Ataques à distância, ele pode Aceitar normalmente, desde que consiga atingir o atacante.

---

← [Voltar para Ação](../A%C3%A7%C3%A3o.md)
