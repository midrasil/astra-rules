# 05 · Vida

**Arquivo:** `Regras/Personagens/Vida.md` (e a versão em `en/`)
**Status:** em discussão

## O que está estabelecido

- **Trilha.** Tem **3 + Vigor** espaços (4 a 8). Vigor pode ser substituído por Capacidades, e isso afeta só o tamanho da trilha.
- **Gravidades.** O dano pode ser superficial (/) ou agravado (X). O Tipo de Dano é uma informação separada. **Por padrão, todo dano é agravado.** O desarmado é superficial. Armaduras e Resistências convertem agravado em superficial.
- **Trilha cheia.**
  - Com a trilha cheia, o personagem fica **Debilitado** (-2 dados em rolagens Físicas).
  - O dano que excede a trilha converte espaços superficiais em agravados.
  - Com a trilha toda agravada, o personagem fica **incapacitado**, "potencialmente fatal", e a sobrevivência fica a critério do Narrador.
- **Recuperação.**
  - O dano superficial se recupera em Vigor pontos por Descanso Prolongado.
  - O dano agravado só se recupera com **tratamento**: uma cena com Astúcia + Curar em que cada Sucesso converte 1 ponto em superficial, uma vez por dia.
  - **Hospitalizado**, o personagem converte 1 por dia sem rolagem.

### Referência: ritmo de dano

Um Ataque causa Margem + Dano da arma. A Margem fica tipicamente entre 1 e 2, e o Dano da arma vai de 1 a 4. Isso dá 3 a 5 por acerto. Com Vigor 2 ou 3 (5 a 6 espaços), o personagem fica Debilitado em cerca de 2 acertos e incapacitado em cerca de 3, dependendo da Absorção. O combate é letal e rápido, o que é coerente com a proposta Storyteller. Não proponho mudar esses números.

## Análise

1. **"Incapacitado" não tem regra (lacuna objetiva).** É o estado mais importante de um combate, e o texto só diz que o personagem "deixa de conseguir continuar normalmente". Mesmo assim, Guardião e Furioso dependem dele, e Confrontar fala em alvo "inconsciente". Ficam sem resposta:
   - se o personagem incapacitado pode agir ou se mover;
   - se ele responde a Ataques;
   - se cai no chão;
   - o que acontece se ele sofrer mais dano;
   - como ele volta a agir.
2. **O excesso de dano não diz a proporção (lacuna pequena).** "O dano adicional começa a converter espaços superficiais em agravados", mas quantos por ponto? Presumo 1 por ponto, mas o texto não diz.
3. **Texto repetido e fora de lugar.** A regra principal ("por padrão todo dano é agravado; desarmado é superficial") está no meio da seção Dano Agravado. A conversão por armadura e Resistência aparece três vezes. O desarmado aparece duas vezes, com redações diferentes ("quando a fonte ou o Narrador determinar" e "por padrão").
4. **Ordem na trilha (lacuna pequena).** "Da esquerda para a direita" não diz onde fica o agravado e onde fica o superficial. Isso importa quando o superficial se cura e o agravado fica.
5. **Hospital contra tratamento.** As duas regras convivem sem relação. Hospitalizado converte 1 por dia, e o tratamento converte em média 2 com 4 dados. O hospital é pior do que uma rolagem, e o texto não diz se os dois se somam.

## Propostas

### P-05.1 · Definir Incapacitado (lacuna objetiva; decisão do autor sobre letalidade)

Criar **Incapacitado** como Condição, em `Regras/Condições/`, com link a partir de Vida:

> Um personagem **Incapacitado** está [Caído](...), não pode realizar Ações, Movimentação nem responder a Confrontos (é um [alvo sem resposta](...)). A Condição termina quando ao menos 1 ponto de dano agravado de Vida é convertido em superficial.

**Questão para o autor: o que acontece com mais dano?**

- **(a) Narrativo, como hoje.** A morte fica a critério do Narrador. É o mais próximo do texto atual.
- **(b) Morte por excesso.** Dano agravado sofrido enquanto Incapacitado mata. É simples e letal.
- **(c) Agonia.** Sem tratamento até o fim da Cena, o personagem morre. Isso dá urgência sem rolagem nova.

Recomendo a **(a)** com a definição mecânica acima. Se o autor quiser mais letalidade, a **(c)**.

### P-05.2 · Excesso de dano e ordem na trilha (lacuna pequena)

> Com a trilha cheia, **cada ponto** de dano adicional converte **1 espaço** de dano superficial em agravado. Mantenha o dano agravado à esquerda da trilha e o superficial à direita.

### P-05.3 · Reorganizar o texto (sem mudar regras)

- **Gravidade do Dano** passa a abrir com a regra: "por padrão todo dano é agravado; o desarmado e as fontes indicadas causam dano superficial".
- As seções Superficial e Agravado só descrevem o que cada gravidade representa e como se marca.
- A conversão por armaduras e Resistências fica em uma frase só, com link.

### P-05.4 · Unir hospital e tratamento (simplificação)

> Em **instalações adequadas**, como um hospital, o tratamento diário converte pelo menos 1 ponto, mesmo sem Sucessos.

- **Consequência:** fica uma regra só, e o hospital passa a ser um piso, não uma alternativa pior.
