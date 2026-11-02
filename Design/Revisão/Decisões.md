# Decisões da Revisão

Registro das propostas aprovadas e rejeitadas. Rejeições também ficam aqui, para não serem reabertas sem argumento novo.

Formato: **D-NNN · data · seção** — decisão · status · justificativa · impacto · arquivos alterados.

---

**D-001 · 2026-11-01 · Planejamento**
- **Decisão:** adotar o plano de revisão. São 54 unidades na ordem do Readme, com Criação de Personagem logo depois de Competências. O registro fica em `Design/Revisão/`.
- **Status:** aprovada.
- **Justificativa:** registro versionado junto com as regras e fora da wiki.
- **Impacto:** nenhum nas regras.
- **Arquivos:** `Design/Revisão/`.

**D-002 · 2026-11-01 · 00 Introdução (P-00.5)**
- **Decisão:** reescrever a apresentação do Readme. O Astra é descrito como sistema genérico, sem classes nem níveis, com **núcleo + módulos**. A origem de cada parte também fica explícita: resolução **Storyteller** no formato de **Pathfinder 2e e D&D**. Savage Worlds e a analogia com software open source saem.
- **Status:** aprovada.
- **Justificativa:** o texto antigo prometia modularidade sem descrevê-la e atribuía ao SWADE influências que o sistema já não tem. O autor pretende criar módulos, distribuídos no Foundry como módulos (pacotes de extensão).
- **Impacto:** nenhum nas regras. A separação entre núcleo e módulos fica pendente (Q-005).
- **Arquivos:** `Readme.md`, `en/Readme.md`.

**D-003 · 2026-11-01 · 00 Introdução (P-00.1)**
- **Decisão:** usar os termos oficiais na apresentação. "Pools de dados" vira "Reservas de Dados" e "customização" vira "personalização". Na prática, a troca ficou absorvida pela reescrita da D-002.
- **Status:** aprovada.
- **Arquivos:** `Readme.md`, `en/Readme.md`.

**D-004 · 2026-11-01 · 00 Introdução (P-00.2)**
- **Decisão:** acrescentar a seção **Como se joga** ao Readme, definindo Narrador, jogadores, personagem de jogador e NPC, e dizendo que ações incertas são resolvidas por teste de d10.
- **Status:** aprovada.
- **Justificativa:** esses termos eram usados em várias páginas e não eram definidos em nenhuma.
- **Arquivos:** `Readme.md`, `en/Readme.md`.

**D-005 · 2026-11-01 · 00 Introdução (P-00.3)**
- **Decisão:** substituir a lista de etapas da Criação de Personagem no Readme por um único link para a visão geral.
- **Status:** aprovada.
- **Justificativa:** o conteúdo estava duplicado em três lugares e já divergia.
- **Arquivos:** `Readme.md`, `en/Readme.md`.

**D-006 · 2026-11-01 · 00 Introdução (P-00.4)**
- **Decisão:** a ordem das áreas no Readme e na wiki fica para a seção 53.
- **Status:** adiada (Q-001).

**D-007 · 2026-11-02 · 01 Mecânica Básica (P-01.1)**
- **Decisão:** penalidades nunca reduzem uma Reserva a menos de 1 dado. Saem a regra "menos de 1 dado = 1 Sucesso" e a menção correspondente em *Alvo sem Resposta*. Regras que impedem a ação nesse caso, como o Alcance em Confrontar, continuam valendo como exceção.
- **Status:** aprovada.
- **Justificativa:** com a regra antiga, ser penalizado até zerar a Reserva era melhor do que rolar 1 dado (1 Sucesso garantido contra 50% de chance).
- **Impacto:** quem só é penalizado continua rolando 1 dado. *Alvo sem Resposta* passa a valer só para quem de fato não pode responder.
- **Arquivos:** `Regras/Mecânica Básica/Reserva de Dados.md`, `Regras/Cenas e Conflitos/Ações/Confrontar.md` e as versões em `en/`.

**D-008 · 2026-11-02 · 01 Mecânica Básica (P-01.2)**
- **Decisão:** criar uma regra geral de **teste oposto**. Vence quem tiver mais Sucessos e, no empate, prevalece a situação atual. Regras específicas podem mudar o empate, como Confrontar, em que o atacante vence.
- **Status:** aprovada.
- **Justificativa:** não havia resposta para empates fora das regras específicas. O padrão escolhido é o que Manobras e Agarrado já usavam.
- **Arquivos:** `Regras/Mecânica Básica/Reserva de Dados.md` e a versão em `en/`.

**D-009 · 2026-11-02 · 01 Mecânica Básica (P-01.3)**
- **Decisão:** reorganizar a Reserva de Dados nesta ordem: dados, montagem, Sucessos, Dificuldade, testes opostos, penalidades, substituições e Ajuda. As quatro explicações do Atributo vinculado viram uma só, e o exemplo repetido sai. Nenhuma regra muda.
- **Status:** aprovada.
- **Arquivos:** `Regras/Mecânica Básica/Reserva de Dados.md` e a versão em `en/`.

**D-010 · 2026-11-02 · 01 Mecânica Básica (P-01.4)**
- **Decisão:** a exigência de estar adjacente e de gastar a Ação vale na Cena Tática. Fora dela, basta que o ajudante possa participar da tarefa, a critério do Narrador.
- **Status:** aprovada.
- **Arquivos:** `Regras/Mecânica Básica/Reserva de Dados.md` e a versão em `en/`.

**D-011 · 2026-11-02 · 01 Mecânica Básica (Q-006)**
- **Decisão:** a Ajuda continua com +1 dado e custo de uma Ação. Ela é fraca de propósito, como base a ser ampliada por Competências como o Inspirador.
- **Status:** mantida por intenção de design.
- **Consequência para revisões futuras:** não propor fortalecer a Ajuda base. Avaliar o valor dela nas Competências que a ampliam.

**D-012 · 2026-11-02 · 02 Personagens + Atributos (P-02.1)**
- **Decisão:** a página de Atributos deixa de repetir as regras de penalidade por categoria e de substituição e passa a apontar para a Reserva de Dados. A regra das substituições em fórmulas fixas continua em Atributos.
- **Status:** aprovada.
- **Arquivos:** `Regras/Personagens/Atributos.md` e a versão em `en/`.

**D-013 · 2026-11-02 · 02 Personagens + Atributos (P-02.2)**
- **Decisão:** a seção **Escala** passa a ficar em Atributos: 1 Fraco, 2 Médio, 3 Notável, 4 Excepcional, 5 Auge humano. A Criação de Personagem aponta para ela.
- **Status:** aprovada. Os níveis 3 e 4 também foram aprovados.
- **Arquivos:** `Regras/Personagens/Atributos.md`, `Criação de Personagem/2 - Atributos e Perícias.md` e as versões em `en/`.

**D-014 · 2026-11-02 · 02 Personagens + Atributos (P-02.3)**
- **Decisão:** a palavra "Capacidade" fica reservada ao termo das Competências. O título "Capacidades" do índice de Personagens vira "Atributos e Perícias", e "capacidades fundamentais" vira "aptidões fundamentais".
- **Status:** aprovada.
- **Consequência para revisões futuras:** apontar outros usos genéricos de "capacidade" ou "capacidades" no texto das regras.
- **Arquivos:** `Regras/Personagens/Personagens.md`, `Regras/Personagens/Atributos.md` e as versões em `en/`.

**D-015 · 2026-11-02 · 02 Personagens + Atributos (P-02.4)**
- **Decisão:** é intencional que Vigor e Determinação não tenham Perícias. O peso deles vem de Vida, Vontade, Iniciativa e resistências. Isso não precisa constar no texto.
- **Status:** mantida por intenção de design.
- **Consequência para revisões futuras:** não propor vincular Perícias a esses dois Atributos.

**D-016 · 2026-11-02 · 03 Perícias (P-03.1)**
- **Decisão:** dar ao Conhecimento Específico a função de **profundidade**. Em testes sobre o seu assunto, ele pode substituir Conhecimento Geral, Erudição ou Ocultismo, e o Narrador pode exigi-lo para informações raras. O exemplo "Medicina", que se sobrepunha a Curar, vira "Venenos".
- **Status:** aprovada, na opção (a).
- **Justificativa:** com o mesmo custo de uma Perícia ampla e sem função própria, era sempre melhor aumentar Erudição.
- **Arquivos:** `Regras/Personagens/Perícias.md` e a versão em `en/`.

**D-017 · 2026-11-02 · 03 Perícias (P-03.2)**
- **Decisão:** a regra de substituição sai de Perícias. Fica uma frase com link para a Reserva de Dados.
- **Status:** aprovada.

**D-018 · 2026-11-02 · 03 Perícias (P-03.3)**
- **Decisão:** a escala de Perícias passa a ficar em Perícias: 0 Sem treino, 1 Iniciante, 2 Competente, 3 Especialista, 4 Mestre e 5 Referência na área. A página diz que Perícia 0 não acrescenta dados. A Criação aponta para essa escala.
- **Status:** aprovada.
- **Arquivos:** `Regras/Personagens/Perícias.md`, `Criação de Personagem/2 - Atributos e Perícias.md` e as versões em `en/`.

**D-019 · 2026-11-02 · 03 Perícias (P-03.4)**
- **Decisão:** "áreas de competência" vira "áreas de conhecimento".
- **Status:** aprovada.
