# Guia de Criaturas · 01 · Lista única de Capacidades

**Questões:** Q-015 (lista única de Capacidades); prepara a Q-014 (ficha de criatura)
**Status:** em análise

## Plano do guia

O guia de criação de criaturas segue o mesmo fluxo da revisão: uma análise por parte, a decisão do autor e um PR.

| Parte | Assunto | Questão |
|---|---|---|
| **01** | Lista única de Capacidades: como Competências e NPCs usam as mesmas Capacidades | Q-015 |
| **02** | Ficha de criatura: Atributos, Perícias, Vida, Vontade, Absorção base e Ataques naturais | Q-014 |
| **03** | Criação de criaturas: orçamento de poder por patamar, como o critério de equipamentos | nova |

## O que já está decidido em princípio (Q-015)

- As Competências continuam existindo para os jogadores. Elas não viram talentos comprados um a um.
- Capacidades que escalam com o Nível da Competência passam a ter um valor configurável, como "Nada Escapa (N)": na Competência, N é o Nível; no NPC, é o valor escolhido.
- As Características de NPC atuais entram na mesma lista.

## O que existe hoje

- **Competências:** 14 Competências com 51 Capacidades nomeadas. Sete delas escalam com o Nível: Acrobata, Assassino, Caçador, Duelista, Mentalista, Robusto e a coluna do Atirador. Duas evoluem uma Capacidade anterior (Atirador e Guardião), e várias citam outras Capacidades da mesma Competência pelo nome. Quatro têm requisitos comuns no topo da página: Ambidestro (duas armas), Guardião (escudo), Sentinela (arma corpo a corpo) e Caçador (Perícias usadas). Onze Capacidades custam Vontade.
- **Características de NPC:** 20 características em uma página própria, já com valores configuráveis entre parênteses (Potência, Margem, alcance).
- **NPCs:** a ficha não diz como um NPC recebe uma Capacidade de Competência. Na prática, o Narrador daria Níveis de Competência ao NPC.

## Análise

### 1. Onde fica a lista

Há dois caminhos:

- **A · Índice único.** Uma nova página `Regras/Capacidades/Capacidades.md` lista todas as Capacidades em uma tabela, com origem (Competência e Nível, ou NPC), valor N quando houver, requisito e link para o texto. O texto continua onde está hoje: nas páginas das Competências e na de Características de NPC.
- **B · Um arquivo por Capacidade.** Cada Capacidade ganha o próprio arquivo em `Regras/Capacidades/`, e as Competências passam a ser só a tabela de Progressão com links.

Recomendo o **A**. Ele cumpre o objetivo da Q-015, que é ter uma lista única usável por NPCs, sem mexer nas 14 Competências, que acabaram de ser revisadas. Ele também não duplica texto e mantém o formato do Fundamento (uma seção por Nível). O B é a forma "pura" da ideia, mas reescreve a estrutura de todas as Competências e muda a navegação da wiki. Pode ficar para depois, se o Foundry pedir um item por Capacidade.

### 2. Valor configurável (N)

Hoje o texto diz, por exemplo, "igual ao seu Nível de Mentalista". Há duas formas de chegar ao "Nada Escapa (N)":

- **Reescrever** cada Capacidade com N.
- **Uma regra geral:** "Quando um NPC tem uma Capacidade que usa o Nível da sua Competência, a ficha dá o valor desse Nível entre parênteses, de 1 a 5."

Recomendo a **regra geral**. O texto das Competências não muda, e o índice mostra a Capacidade com "(N)". O teto de 5 é o mesmo dos personagens; criaturas fortes crescem por outros meios (Atributos acima de 5, D-056).

### 3. Dependências entre Capacidades

Um NPC que recebe uma Capacidade solta pode não ter o que ela pressupõe. Proponho três regras curtas:

- **Requisitos da Competência:** os requisitos comuns no topo da página (escudo, duas armas, arma corpo a corpo) valem também para o NPC. O índice repete o requisito na linha da Capacidade.
- **Capacidades que evoluem outra**, como a Postura de Tiro Aprimorada: o NPC precisa ter também a Capacidade evoluída.
- **Capacidades que citam outra pelo nome**, como o Golpe do Caçador, que usa a presa Lida do Conhecer a Presa: só funcionam se o NPC tiver a outra. O índice indica a dependência.

### 4. Custos de Vontade

Onze Capacidades custam Vontade. Um NPC precisa de uma trilha de Vontade para usá-las. Isso entra na parte 02 (ficha de criatura). Aqui, proponho só a regra: **um NPC sem trilha de Vontade não pode usar Capacidades que custem Vontade**. Assim, o Narrador decide na ficha se a criatura é capaz desse esforço.

### 5. Características de NPC na mesma lista

As 20 características entram no índice com a origem "NPC". Proponho manter o nome **Características de NPC** para elas, e não chamá-las de Capacidades. Elas continuam fora do alcance dos jogadores, e o nome deixa isso claro. O índice lista as duas famílias em tabelas separadas na mesma página.

### 6. Jogadores e Capacidades soltas

A lista única não abre a compra de Capacidades soltas para jogadores. Isso já está decidido em princípio e vale escrever no topo do índice: **personagens recebem Capacidades só pelos Níveis das Competências**.

## Propostas

### P-G01.1 · Índice único (caminho A)

Criar `Regras/Capacidades/Capacidades.md` (e a versão em `en/`) com:

- uma introdução: o que é a lista, que personagens recebem Capacidades só por Competências e que NPCs recebem soltas;
- a seção **Uso por NPCs**, com as regras dos itens 2, 3 e 4;
- a tabela **Capacidades de Competências**: Capacidade, Competência e Nível, valor (N), requisito ou dependência e link;
- a tabela **Características de NPC**: nome, valores padrão e link.

### P-G01.2 · Área nova no Readme

Acrescentar **Capacidades** às áreas do Readme. Pela ordem de dependência da D-081, ela entra entre Competências e Criaturas.

### P-G01.3 · Links de volta

Acrescentar, nas páginas de Competências e de Características de NPC, uma linha que remeta ao índice. Nenhum texto de Capacidade muda.
