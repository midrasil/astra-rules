# 00 · Introdução

**Arquivo:** `Readme.md` (e `en/Readme.md`)
**Status:** em discussão

## O que está estabelecido

O Readme é a página inicial do vault e da wiki. Ele tem quatro partes:

1. **Apresentação.** O Astra é um sistema genérico e modular. Ele se inspira principalmente no Storyteller (reservas de dados e foco em personagens, conflitos e consequências) e também em SWADE, Pathfinder e D&D (modularidade, personalização e combate tático). A ideia é um "núcleo + módulos", como em software open source. O Foundry é a implementação principal, mas as regras servem para mesa presencial.
2. **Comece por aqui.** Ordem de leitura: Mecânica Básica, Personagens, Criação de Personagem, Cenas e Conflitos.
3. **Regras do sistema.** As nove áreas, com uma linha de descrição cada.
4. **Criação de personagem.** As cinco etapas, com uma linha cada.

Não há regra mecânica nesta seção. A revisão aqui é textual e estrutural.

## Análise

### Escrita

- O texto é claro e curto. A apresentação cumpre o papel de dizer o que o Astra é e de onde vem.
- **Terminologia.** O texto diz "pools de dados", mas o termo oficial do sistema é **Reserva de Dados**. Também diz "customização", enquanto o índice de Personagens usa "personalização".
- "Especialmente suas edições mais recentes" é vago, mas é contexto de identidade e não atrapalha.

### Estrutura

- **Termos básicos nunca definidos.** "Narrador" aparece em 16 páginas, e "personagem de jogador" e "NPC" em várias outras. Nenhuma página diz quem é o Narrador, o que fazem os jogadores ou o que é um NPC. Para quem já joga RPG isso é óbvio, mas o Readme é a porta de entrada.
- **Lista de Criação duplicada.** A parte "Criação de personagem" repete o índice de `0 - Criação de Personagem.md`. As duas descrições já começaram a divergir: "array fixo de Atributos e perfis de Perícias" no Readme e "Atributos (array fixo) e Perícias (perfis)" no índice. Cada mudança na Criação exige atualizar três lugares (Readme, índice e as versões em inglês).
- **Ordem de leitura.** Criação vem antes de Cenas e Conflitos, mas ela pede Competências e Equipamentos, que não estão no caminho sugerido. Como a própria Criação tem links para essas páginas, considero aceitável.
- **Divergência com a wiki.** A ordem das áreas no Readme não é a mesma da árvore da wiki (veja Q-001).

## Propostas

### P-00.1 · Corrigir terminologia (problema objetivo, pequeno)

Trocar "pools de dados" por "Reservas de Dados" e "customização" por "personalização".

- **Por quê:** o termo oficial deve aparecer já na primeira página.
- **Consequência:** nenhuma mecânica. O texto em inglês também muda.

### P-00.2 · Definir os papéis à mesa (lacuna objetiva)

Acrescentar uma seção curta, por exemplo "Como se joga", com 3 a 5 frases:

- um **Narrador** conduz o jogo, descreve o mundo e interpreta os **NPCs**;
- os **jogadores** controlam os **personagens de jogadores**;
- quando o resultado de uma ação é incerto, ela é resolvida com um teste de d10 (link para Mecânica Básica).

Alternativas:

- (a) colocar essa definição no índice de Mecânica Básica, e não no Readme;
- (b) manter como está, assumindo que o leitor já conhece RPG.

**Recomendo o Readme**, porque o termo aparece logo nas primeiras regras e a explicação custa poucas linhas.

### P-00.3 · Remover a lista duplicada de Criação (redundância)

Substituir a lista "Criação de personagem" por uma única linha com link para a visão geral. Ou então tirar a seção, já que "Comece por aqui" já leva até lá.

- **Por quê:** evita manter o mesmo conteúdo em três lugares, que já está divergindo.
- **Consequência:** o Readme fica mais curto. Quem quiser ver as etapas clica uma vez a mais.
- **Alternativa:** manter a lista. Nesse caso, padronizar as descrições.

### P-00.4 · Ordem das áreas: Readme × wiki (divergência, decisão do autor)

| Readme | Wiki |
| --- | --- |
| Mecânica Básica | Mecânica Básica |
| Personagens | Personagens |
| **Competências** | **Criação de Personagem** |
| Criaturas | **Cenas e Conflitos** |
| Cenas e Conflitos | **Competências** |
| Movimento | Criaturas |
| Equipamentos | Movimento |
| Resistência e Vulnerabilidade | Equipamentos |
| Condições | Resistência e Vulnerabilidade |
| | Condições |

Minha leitura é que a ordem da wiki é mais didática, por dois motivos:

- Criação fica ao lado de Personagens.
- Competências vêm depois de Cenas e Conflitos, cujas Ações e Manobras as Capacidades usam.

Por outro lado, mudar a wiki envolve o gerador no astra-engine. **Recomendo adiar a decisão para a seção 53**, quando já teremos visto todas as dependências.

### P-00.5 · Reescrever a apresentação: "genérico" sim, "modular" não (levantada pelo autor)

**Pergunta do autor:** a apresentação ainda descreve o sistema? Ele é genérico, mas parece mais Savage Worlds do que modular.

**Análise:**

- **"Modular" não se sustenta.** Não há módulos, regras opcionais marcadas nem separação entre núcleo e opcional. O que existe são **ganchos para cenários**: fórmulas de Vida e Vontade, Tipos de Criatura, Tamanho e Progressão dizem que "cenários e módulos podem ajustar". Isso é um sistema genérico configurável por cenário, o mesmo modelo das *Setting Rules* do SWADE. A analogia com software open source descreve como o projeto é desenvolvido, não como se joga.
- **A semelhança com o Savage Worlds está na proposta, não na mecânica.** O que lembra o SWADE é ser genérico, tático em mapa, sem classes nem níveis e ajustável por cenário. Com a saída de Privilégios e Complicações (equivalentes a Edges e Hindrances), a semelhança mecânica diminuiu.
- **A mecânica é Storyteller (V5) quase por inteiro:** reservas de d10 com sucesso em 6+, par de 10 como crítico, Atributo + Perícia, dano superficial e agravado, rerrolar 3 dados com Vontade, Ambição e Desejo, Convicções e Pilares (equivalentes a Convictions e Touchstones).
- **A influência de D&D e Pathfinder** está em equipamentos (propriedades de armas), Tamanho, Condições e combate em quadrados.

**Proposta:** reescrever os três primeiros parágrafos para dizer o que o Astra é:

- um sistema genérico, tático, sem classes nem níveis, cujo núcleo os cenários ajustam;
- e de onde vem cada parte: Storyteller na resolução e no lado pessoal, Savage Worlds na proposta, D&D e Pathfinder nos equipamentos e no combate.

Tirar "modular" e a analogia com open source, a menos que o autor pretenda criar módulos opcionais.

**Questão para o autor:** existe intenção de módulos opcionais (por exemplo magia, veículos, horror)? Isso muda a recomendação. Ver Q-005.

**Resposta do autor (2026-11-01):** pretende criar módulos adicionais. "Modular" fica, mas descrito como estrutura de **núcleo + módulos**, sem dar a entender que os módulos já existem.

**Rascunho proposto** (substitui os três primeiros parágrafos; o parágrafo do Foundry fica como está):

> **Astra** é um sistema genérico de RPG de mesa, pensado para servir a diferentes cenários, gêneros e estilos de jogo. Os personagens são construídos livremente, sem classes nem níveis, e os conflitos podem ser resolvidos de forma narrativa ou tática, em mapa.
>
> As regras se organizam em um **núcleo**, comum a qualquer mesa, sobre o qual podem ser construídos **módulos** que acrescentam regras para necessidades específicas, como magia ou veículos. Cada cenário escolhe os módulos que usa e pode ajustar partes do núcleo, como os Tipos de Criatura e os equipamentos disponíveis, sem precisar reescrevê-lo.
>
> A resolução de ações e o lado pessoal dos personagens vêm da família **Storyteller**: Reservas de d10, dano superficial e agravado, Vontade, Ambição, Desejo e Convicções. A proposta de um sistema genérico, tático e adaptável por cenário se aproxima do **Savage Worlds**. Equipamentos, Condições e combate em quadrados se inspiram em **Pathfinder** e **Dungeons & Dragons**.

**Ponto de atenção:** no Foundry, "módulo" é o nome dos pacotes de extensão. Isso pode confundir quando um módulo de regras do Astra for distribuído como módulo do Foundry. Avaliar o termo quando o primeiro módulo existir (ver Q-005).

**Resposta do autor sobre o termo:** os módulos de regras serão distribuídos como módulos do Foundry. O termo coincide de propósito, então o ponto de atenção está resolvido.

**Ajuste do autor (2026-11-01):** o rascunho está bom, mas o sistema seguiu a direção de um **Storyteller montado no formato de Pathfinder 2e e D&D**. O terceiro parágrafo passa a refletir isso, e a menção ao Savage Worlds sai: o caráter genérico já está no primeiro parágrafo.

> No centro do Astra está a resolução da família **Storyteller**: Reservas de d10, dano superficial e agravado, Vontade, Ambição, Desejo e Convicções. Sobre ela, o jogo se organiza no formato de **Pathfinder 2e** e **Dungeons & Dragons**: Turnos com Ação e Movimentação, combate em quadrados, Condições, propriedades de armas e Competências que evoluem por Níveis.
