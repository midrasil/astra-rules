Rascunho de trabalho. Lista as habilidades de criaturas do livro de monstros que serviu de referência, resumidas e já pensadas com as regras do Astra, para decidirmos uma a uma como entram como **Características de NPC**: Trunfos que, por padrão, só NPCs usam.

> [!success] Compatibilidade revisada
> As Características foram conferidas para as Reservas vinculadas. Testes expressos com dois Atributos foram mantidos; Teia e Emboscada Subterrânea receberam fórmulas completas.

Este documento registra as decisões usadas nas Características oficiais e na conversão das criaturas atuais.

Legenda do status: ⬜ não analisado · 🟨 em discussão · ✅ decidido · ❌ descartado · ⏸️ adiado

## Decisões gerais

- Planejar só com o que o Astra tem; o que não existe vira regra nova simples ou fica de fora.
- **Movimento especial:** a criatura que tem um tipo de movimento especial pode, no seu turno, usar a sua Movimentação com o movimento normal ou com o especial.
- **Efeitos ao acertar:** podemos criar efeitos (Condições) novos.
- **Sentidos:** só Visão no Escuro, com regras simples de iluminação.
- **Ataques especiais:** cada um precisa de tratamento próprio.

## Grupo 1 — Movimentos especiais ✅

No Astra, nadar e escalar são [Movimentação Especial](../Movimento/Movimenta%C3%A7%C3%A3o.md#movimenta%C3%A7%C3%A3o-especial) e custam 2 pontos de Movimentação por quadrado. O [Voo](../Movimento/Movimenta%C3%A7%C3%A3o.md#voo) não segue essa regra: quem concede o Voo define como ele funciona.

Pela decisão geral, a característica deixa a criatura usar a sua Movimentação com aquele movimento **pelo custo normal**, 1 ponto por quadrado.

| Característica | Proposta |
|---|---|
| **Aquática** | Nada pelo custo normal e respira debaixo d'água. |
| **Voadora** | Voa pelo custo normal e ignora Terreno Difícil no chão, porque passa por cima dele. Ao ficar Caída ou Agarrada no ar, cai. |
| **Escavadora** | Cava e se move por dentro da terra pelo custo normal. Enquanto está enterrada, não pode ser alvo de Ataques. |
| **Escaladora** | Escala paredes e tetos pelo custo normal, sem precisar de teste. |

- O ataque surpresa da Escavadora (sair do chão com bônus) foi para o Grupo 6, como ataque especial.

## Grupo 2 — Efeitos ao acertar ✅

Molde comum: **ao vencer um Ataque com o ataque natural da criatura**, o alvo faz um teste para resistir. A **Potência** da característica, entre parênteses, é a **Dificuldade** do teste. Cada característica diz a duração: nem todas duram pela Potência, para que as Condições mais fortes não fiquem fortes demais. Ex.: **Venenosa (2)**: Dificuldade 2, e o Envenenado dura 2 turnos.

Cada característica define a **Reserva do teste** de resistência, então habilidades diferentes são resistidas de formas diferentes.

| Característica | Reserva para resistir | Efeito ao falhar | Duração | Condição nova |
|---|---|---|---|---|
| **Venenosa** | Vigor + Determinação | -2 dados em rolagens com Atributo Físico. | Potência, em turnos | Envenenado |
| **Paralisante** | Vigor + Força | Sem Ação e sem Movimentação; quem o ataca usa a regra de alvo sem resposta. | 1 turno | Paralisado |
| **Atordoante** | Determinação + Astúcia | Sem Ação, mas ainda pode se mover. | 1 turno | Atordoado |
| **Infecciosa** | definida na criatura | Doença ou maldição descrita na criatura ou no cenário (ex.: licantropia). | definida na criatura | — |

- **Imunidade depois do efeito:** quando Paralisado ou Atordoado terminam, o personagem fica **imune àquele mesmo efeito por 1 turno**, para não ficar preso nele de forma contínua.

## Grupo 3 — Resistência ❌

Fica de fora: usamos o que o sistema já tem, como Absorção, Resistências, Vulnerabilidades e Imunidades por Tipo de Dano e por Material, e o Tipo de Criatura.

- Confirmado: no Astra, o dano superficial transborda para agravado quando a trilha de Vida enche.

## Grupo 4 — Sentidos e iluminação ✅

Regra simples de iluminação, nova no vault:

| Iluminação | Penalidade em rolagens que dependem de enxergar |
|---|---|
| **Claro** | nenhuma |
| **Penumbra** | -2 dados |
| **Escuro** | -4 dados |
| **Breu** | -6 dados |

- **Visão no Escuro:** ignora as penalidades de Penumbra e Escuro, mas não as de Breu.
- Infravisão: descartada, por decisão geral.
- O Narrador define a iluminação da área. Por enquanto, a penalidade entra como modificador na Reserva; ler a luz da cena do Foundry fica para depois.

## Grupo 5 — Tamanho no ataque ✅

O Astra já tem o campo [Tamanho](Tamanho.md). Proposta: atacar um alvo muito maior é mais fácil e atacar um alvo muito menor é mais difícil.

Conta a diferença de categorias entre atacante e alvo (Minúsculo, Pequeno, Médio, Grande, Enorme, Colossal):

- Alvo **2 categorias maior**: **+2 dados** no Ataque (ex.: Médio contra Enorme).
- Alvo **3 ou mais categorias maior**: **+4 dados** (ex.: Médio contra Colossal).
- Alvo **2 ou mais categorias menor**: **-2 dados** (ex.: Médio contra Minúsculo).
- Uma categoria de diferença não muda nada.
- Vale nos dois sentidos, e o sistema pode aplicar sozinho pela Reserva, como o flanco.
- Gigantesca: fica de fora; esmagar com bônus pelo Tamanho, se for preciso, entra como ataque especial.

## Grupo 6 — Ataques especiais ✅

Cada um com tratamento próprio:

| Característica | Proposta |
|---|---|
| **Frenesi** | Uma vez por turno, ao vencer um Ataque, pode fazer outro Ataque contra outro alvo adjacente, com -2 dados. No **Aprimorado**, sem a penalidade. |
| **Sopro** (fogo, gelo, ácido…) | Ação: cria uma [Zona](../Cenas%20e%20Conflitos/Zonas.md) instantânea em cone de 3 quadrados, com Dano e Tipo definidos na criatura. Não pode ser usado em turnos seguidos. |
| **Investida** (Bote, Espetar, Carga) | Ao se mover pelo menos 4 quadros em linha reta antes de atacar, soma +2 ao Dano do Ataque. |
| **Ir para a Garganta** | Ao vencer com Margem 3 ou mais, o dano ignora a Absorção da armadura do alvo. |
| **Constritora** (Constrição, Abraço, Rolar) | Ao vencer com Margem 2 ou mais, o alvo também fica Agarrado. No começo de cada turno da criatura, o alvo Agarrado por ela sofre o Dano do ataque natural. |
| **Aterrorizante (Potência)** (Medo) | Quem vê a criatura pela primeira vez na cena testa Determinação + Astúcia contra a Potência; se falhar, recebe acúmulos da Condição **Medo**. Uma vez por cena para cada personagem. |
| **Teia (Potência)** | Ataque à distância com Agilidade + Atirar que, ao vencer, deixa o alvo Agarrado pela teia. A ficha pode estabelecer expressamente outro Atributo de Ataque. Para se soltar, o alvo usa a Ação num teste de Força + Atletismo contra a Potência. |
| **Emboscada Subterrânea** (da Escavadora) | Ao sair da terra para atacar, testa Agilidade + Furtividade contra Astúcia + Perceber do alvo; se vencer, recebe +2 dados no Ataque. |

## Fora desta leva

Ficam de fora, por serem de cenário ou dependerem de regras que o Astra não tem: feitiços e magias, erguer mortos, cria de vampiro, enfeitiçar, mudança de forma, névoa, convocar animais, cartas de ação (Focado, Rápida) e a escala de Força em dados.

## Condição nova: Medo

- **Medo** é acumulável. Cada acúmulo impõe **-1 dado** em todas as Reservas do personagem.
- No **fim de cada turno do personagem afetado**, ele perde 1 acúmulo.
- A quantidade de acúmulos da Aterrorizante, como todos os valores das características, é configurável em cada criatura; o padrão é igual à Potência.
- Texto final em [Características de NPC](Trunfos/Caracter%C3%ADsticas%20de%20NPC.md).
