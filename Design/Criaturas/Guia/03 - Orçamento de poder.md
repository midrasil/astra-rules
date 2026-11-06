# Guia de Criaturas · 03 · Orçamento de poder

**Questões:** nova (orçamento de criação de NPCs); fecha o que ficou pendente na parte 02 (Capacidades de Nível alto em NPCs)
**Status:** concluída (PR #79, mergeado em 2026-11-06)

## O que o orçamento precisa responder

Duas perguntas, nesta ordem:

1. **Esse NPC é páreo para o grupo?** O Narrador precisa saber, antes da cena, se um inimigo é um capanga, um igual ou uma ameaça para o grupo inteiro.
2. **Uma Capacidade forte não sai barata?** Na parte 02 ficou combinado que o NPC não pode chegar ao Recusar a Queda sem pagar o caminho que o personagem paga.

Como no [Critério de Equilíbrio de Equipamentos](../../Equipamentos/Crit%C3%A9rio%20de%20Equil%C3%ADbrio%20de%20Equipamentos.md), o objetivo não é que todo NPC do mesmo patamar tenha o mesmo poder. O objetivo é que o Narrador tenha uma referência e que nada saia de graça.

## O que existe hoje

- **Personagem inicial:** Atributos com soma 15 e máximo 4; Perícias com soma de 16 a 21, conforme o perfil, e máximo 4; 2 Níveis de Competência; Vida de 4 a 7.
- **Progressão:** Atributo custa novo nível × 5 XP, Perícia novo nível × 3 XP, Competência novo Nível Total × 3 XP. O ritmo sugerido é 2 XP por sessão.
- **NPCs:** a ficha (parte 02) e as Capacidades soltas (parte 01) existem, mas nada diz quanto um NPC pode ter.
- **Rascunho de conversão:** as criaturas convertidas em `Design/Criaturas/Criaturas em Análise.md` servem de teste para os números abaixo.

## Análise

### 1. Dois modelos

- **A · XP equivalente.** Cada parte da ficha tem um preço em XP, pelas regras de Progressão, e o NPC "vale" o XP total. É exato e usa uma moeda que já existe. Mas somar o custo de uma ficha inteira é trabalhoso, e várias coisas não têm preço em XP: Capacidades de NPC, Atributos acima de 5, Absorção natural.
- **B · Patamares com tetos.** Uma tabela diz, para cada patamar, a soma e o máximo de Atributos e Perícias, quantos pontos de Capacidade o NPC tem e qual o Nível mais alto que ele pode ter. É o modelo do D&D 5e (níveis de desafio) e do critério de equipamentos (base mais orçamento).

Recomendo o **B**, com cada patamar ancorado no XP de um personagem. O Narrador monta um NPC em poucos minutos, e a âncora diz a que personagem ele equivale.

### 2. Patamares

| Patamar | Equivale a | Atributos (soma; máximo) | Perícias (soma; máximo) | Pontos de Capacidade (Nível máximo) | Absorção natural máxima |
|---|---|---|---|---|---:|
| **Capanga** | abaixo de um personagem inicial | 12; 3 | 8; 3 | 1 (Nível 1) | 1 |
| **Par** | personagem inicial | 15; 4 | 18; 4 | 2 (Nível 2) | 2 |
| **Veterano** | personagem com cerca de 30 XP (15 sessões) | 16; 5 | 22; 5 | 3 (Nível 3) | 3 |
| **Elite** | personagem com cerca de 85 XP (40 sessões) | 17; 5 | 26; 5 | 5 (Nível 4) | 4 |
| **Lendário** | além dos personagens | 19 ou mais; acima de 5 para criaturas que não são humanas | 30; 5 | 8 (Nível 5) | 5 |

As âncoras de XP são o custo mínimo de passar de Par ao patamar (por exemplo, Veterano: um Atributo de 1 para 2, quatro Perícias de 0 para 1 e um terceiro Nível de Competência: 10 + 12 + 9 = 31 XP).

Os números são uma primeira proposta, para ajustar com os testes do item 4.

### 3. Pontos de Capacidade

Um só orçamento para as Capacidades de Competências e as Capacidades de NPC:

- **Capacidades de Competências:** uma Competência custa o **Nível mais alto** que o NPC tem dela. As Capacidades abaixo desse Nível podem entrar sem custo a mais. Assim:
  - Fúria e Recusar a Queda custam **5**, o mesmo que o personagem paga em Níveis para chegar lá;
  - um guarda "Sentinela 2" custa **2**, como na equivalência da parte 01;
  - Corpo Robusto (N) custa **N**, porque é o Robusto no Nível N.
- **Teto:** o NPC não pode ter Capacidade de Nível acima do máximo do patamar. Um capanga com Recusar a Queda fica impossível.
- **Capacidades de NPC:** custam pela tabela do item 4.

### 4. Custo das Capacidades de NPC

Proponho separar o que descreve a criatura do que a deixa mais forte em combate:

| Custo | Capacidades |
|---:|---|
| **0** | Aquática, Escavadora, Escaladora, Visão no Escuro, Infecciosa |
| **1** | Voadora, Frenesi, Frenesi Aprimorado, Investida, Ir para a Garganta, Constritora, Teia, Emboscada Subterrânea, Venenosa, Paralisante, Atordoante, Aterrorizante |
| **2** | Sopro, Enxame, Regeneração (2) |

- **Valores acima do padrão:** cada ponto de Potência acima de 2, ou de Regeneração acima de 2, custa **+1**.
- **Custo 0:** movimento e sentidos dizem o que a criatura é. A Infecciosa age fora do combate e é narrativa.
- **Voadora** custa 1, porque um inimigo no ar muda o combate para quem só luta corpo a corpo.

Testes com o rascunho:

| Criatura | Capacidades | Custo | Patamar |
|---|---|---:|---|
| Lobo | Ir para a Garganta | 1 | Capanga |
| Troll | Regeneração (2), Frenesi, Frenesi Aprimorado | 4 | Elite |
| Aranha Gigante | Escaladora, Teia, Venenosa (Potência 4) | 4 | Elite |
| Dragão | Aterrorizante (Potência 3), Frenesi, Frenesi Aprimorado, Voadora, Sopro | 7 | Lendário |

### 5. Ataques naturais

O Dano segue o [Critério de Equilíbrio](../../Equipamentos/Crit%C3%A9rio%20de%20Equil%C3%ADbrio%20de%20Equipamentos.md) das armas, para que uma garra não bata mais que uma espada sem motivo:

- **Base:** 2, como uma arma de uma mão; 1 para um Ataque natural Leve, como a mordida de um animal Pequeno.
- **Tamanho:** +1 por categoria acima de Médio (Grande 3, Enorme 4, Colossal 5).
- **Livre:** Pesado, como nas armas.

O rascunho tem casos acima disso, como a Pancada do Verme Gigante (Dano 8). Pelo critério, ela teria Dano 5. Se o autor quiser manter golpes maiores, eles passam a custar pontos de Capacidade.

### 6. Vida e Vontade

- **Vida:** já sai do orçamento. Vigor está nos Atributos, e Corpo Robusto (N) custa N pontos de Capacidade.
- **Vontade:** Capanga sem trilha; Par e Veterano a critério do Narrador; Elite e Lendário com trilha. A ideia é que uma ameaça séria se esforce como os personagens.

### 7. Inimigo sozinho contra o grupo

Um Lendário sozinho contra quatro personagens age uma vez por Rodada, e eles agem quatro. É o problema conhecido de "chefe solitário". Há dois caminhos:

- **Sem regra nova:** o guia recomenda que um Lendário venha com Capangas ou Pares, ou que o Narrador use dois NPCs.
- **Regra de chefe:** um Lendário ganha um Turno a mais por Rodada, ou uma Ação extra. Isso resolve o problema, mas é uma mecânica nova.

Recomendo **sem regra nova** por enquanto. Se o teste em mesa mostrar que chefes caem rápido demais, a regra de chefe pode entrar depois.

### 8. Montar um encontro

Uma régua curta para o Narrador, sem fórmula:

- **1 Par** é um adversário à altura de **1 personagem**;
- **2 Capangas** valem **1 Par**;
- **1 Veterano** vale cerca de **2 Pares**;
- **1 Elite** vale cerca de **3 Pares**;
- **1 Lendário** é um desafio para o **grupo inteiro**.

### 9. Onde fica

O critério de equipamentos ficou em `Design/`, porque serve a quem cria itens para o núcleo. O orçamento de NPCs serve ao Narrador durante a campanha, então proponho uma página de regras: `Regras/Criaturas/Criação de NPCs.md`, com a versão em `en/`.

## Propostas

### P-G03.1 · Patamares

A tabela do item 2, com os números como primeira proposta.

### P-G03.2 · Pontos de Capacidade

Um só orçamento; Competência custa o Nível mais alto; teto de Nível por patamar; Capacidades de NPC pela tabela do item 4.

### P-G03.3 · Ataques naturais, Vida e Vontade

Dano pelo critério das armas mais o Tamanho; Vida e Vontade como no item 6.

### P-G03.4 · Encontros e chefes

A régua do item 8, sem regra nova de chefe.

### P-G03.5 · Página Criação de NPCs

Criar `Regras/Criaturas/Criação de NPCs.md` (e em `en/`) com os itens 2 a 8, e a página na área Criaturas.

## Perguntas ao autor

1. Os cinco patamares e os números da tabela fazem sentido como ponto de partida?
2. Concorda com o custo das Capacidades de NPC, em especial com movimento e sentidos de graça?
3. Prefere deixar o chefe sem regra nova, ou quer uma regra de chefe agora?
4. O Dano 8 da Pancada do Verme deve cair para 5, ou golpes maiores passam a custar pontos?

## Decisões do autor (2026-11-06)

- "Concordo com suas propostas": P-G03.1 a P-G03.5 aprovadas, com as recomendações das perguntas: os números da tabela como ponto de partida; os custos das Capacidades de NPC, com movimento e sentidos de graça; chefe sem regra nova; e o Dano dos Ataques naturais limitado pela referência, então a Pancada do Verme passou de 8 para 5 no rascunho de conversão.
- A página ficou em `Regras/Criaturas/Criação de NPCs.md`, e a Ficha de NPC remete a ela em Progressão.

## Revisão posterior (2026-11-06)

- O autor tornou a trilha de Vontade padrão em todos os NPCs, porque várias Capacidades usam Vontade (D-087). A Vontade opcional desta parte foi substituída.
