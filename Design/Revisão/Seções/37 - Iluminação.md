# 37 · Iluminação

**Arquivo:** `Regras/Cenas e Conflitos/Iluminação.md` (e `en/`)
**Relacionadas:** Características de NPC (Visão no Escuro), Confrontar (respostas), Perícias (Perceber, Furtividade)
**Status:** decidida (D-063) e aplicada; aguardando o merge do PR

## O que está estabelecido

- A Iluminação afeta as rolagens que dependem de enxergar (atacar, perceber, procurar). O Narrador define a de cada área.
- Claro: nenhuma penalidade. Penumbra: -2 dados. Escuro: -4. Breu: -6.
- Visão no Escuro ignora Penumbra e Escuro até o alcance; o Breu a bloqueia.

## Análise

### Mecânica

1. **A regra é boa e leve.** Uma tabela, um modificador por nível, e a Visão no Escuro como única exceção. Não proponho mudar os valores.
2. **Os níveis não são descritos, e o Breu só é explicado em outra página (lacuna).** A página não diz o que é Penumbra, Escuro ou Breu. Só a Visão no Escuro, em Características de NPC, diz que o Breu é "a escuridão mágica". Sem isso, uma caverna sem nenhuma luz pode ser lida como Breu, e aí a Visão no Escuro não funcionaria justamente onde deveria. Proponho descrever cada nível com exemplos, deixando claro que o Breu é escuridão sobrenatural e que uma caverna sem luz é Escuro.
3. **Não está claro qual iluminação conta (lacuna).** Se o atacante está no escuro e o alvo está num lugar iluminado, quem sofre a penalidade? A forma mais simples, e a que faz sentido para "enxergar", é usar a iluminação de onde está o que se tenta ver: o alvo, a criatura ou o objeto. Assim, quem está no escuro ataca normalmente quem está na luz, e quem está na luz tem dificuldade de responder a quem está no escuro.
4. **As respostas ao Confronto (observação ligada ao item 3).** Aceitar, Defender e Esquivar dependem de ver o Ataque. Proponho dizer que elas também sofrem a penalidade, usando a iluminação do atacante. Assim, se os dois estão no escuro, os dois perdem os mesmos dados e nada muda no equilíbrio; se só o atacante está no escuro, ele tem a vantagem, que é o que se espera de uma emboscada.
5. **Fontes de luz não são definidas (observação).** Não há regra para o alcance de uma tocha ou lanterna. Isso cabe ao Narrador por enquanto e pode entrar como item de equipamento depois; não proponho aqui.

### Texto e estrutura

6. A página é curta e clara. Só mudaria o que as propostas pedem.

## Propostas

### P-37.1 · Descrição dos níveis (lacuna)

A tabela ganha uma coluna "Exemplos":

| Iluminação | Penalidade | Exemplos |
|---|---|---|
| **Claro** | nenhuma | luz do dia, um ambiente bem iluminado |
| **Penumbra** | -2 dados | crepúsculo, luar, a borda da luz de uma tocha, neblina leve |
| **Escuro** | -4 dados | noite sem lua, uma caverna ou um porão sem nenhuma luz |
| **Breu** | -6 dados | escuridão sobrenatural ou mágica |

E a frase do Breu passa a dizer: "O Breu é uma escuridão sobrenatural: nem a Visão no Escuro enxerga através dele."

### P-37.2 · Qual iluminação conta (lacuna)

Depois da tabela: "A penalidade usa a iluminação do lugar onde está o que se tenta ver: o alvo de um Ataque, a criatura que se tenta perceber ou o objeto que se procura. Responder a um [Confronto](A%C3%A7%C3%B5es/Confrontar.md) também depende de ver, e usa a iluminação de onde está o atacante."

- **Alternativa:** deixar ao Narrador, como hoje.

## Pedido do autor (2026-11-03)

"Siga um modelo parecido com o D&D 5e." As propostas P-37.1 e P-37.2 acima ficam substituídas pela P-37.3.

### Como o 5e trata a luz (resumo)

- Três níveis: luz plena, penumbra e escuridão.
- Penumbra deixa a área "levemente obscurecida": só atrapalha a percepção pela visão.
- Escuridão deixa a área "fortemente obscurecida": quem está ali não pode ser visto. Atacar quem não se vê é mais difícil, e quem não é visto ataca com vantagem. Se os dois estão no escuro, os efeitos se anulam.
- Visão no escuro sobe um nível dentro do alcance: penumbra conta como luz plena e escuridão como penumbra.
- Escuridão mágica é escuridão que nem a visão no escuro atravessa; não é um nível a mais.
- Fontes de luz têm um raio de luz plena e outro igual de penumbra (tocha: 20 pés + 20 pés).

### P-37.3 · Iluminação no modelo do 5e (mudança de regra)

Adaptação ao Astra, mantendo os valores que a página já usa (-2 e -4):

| Iluminação | Efeito | Exemplos |
|---|---|---|
| **Claro** | nenhum | luz do dia, ambiente bem iluminado |
| **Penumbra** | -2 dados em testes de Perceber que dependem da visão; Ataques não são afetados | crepúsculo, luar, a borda da luz de uma tocha, neblina leve |
| **Escuro** | quem está no Escuro não pode ser visto: -4 dados em toda rolagem que dependa de ver essa criatura ou objeto, inclusive Ataques, respostas a um Confronto e Perceber | noite sem lua, caverna ou porão sem luz |

- **Qual iluminação conta:** a do lugar onde está o que se tenta ver. Quem está no Escuro ataca sem penalidade quem está na luz, e quem está na luz perde 4 dados para responder. Se os dois estão no Escuro, os dois perdem 4 dados e nada muda no equilíbrio, como no 5e.
- **Visão no Escuro:** até o alcance, a Penumbra conta como Claro e o Escuro como Penumbra. Hoje ela ignora as duas penalidades; no 5e, quem tem visão no escuro ainda enxerga mal no escuro total.
- **Breu deixa de ser um nível:** passa a ser "escuridão sobrenatural", que conta como Escuro e que nem a Visão no Escuro atravessa. A penalidade de -6 sai.
- **Fontes de luz** (nova tabela): cada uma ilumina como Claro até o seu raio e como Penumbra por mais o mesmo raio.

| Fonte | Claro | Penumbra além disso |
|---|---|---|
| Vela | 1 quadrado | +1 quadrado |
| Tocha | 4 quadrados | +4 quadrados |
| Lampião | 6 quadrados | +6 quadrados |

**Arquivos:** `Iluminação.md`, a Visão no Escuro em `Características de NPC.md` e as versões em `en/`.

**O que muda em relação a hoje:**
- a Penumbra deixa de afetar Ataques;
- o Escuro afeta as respostas, e não só o atacante;
- a Visão no Escuro fica um pouco mais fraca no Escuro total;
- o -6 do Breu sai.

**Alternativa:** manter os quatro níveis atuais e aplicar só as partes do 5e que faltam (qual iluminação conta, Visão no Escuro subindo um nível e fontes de luz).

## Decisões do autor (2026-11-03)

- **P-37.3:** aprovada (D-063). P-37.1 e P-37.2 ficam absorvidas por ela.
