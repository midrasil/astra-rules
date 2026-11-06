# Guia de Criaturas · 04 · Bestiário

**Questões:** nova (fichas das criaturas do núcleo no novo modelo)
**Status:** concluída (PR #81, mergeado em 2026-11-06)

## O pedido

Pegar as 25 criaturas do compêndio do Astra, montá-las no novo modelo (Ficha de NPC, Capacidades de NPC e Criação de NPCs) e publicar as fichas nas regras, para que entrem na wiki.

## O que existe hoje

- **Compêndio:** `module/content/core-creatures.json` no astra-engine tem as 25 criaturas: 16 animais e 9 humanoides e monstros. Os números são os mesmos do rascunho `Design/Criaturas/Criaturas em Análise.md`, menos a Pancada do Verme Gigante, que lá ainda tem Dano 8.
- **Regras:** nenhuma ficha de criatura está em `Regras/`. A wiki só mostra as regras de criação.

## Análise

### 1. O teste do orçamento

Montei cada criatura no orçamento da parte 03. O patamar de cada uma é o mais alto entre as quatro medidas (Atributos, Perícias, Pontos de Capacidade e Absorção natural), porque o patamar é um teto.

O teste mostrou um problema: **a soma de Atributos foi calibrada para personagens e não serve para animais grandes**. Um leão tem Força 5, Vigor 3 e Determinação 4, e soma 18. Pela tabela atual, isso o põe em Lendário, junto com o Dragão. O mesmo acontece com o Urso, o Tubarão Branco, o Minotauro, o Verme e o Draco. Os cavalos ficam em Veterano só pela Força 5.

Proponho um ajuste pequeno na Criação de NPCs: **cada categoria de Tamanho acima de Médio soma +2 à soma e +1 ao máximo de Atributos do patamar**. Uma criatura grande é forte e resistente sem ser mais perigosa por isso, e o resto do orçamento (Perícias, Capacidades, Absorção) continua igual.

Com esse ajuste, os patamares ficam assim:

| Criatura | Atributos (soma; máx.) | Ajustado pelo Tamanho | Perícias (soma; máx.) | Pontos de Capacidade | Absorção natural | Patamar | O que decide |
|---|---|---|---|---:|---:|---|---|
| Cão/Lobo | 12; 3 | 12; 3 | 9; 4 | 1 | 0 | **Par** | Perícias |
| Lobo Atroz | 13; 3 | 13; 3 | 10; 3 | 1 | 0 | **Par** | Atributos, Perícias |
| Leão | 18; 5 | 16; 4 | 9; 3 | 3 | 0 | **Veterano** | Atributos, Capacidades |
| Urso Grande | 18; 5 | 16; 4 | 9; 3 | 1 | 0 | **Veterano** | Atributos |
| Touro | 17; 5 | 15; 4 | 4; 2 | 1 | 0 | **Par** | Atributos |
| Cavalo de Guerra | 15; 5 | 13; 4 | 7; 3 | 0 | 0 | **Par** | Atributos |
| Cavalo de Montaria | 15; 5 | 13; 4 | 6; 3 | 0 | 0 | **Par** | Atributos |
| Mula | 11; 3 | 11; 3 | 2; 1 | 0 | 0 | **Capanga** | Atributos, Perícias, Capacidades, Absorção |
| Gato Pequeno | 13; 4 | 13; 4 | 11; 4 | 0 | 0 | **Par** | Atributos, Perícias |
| Jacaré/Crocodilo | 13; 4 | 13; 4 | 9; 3 | 1 | 2 | **Par** | Atributos, Perícias, Absorção |
| Serpente Constritora | 10; 3 | 10; 3 | 9; 4 | 1 | 0 | **Par** | Perícias |
| Serpente Venenosa | 9; 3 | 9; 3 | 11; 5 | 1 | 0 | **Veterano** | Perícias |
| Tubarão Branco | 18; 5 | 16; 4 | 16; 5 | 0 | 0 | **Veterano** | Atributos, Perícias |
| Tubarão Devorador de Homens | 12; 3 | 12; 3 | 15; 5 | 0 | 0 | **Veterano** | Perícias |
| Aranha Gigante | 14; 4 | 14; 4 | 23; 5 | 4 | 0 | **Elite** | Perícias, Capacidades |
| Enxame | 18; 5 | 16; 4 | 6; 4 | 2 | 0 | **Veterano** | Atributos |
| Goblin | 12; 3 | 12; 3 | 16; 4 | 0 | 0 | **Par** | Perícias |
| Orc | 13; 3 | 13; 3 | 13; 3 | 0 | 0 | **Par** | Atributos, Perícias |
| Orc Líder Tribal | 17; 4 | 17; 4 | 19; 5 | 0 | 0 | **Elite** | Atributos |
| Ogro | 17; 5 | 15; 4 | 10; 3 | 1 | 0 | **Par** | Atributos, Perícias |
| Troll | 16; 5 | 14; 4 | 15; 4 | 4 | 1 | **Elite** | Capacidades |
| Minotauro | 20; 5 | 18; 4 | 17; 5 | 1 | 0 | **Lendário** | Atributos |
| Verme Gigante | 19; 5 | 13; 2 | 11; 4 | 0 | 4 | **Elite** | Absorção |
| Draco | 19; 5 | 15; 3 | 14; 5 | 3 | 4 | **Elite** | Absorção |
| Dragão | 22; 5 | 16; 2 | 17; 5 | 7 | 4 | **Lendário** | Capacidades |

### 2. Casos para o autor decidir

- **Minotauro (Lendário):** fica em Lendário só pela soma de Atributos (20, ou 18 com o ajuste), com Capacidades de Capanga. Proponho baixá-lo para **Elite**, com Determinação 2 no lugar de 3 (soma 19, ajustada 17). Sem isso, ele fica no patamar do Dragão.
- **Investida do Minotauro (+4 de Dano, 6 quadrados):** a tabela de custos só cobra Potência e Regeneração acima do padrão. Proponho cobrar **+1 por ponto de Dano acima de +2** na Investida, o que dá custo 3 ao Minotauro. Ele continua cabendo no Elite.
- **Orc Líder Tribal (Elite):** a soma 17 o põe em Elite, mas ele não tem nenhuma Capacidade. Proponho dar a ele a **Fúria**, como no exemplo da Ficha de NPC. Ela custa 1 e combina com o patamar.
- **Animais pequenos que viram Par pelas Perícias:** o Cão/Lobo e a Serpente Constritora sobem para Par só por terem uma Perícia em 4 (Perceber). Isso parece certo: são predadores atentos. Não proponho mudança.

### 3. Vontade

Pela parte 03, Elite e Lendário têm trilha de Vontade (3 + Determinação). Capanga não tem, e Par e Veterano ficam a critério do Narrador. Proponho:

- **Com trilha:** Aranha Gigante, Orc Líder Tribal, Troll, Minotauro, Verme Gigante, Draco e Dragão, pelo patamar.
- **Sem trilha:** todos os outros, porque são animais ou capangas que não precisam se esforçar como os personagens.

### 4. Onde as fichas ficam

Há dois caminhos:

- **A · Uma página por criatura**, em `Regras/Criaturas/Bestiário/`, com um índice `Bestiário.md` (nome, patamar, Tipo e Tamanho). Cada criatura tem o próprio link na wiki e pode ser citada pelas regras.
- **B · Uma página só**, `Regras/Criaturas/Bestiário.md`, com as 25 fichas em sequência.

Recomendo o **A**. A wiki e o Foundry tratam cada página como uma entrada, e 25 fichas numa página só ficam longas demais. O índice ainda permite ver todas juntas, ordenadas por patamar. Cada ficha segue o modelo da Ficha de NPC, com Reservas prontas. A pasta ganha o título em `en/folders.json` ("Bestiary").

### 5. O compêndio do Foundry

O `core-creatures.json` do astra-engine continua com os números antigos e não tem patamar nem Vontade. Atualizá-lo é trabalho no astra-engine. Proponho fazer isso depois do merge, na conversa da wiki, a partir das páginas do Bestiário.

## Revisão depois da observação do autor (2026-11-06)

O autor lembrou que essas criaturas foram feitas antes de qualquer orçamento e podem ser refeitas do zero. Isso muda a leitura do item 1: o teste não mostra que o orçamento está errado. Mostra que as fichas antigas não foram feitas para ele.

Por isso retiro o ajuste por Tamanho (P-G04.1). Sem ele, uma criatura grande e forte simplesmente fica num patamar mais alto, o que também faz sentido: é mais perigosa. Isso evita uma regra a mais.

O novo método é:

1. **Escolher o patamar pelo conceito** da criatura: quão perigosa ela deve ser para o grupo.
2. **Montar a ficha dentro dos tetos** desse patamar, usando a ficha antiga só como referência de perfil (o que é forte, o que é fraco, quais Capacidades).

Patamares propostos pelo conceito:

| Patamar | Criaturas |
|---|---|
| **Capanga** | Mula, Gato Pequeno, Cavalo de Montaria, Serpente Constritora, Serpente Venenosa, Cão/Lobo, Goblin, Orc |
| **Par** | Lobo Atroz, Cavalo de Guerra, Touro, Jacaré/Crocodilo, Tubarão Devorador de Homens |
| **Veterano** | Leão, Urso Grande, Tubarão Branco, Ogro, Enxame, Orc Líder Tribal |
| **Elite** | Aranha Gigante, Troll, Minotauro, Verme Gigante, Draco |
| **Lendário** | Dragão |

Os demais itens continuam valendo: a Investida cobra o Dano acima de +2, a Vontade segue o patamar (o Orc Líder, em Veterano, fica com a trilha a critério do Narrador, e proponho que tenha, por causa da Fúria), e as fichas vão para `Regras/Criaturas/Bestiário/`, uma página por criatura.

## Fichas refeitas (2026-11-06)

O autor aprovou o método e os patamares ("concordo"). As 25 fichas abaixo foram refeitas do zero dentro dos tetos de cada patamar, e um script conferiu todos os tetos (Atributos, Perícias, Pontos de Capacidade, Absorção natural e Dano dos Ataques naturais). A Vida é 3 + Vigor, mais Corpo Robusto quando houver; a Vontade é 3 + Determinação nas criaturas com trilha.

| Criatura | Patamar | Tipo · Tamanho | For/Agi/Vig/Car/Ast/Det | Perícias | Vida · Vontade · Mov. · Absorção base | Ataques naturais | Capacidades (custo) | Equipamento e notas |
|---|---|---|---|---|---|---|---|---|
| Mula | Capanga | Besta · Médio | 3/1/3/1/1/2 | Acrobacia 1, Perceber 1 | 6 · — · 6 · 0 | Coice, Dano 1, Contusão, Pesado | — · total 0 | Genioso: quem tenta montá-la sofre -2 dados em Cavalgar. |
| Gato Pequeno | Capanga | Besta · Minúsculo | 1/3/2/1/2/3 | Acrobacia 3, Furtividade 3, Perceber 2 | 5 · — · 6 · 0 | Garras, Dano 0, Corte, Leve | Visão no Escuro (0) · total 0 | — |
| Cavalo de Montaria | Capanga | Besta · Grande | 3/3/3/1/1/1 | Acrobacia 3, Atletismo 2, Perceber 2 | 6 · — · 10 · 0 | Coice, Dano 1, Contusão, Pesado | — · total 0 | — |
| Serpente Constritora | Capanga | Besta · Médio | 3/2/2/1/1/3 | Acrobacia 1, Atletismo 2, Lutar 2, Perceber 3 | 5 · — · 4 · 0 | Mordida, Dano 0, Perfurante | Constritora (Margem 2) (1) · total 1 | Agarra com o corpo. |
| Serpente Venenosa | Capanga | Besta · Minúsculo | 1/3/2/1/2/3 | Acrobacia 3, Lutar 3, Perceber 2 | 5 · — · 4 · 0 | Mordida, Dano 0, Perfurante, Leve | Venenosa (Potência 2) (1) · total 1 | — |
| Cão/Lobo | Capanga | Besta · Pequeno | 2/3/2/1/2/2 | Acrobacia 3, Lutar 2, Perceber 3 | 5 · — · 8 · 0 | Mordida, Dano 1, Perfurante, Leve | Ir para a Garganta (Margem 3) (1) · total 1 | Agarra com a boca. |
| Goblin | Capanga | Humanoide · Pequeno | 1/3/2/2/2/2 | Acrobacia 2, Arremessar 2, Furtividade 3, Lutar 1 | 5 · — · 5 · 0 | — | Visão no Escuro (0) · total 0 | Lança Curta |
| Orc | Capanga | Humanoide · Médio | 3/2/3/1/1/2 | Acrobacia 1, Arremessar 1, Intimidar 2, Lutar 3, Perceber 1 | 6 · — · 6 · 0 | — | Visão no Escuro (0) · total 0 | Cimitarra, Armadura de Couro |
| Lobo Atroz | Par | Besta · Médio | 3/3/3/1/2/3 | Acrobacia 3, Atletismo 2, Furtividade 2, Intimidar 3, Lutar 3, Perceber 4 | 6 · — · 10 · 0 | Mordida, Dano 2, Perfurante | Ir para a Garganta (Margem 3) (1) · total 1 | Agarra com a boca. |
| Cavalo de Guerra | Par | Besta · Grande | 4/2/4/1/2/2 | Acrobacia 2, Atletismo 2, Lutar 3, Perceber 2 | 7 · — · 8 · 0 | Coice, Dano 2, Contusão, Pesado | Investida (+2 de Dano; 4 quadrados) (1) · total 1 | — |
| Touro | Par | Besta · Grande | 4/2/4/1/1/3 | Acrobacia 1, Atletismo 2, Lutar 2, Perceber 2 | 7 · — · 7 · 0 | Chifres, Dano 3, Perfurante, Pesado | Investida (+2 de Dano; 4 quadrados) (1) · total 1 | — |
| Jacaré/Crocodilo | Par | Besta · Médio | 4/2/4/1/1/3 | Acrobacia 1, Atletismo 3, Furtividade 3, Lutar 3, Perceber 2 | 7 · — · 3 · 2 | Mordida, Dano 2, Perfurante, Pesado | Aquática (5) (0), Constritora (Margem 2) (1) · total 1 | Agarra com a boca. Absorção base 2 (escamas). |
| Tubarão Devorador de Homens | Par | Besta · Médio | 3/3/3/1/2/3 | Acrobacia 3, Atletismo 4, Lutar 3, Perceber 4 | 6 · — · 0 · 0 | Mordida, Dano 2, Perfurante | Aquática (10) (0), Frenesi (1) · total 1 | — |
| Leão | Veterano | Besta · Grande | 5/3/3/1/2/2 | Acrobacia 3, Atletismo 3, Furtividade 3, Intimidar 3, Lutar 4, Perceber 3 | 6 · — · 8 · 0 | Garras e Mordida, Dano 3, Corte | Investida (+2 de Dano; 4 quadrados) (1), Frenesi (1), Frenesi Aprimorado (1) · total 3 | — |
| Urso Grande | Veterano | Besta · Grande | 5/2/5/1/1/2 | Acrobacia 1, Atletismo 3, Intimidar 3, Lutar 4, Perceber 3 | 8 · — · 8 · 1 | Garras, Dano 3, Corte, Pesado | Constritora (Margem 2) (1), Frenesi (1) · total 2 | Agarra com as patas. Absorção base 1 (pele grossa). |
| Tubarão Branco | Veterano | Besta · Grande | 5/3/4/1/1/2 | Acrobacia 3, Atletismo 5, Lutar 4, Perceber 5 | 7 · — · 0 · 1 | Mordida, Dano 3, Perfurante, Pesado | Aquática (10) (0), Frenesi (1), Frenesi Aprimorado (1) · total 2 | Absorção base 1 (couro). |
| Ogro | Veterano | Humanoide · Grande | 5/2/4/1/1/3 | Acrobacia 1, Arremessar 2, Atletismo 3, Intimidar 3, Lutar 4, Perceber 1 | 9 · — · 7 · 0 | — | Frenesi (1), Corpo Robusto (2) (2) · total 3 | Clava Massiva, Peles Grossas |
| Enxame | Veterano | Besta · Grande | 1/4/3/1/1/5 | Acrobacia 4, Perceber 3 | 6 · — · 10 · 0 | — | Enxame (dano 4 pelo Tamanho) (2), Voadora (1) · total 3 | Imune a Corte e Perfurante. |
| Orc Líder Tribal | Veterano | Humanoide · Médio | 4/3/4/2/1/2 | Acrobacia 3, Arremessar 3, Atletismo 2, Furtividade 1, Intimidar 4, Lutar 5, Perceber 2 | 7 · 5 · 6 · 0 | — | Fúria e Sangue por Sangue (Furioso 2) (2), Visão no Escuro (0) · total 2 | Machado de Batalha, Placa Peitoral |
| Aranha Gigante | Elite | Besta · Médio | 4/4/3/1/2/3 | Acrobacia 5, Atirar 4, Furtividade 4, Intimidar 3, Lutar 4, Perceber 4 | 6 · 6 · 8 · 0 | Mordida, Dano 2, Perfurante | Escaladora (0), Teia (Potência 2; Alcance 6) (1), Venenosa (Potência 4) (3) · total 4 | — |
| Troll | Elite | Monstruosidade · Grande | 5/2/5/1/1/3 | Acrobacia 2, Arremessar 2, Atletismo 3, Intimidar 4, Lutar 4, Perceber 2 | 8 · 6 · 7 · 1 | Garras, Dano 2, Corte, Pesado | Regeneração (2; interrompida por Fogo) (2), Frenesi (1), Frenesi Aprimorado (1) · total 4 | Porrete com Espinhos; Absorção base 1 (pele). |
| Minotauro | Elite | Monstruosidade · Grande | 5/3/4/1/2/2 | Acrobacia 2, Arremessar 2, Atletismo 3, Intimidar 5, Lutar 5, Perceber 4 | 7 · 5 · 8 · 0 | Chifres, Dano 3, Perfurante, Pesado | Investida (+4 de Dano; 6 quadrados) (3), Frenesi (1) · total 4 | Lança, Armadura de Couro |
| Verme Gigante | Elite | Monstruosidade · Colossal | 5/2/5/1/2/2 | Acrobacia 1, Atletismo 2, Furtividade 4, Lutar 4, Perceber 4 | 11 · 5 · 6 · 4 | Mordida, Dano 4, Perfurante, Pesado; Pancada, Dano 5, Contusão, Alcance 2, Pesado | Escavadora (0), Emboscada Subterrânea (1), Corpo Robusto (3) (3) · total 4 | Absorção base 4 (escamas). |
| Draco | Elite | Dragão · Enorme | 5/2/5/1/2/2 | Acrobacia 2, Atletismo 2, Intimidar 5, Lutar 4, Perceber 3 | 8 · 5 · 6 · 4 | Garras e Mordida, Dano 4, Corte, Pesado | Sopro (Dano 4; Fogo) (2), Aterrorizante (Potência 2) (1) · total 3 | Absorção base 4 (escamas). |
| Dragão | Lendário | Dragão · Colossal | 7/3/8/3/4/4 | Acrobacia 3, Atletismo 3, Erudição 3, Intimidar 5, Lutar 5, Mentir 3, Perceber 5 | 11 · 7 · 8 · 5 | Garras e Mordida, Dano 5, Corte, Pesado | Voadora (24) (1), Sopro (Dano 5; Fogo) (2), Aterrorizante (Potência 3) (2), Frenesi (1), Frenesi Aprimorado (1) · total 7 | Absorção base 5 (escamas). |

Escolhas que vale conferir:

- **Cavalo de Montaria em Capanga:** com Força 3, ele é fraco em combate, o que combina com um animal de carga e transporte. O Cavalo de Guerra é o que luta.
- **Orc Líder Tribal:** ganhou Fúria e Sangue por Sangue (Furioso 2, custo 2) e trilha de Vontade.
- **Minotauro:** Investida (+4 de Dano; 6 quadrados) custa 3, pela regra nova de +1 por ponto de Dano acima de +2.
- **Verme Gigante:** a Mordida tem Dano 4 e a Pancada, Dano 5 e Alcance 2. Ganhou Emboscada Subterrânea e Corpo Robusto (3).
- **Sopro:** a tabela de custos não diz quanto Dano o Sopro pode ter. Usei o mesmo teto dos Ataques naturais (Draco 4, Dragão 5), no lugar do 8 antigo. Proponho escrever isso na Criação de NPCs.
- **Açoite de Cauda:** saiu do Draco e do Dragão. No livro era uma área, e o núcleo não tem uma Capacidade para isso. Pode voltar como Capacidade de NPC nova, se o autor quiser.
- **Dragão:** sendo Lendário, tem Atributos acima de 5 (Força 7, Vigor 8), o que dá Vida 11. Ainda assim, ele deve vir acompanhado, como diz a régua de encontros.
- **Enxame:** ganhou Voadora (um enxame de insetos).
- **Página:** segui a recomendação de uma página por criatura, porque a pergunta ficou sem resposta.

## Propostas

### P-G04.1 · Ajuste por Tamanho

Retirada depois da observação do autor. No lugar dela: escolher o patamar pelo conceito e refazer cada ficha dentro dos tetos.

### P-G04.2 · Ajustes nas criaturas

- Minotauro em Elite (Determinação 2).
- Investida: +1 de custo por ponto de Dano acima de +2.
- Orc Líder Tribal com Fúria.
- Pancada do Verme Gigante com Dano 5 (já decidido na D-085).

### P-G04.3 · Vontade

Trilha de Vontade só para as criaturas Elite e Lendário, como no item 3.

### P-G04.4 · Bestiário

Pasta `Regras/Criaturas/Bestiário/` com o índice e uma página por criatura, nas duas línguas.

### P-G04.5 · Compêndio

Atualizar o `core-creatures.json` depois do merge, na conversa da wiki.

## Perguntas ao autor

1. Concorda com o ajuste por Tamanho?
2. O Minotauro desce para Elite, ou prefere mantê-lo como Lendário?
3. Prefere uma página por criatura, ou uma página só?

## Decisões do autor (2026-11-06)

- **Método e patamares:** aprovados ("concordo"); o ajuste por Tamanho saiu.
- **Fichas refeitas:** aprovadas, com duas correções do autor:
  - **Sopro** é uma Zona e não segue a referência dos Ataques naturais. O Dano do Sopro volta a ser definido na ficha (Draco e Dragão com Dano 8), e a Criação de NPCs passa a dizer isso.
  - **Açoite de Cauda:** o autor lembrou que as Capacidades não precisam definir todos os ataques. A Ficha de NPC passa a dizer que a ficha pode definir ataques próprios da criatura, e o Açoite volta ao Draco (Rajada 3, Dano 2 de Contusão) e ao Dragão (Rajada 4, Dano 3 de Contusão), sem custo de Capacidade.
- **Investida:** +1 de custo por ponto de Dano acima de +2, escrito na Criação de NPCs.
- **Páginas:** uma por criatura em `Regras/Criaturas/Bestiário/`, com o índice `Bestiário.md` em ordem de patamar.
- **Imagens de Zonas:** o pedido do autor foi para uma conversa própria.

## Revisão posterior (2026-11-06)

- O autor tornou a trilha de Vontade padrão em todos os NPCs, porque várias Capacidades usam Vontade (D-087). A Vontade opcional desta parte foi substituída.
