# Guia de Criaturas · 02 · Ficha de NPC

**Questões:** Q-014 (ficha de criatura)
**Status:** concluída (PR #78, mergeado em 2026-11-06)

## O ponto de partida

Na parte 01 ficou decidido que a ficha de NPC é a **ficha de jogador simplificada**, e que o campo de Competências vira uma lista de **Capacidades soltas**. Esta parte define o resto da ficha: o que fica, o que sai, como se calculam Vida, Vontade e Absorção base, e como se escrevem os Ataques naturais.

O orçamento de poder (quanto de cada coisa uma criatura de certo patamar pode ter) fica para a parte 03. Aqui só entram as regras da ficha.

## O que existe hoje

- **Fórmulas:** o Narrador usa as dos personagens (Vida 3 + Vigor, Vontade 3 + Determinação, Iniciativa Astúcia + Determinação). Nenhuma regra diz que isso vale para NPCs.
- **Atributos:** criaturas que não são humanas podem passar de 5 (D-056). Humanos ficam de 1 a 5, como os personagens.
- **Ataque natural:** já definido em Características de NPC (Dano, Tipo de Dano e Alcance na ficha; Agilidade + Lutar). A Origem **Natural** das armas já diz que ele não ocupa as mãos e não pode ser Desarmado.
- **Absorção base:** existe nas regras de Armaduras, mas nada diz de onde ela vem. O rascunho de conversão já trata "pele e escamas" como Absorção base.
- **Vida extra:** a Capacidade Corpo Robusto (N) já soma N espaços de Vida e, pela parte 01, pode ser dada solta a um NPC.
- **Rascunho de conversão:** as fichas convertidas em `Design/Criaturas/Criaturas em Análise.md` já usam quase todos os campos abaixo, mas não têm Vontade.

## Análise

### 1. Onde fica

Uma página nova, `Regras/Criaturas/Ficha de NPC.md`, com os campos, as regras de cálculo e dois exemplos. Ela entra na página da área Criaturas, antes de Tipos de Criatura, porque as outras páginas da área são consultadas a partir dela.

Prefiro o nome **Ficha de NPC** a "Ficha de Criatura" porque ela vale também para NPCs humanos, como um guarda ou um rival.

### 2. Campos

| Ficha de jogador | Ficha de NPC |
|---|---|
| Nome, Conceito | **fica** (o Conceito em uma linha) |
| Tipo de Criatura, Tamanho | **fica** |
| Ambição, Desejo, Convicções e Pilares | **sai** |
| Atributos | **fica** (criaturas podem passar de 5) |
| Perícias | **fica**, listando só as que não são 0 |
| Vida, Vontade, Iniciativa | **fica** (Vontade opcional, item 4) |
| Movimentação | **fica** (padrão 6; a ficha pode dar outro valor) |
| Carga máxima | **sai** (o Narrador escolhe um equipamento coerente) |
| Absorção, Resistências, Vulnerabilidades e Imunidades | **fica** |
| Armas, armaduras e itens | **fica** |
| Competências e Pontos de Competência | **sai**: vira **Capacidades soltas** |
| XP e Progressão | **sai** (item 8) |
| — | **novo:** Características de NPC e Ataques naturais |
| — | **novo, opcional:** Reservas prontas (item 7) |

A Carga é o único corte que pode parecer arbitrário. A razão é que ela só serve para o jogador não carregar tudo; o Narrador já escolhe o que o NPC leva. Se um NPC carregar algo pesado demais para a cena, o Narrador aplica a Sobrecarga como faria com qualquer personagem.

### 3. Vida

Proponho **manter 3 + Vigor** e não criar fórmula nova. Há dois meios já existentes de ter mais Vida:

- **Vigor acima de 5**, para criaturas que não são humanas (D-056). Isso também deixa a criatura mais difícil de envenenar ou paralisar, o que combina com uma criatura grande e resistente.
- **Corpo Robusto (N)**, que soma N espaços. Serve para quem aguenta muito sem ser mais resistente a venenos e efeitos, e serve para humanos.

Um Dragão com Vigor 5 tem 8 espaços; com Corpo Robusto (5), 13. Com Vigor 7 e Corpo Robusto (5), 15.

Considerei e não recomendo:

- **Bônus de Vida por Tamanho:** é uma regra a mais, e o Tamanho já tem efeitos próprios (Ataque, Limite de Tamanho).
- **Vida livre**, escolhida pelo Narrador: quebra a ligação com o Vigor e as regras de substituição de Atributo nas fórmulas.

Quanto disso cada patamar pode ter fica para o orçamento da parte 03.

### 4. Vontade

Proponho que a **trilha de Vontade seja opcional** no NPC:

- **Com trilha:** 3 + Determinação, com todas as regras da Vontade: Rerrolar Dados, Ignorar Penalidades Físicas, Romper Limite e Capacidades que custam Vontade. Serve para líderes, rivais e criaturas inteligentes, que devem se esforçar como os personagens.
- **Sem trilha:** a ficha escreve "Vontade: —". O NPC não usa Vontade de nenhuma forma, e dano de Vontade não o afeta.

A razão é de jogo: um NPC comum que rerrola dados a cada teste alonga o combate e acrescenta anotações sem mudar muito a cena. A regra "sem trilha não usa Capacidades que custem Vontade" já foi aprovada na parte 01, então este item só a completa.

Duas regras da Vontade dependem de coisas que o NPC não tem:

- **Recuperação:** o dano superficial sai no Descanso Prolongado, como nos personagens. O agravado, que nos personagens sai por Ambição e Convicções, sai **quando o Narrador decidir**, porque o NPC não tem esses campos.
- **Trilha toda agravada:** a consequência é a da regra geral, definida pelo Narrador. Para NPCs, a mais comum é **fugir ou se render**, e vale citar isso como exemplo.

A alternativa é dar trilha a todos os NPCs. É mais simples de escrever, mas obriga o Narrador a anotar a Vontade de cada lobo e de cada guarda.

### 5. Absorção base

- **Padrão:** 0, como nos personagens.
- **Proteção natural:** pele grossa, escamas ou carapaça dão **Absorção base** na ficha, com o valor escolhido pelo Narrador.
- **Armadura:** soma como nos personagens. A ficha escreve o total e de onde vem, como "Absorção 3 (base 0, Placa Peitoral 3)".

Nada muda nas regras: elas já dizem que a Absorção base não penaliza Esquivar, não é ignorada pelo Ir para a Garganta e não se aplica a Zonas. Isso diferencia escamas de armadura sem regra nova.

### 6. Ataques naturais

A definição já existe. Faltam três detalhes:

- **Material:** o Desarmado é **Orgânico**; proponho o mesmo para os Ataques naturais, salvo indicação da ficha (um Constructo de ferro tem punhos de Metal). Isso importa para Resistências por Material.
- **Gravidade:** o Desarmado causa dano **superficial**, mas o Ataque natural segue a regra geral e causa dano **agravado**. Vale escrever isso, porque os dois são Origem Natural e a confusão é fácil.
- **Agarrar sem mãos:** desde a D-077, Agarrar pede uma mão livre. Lobos, serpentes e cães não têm mãos. Proponho: **a ficha pode indicar uma parte do corpo que conta como mão livre para Agarrar**, como a boca ou a cauda. Sem essa indicação, uma criatura sem mãos não Agarra (a Constritora continua sendo o meio de agarrar ao acertar).

Os demais detalhes já estão nas regras: Pesado troca Agilidade por Força, e a ficha escreve as Propriedades do Ataque natural como as de uma arma.

### 7. Reservas prontas

As fichas convertidas já trazem uma coluna "Reservas" com os dados somados (Mordida 5; Esquiva/Zona 6). Proponho manter isso como **campo opcional**: a ficha pode listar as Reservas mais usadas já somadas, para o Narrador não calcular durante a cena. A regra continua sendo Atributo + Perícia; a linha é só uma anotação, e modificadores da cena se aplicam por cima.

### 8. Progressão

NPCs **não ganham XP**. Um NPC que volta mais forte recebe uma ficha nova ou ajustada pelo Narrador, dentro do orçamento da parte 03.

### 9. Características de NPC são Capacidades

Observação do autor (2026-11-06): as Características de NPC não são outra coisa. São **Capacidades a que os jogadores não têm acesso**. A parte 01 manteve o nome separado por recomendação minha, e isso dá a impressão de duas mecânicas diferentes, quando a única diferença é quem pode ter.

Proposta:

- **Nome:** "Características de NPC" passa a ser **Capacidades de NPC**, e cada uma passa a ser chamada de Capacidade.
- **Lugar:** a página sai de `Regras/Criaturas/` e vai para `Regras/Capacidades/Capacidades de NPC.md`, ao lado do índice.
- **Índice:** a seção "Características de NPC" de `Capacidades.md` vira "Capacidades de NPC", com a coluna de acesso "só NPCs".
- **Regras gerais:** as regras de valores configuráveis (Potência, Reserva para resistir) continuam na página, porque valem para essas Capacidades. A definição de Ataque natural vai para a Ficha de NPC, porque é um campo da ficha e não uma Capacidade.
- **Links:** cerca de dez páginas em português citam a página antiga (Condições, Iluminação, Caçador, Movimentação, Criaturas, Capacidades), mais as versões em `en/`. O Caçador pergunta "Qual é uma de suas Características?" e passa a perguntar "Qual é uma de suas Capacidades?".
- **Wiki:** a troca de caminho precisa chegar ao astra-engine, que lê `Regras/`.

## Propostas

### P-G02.1 · Página Ficha de NPC

Criar `Regras/Criaturas/Ficha de NPC.md` (e a versão em `en/`) com:

- a introdução: a ficha de NPC é a de jogador simplificada;
- a lista de campos do item 2, com o que sai;
- as regras dos itens 3 a 8;
- um modelo da ficha em bloco;
- dois exemplos: um **Lobo** (criatura sem trilha de Vontade, que Agarra com a boca) e um **Orc Líder Tribal** (com armadura, trilha de Vontade e uma Capacidade solta).

E acrescentar a página à área Criaturas.

### P-G02.2 · Vida e Vontade

- Vida: 3 + Vigor; mais Vida por Vigor acima de 5 ou por Corpo Robusto (N). Sem bônus por Tamanho.
- Vontade: trilha opcional (item 4), com recuperação do agravado a critério do Narrador e "fugir ou se render" como exemplo de consequência.

### P-G02.3 · Absorção base e Ataques naturais

- Absorção base: 0 por padrão, ou o valor da proteção natural.
- Ataques naturais: Material Orgânico salvo indicação, dano agravado, e a parte do corpo que conta como mão livre para Agarrar. Esta última frase entra também em Características de NPC, junto da definição de Ataque natural.

### P-G02.4 · Reservas prontas e Progressão

- Reservas prontas como campo opcional.
- NPCs sem XP.

### P-G02.5 · Capacidades de NPC

Renomear as Características de NPC para Capacidades de NPC e mover a página para `Regras/Capacidades/`, como no item 9.

## Perguntas ao autor

1. A trilha de Vontade opcional (item 4) faz sentido, ou prefere que todo NPC tenha a trilha?
2. Concorda em tirar a Carga máxima da ficha de NPC?
3. A regra de Agarrar com uma parte do corpo (item 6) é necessária, ou prefere deixar Agarrar só para quem tem mãos e para a Constritora?

## Decisões do autor (2026-11-06)

- **Vigor e Corpo Robusto:** o autor perguntou a diferença. Vigor alto deixa a criatura resistente em tudo (testes contra efeitos no corpo, recuperação); Corpo Robusto só soma Vida e serve também para humanos, que param em Vigor 5.
- **NPC sem Vontade:** o autor perguntou como ficam as Capacidades que custam Vontade. Resposta: o NPC não as usa, então o Narrador não as coloca na ficha; quem precisa delas tem trilha. Não entra regra de uso gratuito por Cena.
- **Lista separada para NPCs:** o autor perguntou se seria melhor uma lista de Capacidades só para NPCs, citando o Recusar a Queda do Furioso. Fica a lista única: o problema é o NPC pular o custo de chegar a uma Capacidade de Nível alto, e isso entra no orçamento da parte 03 (custo pelo Nível e teto por patamar).
- **Características de NPC são Capacidades** (observação do autor): viram **Capacidades de NPC**, em `Regras/Capacidades/Capacidades de NPC.md`; o índice diz que só NPCs têm acesso a elas, em uma frase no lugar da coluna. A definição de Ataque natural foi para a Ficha de NPC.
- **Agarrar com a boca:** aprovado.
- **P-G02.1 a P-G02.5:** aprovadas ("aprovo tudo"). A Agarrado já dizia que criaturas sem mãos agarram com a parte do corpo indicada na ficha, então a Condição não mudou.
