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

**D-020 · 2026-11-02 · 03 Perícias (Q-008): direção das maestrias de arma**
- **Decisão (princípio):**
  - Lutar, Atirar e Arremessar continuam como Perícias.
  - Cada arma pode ter **uma maestria**, tirada de um catálogo.
  - Quando uma Perícia de Ataque chega a **5**, o personagem ganha a maestria de **uma arma específica** de sua escolha (por exemplo espada longa ou adaga). Cada arma adicional custa **3 XP**.
- **Status:** aprovada como direção. A aplicação nas regras fica para a seção 42 (Armas).
- **A detalhar na seção 42:**
  - se a categoria Especial (Letal, Varredura, Debilitante) vira o catálogo de Maestrias;
  - a linha nova na tabela de Progressão;
  - o caso da arma usada com duas Perícias (por exemplo, a adaga corpo a corpo com Lutar e arremessada com Arremessar);
  - Desarmado;
  - como os NPCs recebem maestria;
  - possíveis sobreposições com Competências de combate.
- **Consequência:** a maestria é da arma escolhida, não do efeito. Dominar a espada longa não libera a mesma maestria em outra arma que também a tenha.

**D-021 · 2026-11-02 · 04 Tamanho (P-04.1 e P-04.3)**
- **Decisão:** **Limite de Tamanho** único. Uma criatura só pode Agarrar, Derrubar ou mover contra a vontade (Reposicionar, arrastar alguém Agarrado) um alvo de no máximo **uma categoria maior** que ela. Desarmar não tem limite. A regra antiga, "mover só alvos do mesmo Tamanho ou menor", sai.
- **Status:** aprovada. O autor considerou que a pergunta sobre Pequeno contra Médio entra nessa mesma regra.
- **Justificativa:** uma criatura muito menor não deve conseguir imobilizar ou derrubar uma muito maior. Uma regra só, para todos os casos, é mais simples.
- **Consequências:** um personagem Pequeno agora move um Médio, e um Médio move um Grande (antes não podia). Um Médio não agarra nem derruba mais um alvo Enorme.
- **Arquivos:** `Regras/Personagens/Tamanho.md`, `Regras/Cenas e Conflitos/Ações/Manobras.md`, `Regras/Condições/Agarrado.md` e as versões em `en/`.

**D-022 · 2026-11-02 · 04 Tamanho (P-04.2)**
- **Decisão:** uma criatura Minúscula pode ocupar o quadrado de outra criatura e pode ser atravessada por qualquer uma. Na tabela, o espaço dela passa a ser "divide um quadrado".
- **Status:** aprovada.
- **Arquivos:** `Regras/Personagens/Tamanho.md` e a versão em `en/`.

**D-023 · 2026-11-02 · 05 Vida (P-05.1): Condição Incapacitado**
- **Decisão:** nova Condição **Incapacitado**. Ela se aplica quando a trilha de Vida está toda agravada. O personagem fica Caído, sem Ação, sem Movimentação e sem responder a Confrontos (é um alvo sem resposta). A Condição termina quando ao menos 1 ponto agravado é convertido. Mais dano fica a critério do Narrador (opção a).
- **Status:** aprovada.
- **Arquivos:** `Regras/Condições/Incapacitado.md` (novo), `Regras/Condições/Condições.md`, `Regras/Personagens/Vida.md`, `Regras/Cenas e Conflitos/Ações/Confrontar.md` e as versões em `en/`.

**D-024 · 2026-11-02 · 05 Vida (P-05.2 e P-05.3)**
- **Decisão:** com a trilha cheia, cada ponto de dano adicional converte 1 espaço superficial em agravado. O agravado fica à esquerda na trilha. O texto foi reorganizado: a regra "por padrão todo dano é agravado" abre a seção Gravidade do Dano, e a conversão por armadura e Resistência aparece uma vez só.
- **Status:** aprovada. A reorganização (P-05.3) foi assumida como aprovada e comunicada ao autor.
- **Arquivos:** `Regras/Personagens/Vida.md` e a versão em `en/`.

**D-025 · 2026-11-02 · 05 Vida (P-05.4): Tratamento e instalações adequadas**
- **Decisão:**
  - **Tratamento:** fora da Cena Tática, exige material de cura (sem material, não há como tratar; com ele, não há bônus). Astúcia + Curar, cada Sucesso converte 1 ponto agravado, no máximo uma vez por dia por personagem. Quem está Incapacitado não pode tratar a si mesmo.
  - **Instalações adequadas:** dispensam o material, dão +2 dados e garantem no mínimo 3 pontos. Sem curador no grupo, a equipe do local garante o mínimo.
  - Os Primeiros Socorros como regra separada **não** foram adotados.
- **Status:** aprovada, depois de três rodadas de discussão.
- **Justificativa:** o hospital tem que ser o melhor lugar de cura, o que o autor exigiu. Com um piso de 3 e +2 dados, ele é sempre melhor que tratar o mesmo paciente fora dele, sem esvaziar quem investe em Curar.
- **Futuro:** uma Competência poderá permitir Tratar durante a Cena Tática ou sem material.
- **Pendência:** "material de cura" precisa virar um item em Equipamentos (Q-009).
- **Arquivos:** `Regras/Personagens/Vida.md` e a versão em `en/`.

**D-026 · 2026-11-02 · 06 Vontade (P-06.1): Vontade como recurso**
- **Decisão:** a Vontade é um recurso que o personagem gasta, e sua trilha representa a psique dele. A introdução passa a dizer isso, e sai a menção a "suportar medo, pressão, influência psicológica". Por padrão, todo dano de Vontade é superficial. Ele é agravado só quando a fonte indicar (Fraturas, Romper Limite, Capacidades). A cláusula que deixava o Narrador causar dano de Vontade livremente não foi adotada.
- **Status:** aprovada. A resposta do autor ("a Vontade é para ser uma forma de usar recursos e representa a psique do personagem") foi lida como escolha da alternativa, mantendo a gravidade padrão.
- **Arquivos:** `Regras/Personagens/Vontade.md` e a versão em `en/`.

**D-027 · 2026-11-02 · 06 Vontade (P-06.2): trilha preenchida igual à da Vida**
- **Decisão:** a trilha cheia, com qualquer combinação de dano, dá -2 dados nas rolagens Espirituais. Cada ponto de dano adicional converte 1 espaço superficial em agravado, e o agravado fica à esquerda. Com a trilha toda agravada, o -2 vale para todas as rolagens, no lugar do Espiritual (não soma), e a consequência dura até que 1 ponto agravado se torne superficial.
- **Status:** aprovada.
- **Arquivos:** `Regras/Personagens/Vontade.md` e a versão em `en/`.

**D-028 · 2026-11-02 · 06 Vontade (P-06.3): Romper Limite para qualquer uso**
- **Decisão:** com a trilha cheia, qualquer uso de Vontade, inclusive o custo de Vontade das Capacidades, é pago ao Romper Limite (opção c). As menções específicas em Atirador e Mentalista saíram, porque ficaram redundantes.
- **Status:** aprovada, contra a recomendação (a).
- **Consequências:** Furioso (entrar em Fúria), Guardião, Sentinela e Inspirador passam a poder pagar seus custos com dano agravado quando a trilha está cheia. Reavaliar nas seções 20, 21, 22 e 25.
- **Arquivos:** `Regras/Personagens/Vontade.md`, `Regras/Competências/Atirador.md`, `Regras/Competências/Mentalista.md` e as versões em `en/`.

**D-029 · 2026-11-02 · 06 Vontade (P-06.4): texto enxuto**
- **Decisão:**
  - introdução em um parágrafo;
  - superficial e agravado em uma frase cada;
  - saíram as frases redundantes, sobre a trilha de Vida em Ignorar Penalidades e sobre "marcado normalmente";
  - o Desejo entrou na lista de Recuperação;
  - a ordem segue a da Vida.
  As âncoras usadas por outras páginas foram mantidas.
- **Status:** aprovada.
- **Arquivos:** `Regras/Personagens/Vontade.md` e a versão em `en/`.

**D-030 · 2026-11-02 · 07 Descanso Prolongado (P-07.1): descanso interrompido**
- **Decisão:** um conflito ou outro esforço significativo interrompe o descanso, que precisa ser recomeçado. Interrupções breves, como um turno de vigia, não o impedem.
- **Status:** aprovada.
- **Arquivos:** `Regras/Personagens/Descanso Prolongado.md` e a versão em `en/`.

**D-031 · 2026-11-02 · 08 Ambição e Desejo (P-08.1): Desejo cumprido**
- **Decisão:** rejeitada. Um novo Desejo continua sendo escolhido só no início da sessão. O Desejo pode durar várias sessões, e, depois de cumprido, o personagem fica sem Desejo até a próxima sessão. O texto passa a dizer isso explicitamente.
- **Status:** rejeitada (regra mantida e esclarecida).
- **Arquivos:** `Regras/Personagens/Ambição e Desejo.md` e a versão em `en/`.

**D-032 · 2026-11-02 · 08 Ambição e Desejo (P-08.2 e P-08.3): critério e troca da Ambição; texto**
- **Decisão:**
  - **critério:** "trabalhou ativamente" é o único critério da Ambição, e os exemplos de progresso viraram exemplos de trabalho ativo;
  - **troca:** a Ambição pode ser trocada no início de uma sessão, quando for concluída, se tornar impossível ou quando as motivações do personagem mudarem de verdade;
  - **texto:** a página foi enxugada, de cerca de 900 para cerca de 540 palavras, e os exemplos foram mantidos.
- **Status:** aprovada.
- **Arquivos:** `Regras/Personagens/Ambição e Desejo.md` e a versão em `en/`.

**D-033 · 2026-11-02 · 09 Convicções e Pilares (P-09.1): alcance do benefício**
- **Decisão:** opção (a). O benefício da Convicção (uma vez por sessão, ao agir por ela) serve só para Rerrolar Dados ou Ignorar Penalidades Físicas e não paga custos de Vontade de Capacidades. A página de Vontade foi corrigida para dizer o mesmo.
- **Status:** aprovada.
- **Arquivos:** `Regras/Personagens/Convicções e Pilares.md`, `Regras/Personagens/Vontade.md` e as versões em `en/`.

**D-034 · 2026-11-02 · 09 Convicções e Pilares (P-09.2): Fraturas pelo Pilar**
- **Decisão:** rejeitada. A regra fica como está:
  - Pilar ferido ou corrompido dá 1 Fratura;
  - Pilar perdido ou morto dá 2 Fraturas e rompe a Convicção.
- **Status:** rejeitada.

**D-035 · 2026-11-02 · 09 Convicções e Pilares (P-09.3): reparo só com Fratura**
- **Decisão:** reparar uma Fratura converte 1 agravado de Vontade. Uma Convicção íntegra não tem o que reparar, e defendê-la não converte dano. O autor quer outras formas de curar agravado de Vontade além das Fraturas (Q-012).
- **Status:** aprovada.
- **Arquivos:** `Regras/Personagens/Convicções e Pilares.md` e a versão em `en/`.

**D-036 · 2026-11-02 · 10 Progressão (P-10.1 a P-10.3)**
- **Decisão:**
  - **P-10.1:** a penalidade de Convicções rompidas (+2 XP por Convicção rompida) aparece abaixo da tabela de custos, com link.
  - **P-10.2:** linha de máximos. Atributos e Perícias vão até 5, e cada Competência até o máximo da sua progressão.
  - **P-10.3:** a regra completa de Competências fica em Competências. Progressão mantém a linha da tabela, um exemplo e o link. Exemplos reduzidos a um por linha e texto final em um parágrafo.
  - **Ritmo de XP:** os 2 XP por sessão são uma sugestão. Cada campanha define seu ritmo a critério do Narrador (por exemplo, XP só ao concluir missões). O texto passa a dizer isso.
- **Status:** aprovada. O ritmo foi esclarecido pelo autor.
- **Arquivos:** `Regras/Personagens/Progressão.md` e a versão em `en/`.

**D-037 · 2026-11-02 · 11 Competências (P-11.1 a P-11.3)**
- **Decisão:**
  - **P-11.1:** o rodapé volta para o Astra (Readme), como nas outras áreas.
  - **P-11.2:** a seção Nível foi enxugada. A criação virou uma frase com link para a Criação de Personagem, que passa a ser a única fonte da regra. "Formato" virou uma frase.
  - **P-11.3:** nas seções 12 a 25, cada PR de Competência também revisa a sua linha na lista de Competências.
- **Status:** aprovada.
- **Arquivos:** `Regras/Competências/Competências.md` e a versão em `en/`.

**D-038 · 2026-11-02 · 12 Acrobata (P-12.1 e P-12.2)**
- **Decisão:**
  - **P-12.1:** o deslocamento da Evasão é o de uma Esquiva e segue suas regras. O autor resumiu: "a Evasão é uma Esquiva".
  - **P-12.2:** "Ao vencer ao Esquivar" virou "Ao vencer uma Esquiva", e a linha da lista de Competências foi atualizada.
- **Status:** aprovada.
- **Arquivos:** `Regras/Competências/Acrobata.md`, `Regras/Competências/Competências.md` e as versões em `en/`.

**D-039 · 2026-11-02 · 13 Ambidestro (P-13.1 a P-13.3)**
- **Decisão:**
  - **P-13.1:** a secundária precisa alcançar o oponente do Confronto só ao atacar ou Aceitar o Confronto, porque o objetivo é causar dano. Na defesa (Guarda Cruzada), o alcance não é exigido.
  - **P-13.2:** no Nível 3, uma arma Flexível conta como arma de uma mão, com o Dano de uma mão. Antes disso, só armas Leves servem como secundária.
  - **P-13.3:** a linha da lista cita o Nível 3.
- **Status:** aprovada. A leitura de P-13.1 (alcance só no ataque) foi interpretada da resposta do autor e comunicada.
- **Arquivos:** `Regras/Competências/Ambidestro.md`, `Regras/Competências/Competências.md` e as versões em `en/`.

**D-040 · 2026-11-02 · 14 Aparador (P-14.1)**
- **Decisão:** o Nível 1 define o termo: "Você pode **Aparar**: escolher Defender... usando uma arma corpo a corpo". O autor também concordou com o registro da Q-013 (armas grandes contra Escudos) para as seções 42 e 45.
- **Status:** aprovada.
- **Arquivos:** `Regras/Competências/Aparador.md` e a versão em `en/`.


**D-041 · 2026-11-02 · 15 Assassino (P-15.1 a P-15.3)**
- **Decisão:** o Nível 5 continua só aumentando os valores. No Golpe Furtivo, a lista de motivos (que incluía a Reserva abaixo de 1 dado, obsoleta pela D-007) saiu: o bônus vale para qualquer alvo sem resposta, "inclusive quando ele foi surpreendido pelo Primeiro Golpe", e os casos ficam só na página do Alvo sem Resposta. Nova linha na lista de Competências.
- **Status:** aprovada.
- **Arquivos:** `Regras/Competências/Assassino.md`, `Regras/Competências/Competências.md` e as versões em `en/`.

**D-042 · 2026-11-02 · 16 Atirador (P-16.1 a P-16.4)**
- **Decisão:** dano de Vontade não conta como sofrer dano; regras que falam em sofrer dano sem citar a Vontade se referem à Vida (regra geral em Vontade). Na Mirando, os acúmulos se perdem ao "utilizar sua Movimentação enquanto estiver Mirando", qualquer que seja a origem deles. A Mira Estável permite assumir a Postura depois de se mover e se mover nela, até metade da Movimentação base no Turno. O Nível 1 do Atirador abre com "Você pode assumir uma Postura de Tiro", o limite do Nível 5 é Astúcia + 5, e a linha da lista foi reescrita.
- **Status:** aprovada.
- **Arquivos:** `Regras/Personagens/Vontade.md`, `Regras/Condições/Mirando.md`, `Regras/Competências/Atirador.md`, `Regras/Competências/Competências.md` e as versões em `en/`.

**D-043 · 2026-11-02 · 17 Caçador (P-17.1 a P-17.3)**
- **Decisão:** no Conhecer a Presa, uma pergunta pode ser repetida para descobrir outra Resistência, Imunidade, Vulnerabilidade ou Característica. Saiu a frase redundante sobre a Reserva sem Nível em Natureza ou Ocultismo. Nova linha na lista de Competências.
- **Status:** aprovada.
- **Arquivos:** `Regras/Competências/Caçador.md`, `Regras/Competências/Competências.md` e as versões em `en/`.

**D-044 · 2026-11-02 · 18 Cativante (P-18.1 a P-18.3)**
- **Decisão:** a tabela de Progressão perdeu a coluna de bônus, que sugeria +4 em todos os testes no Nível 2. A Primeira Impressão virou uma frase só ("qualquer que seja a Perícia ou a abordagem"), com o link para Bonito codificado como os demais. A linha da lista fala em "aparência".
- **Status:** aprovada.
- **Arquivos:** `Regras/Competências/Cativante.md`, `Regras/Competências/Competências.md` e as versões em `en/`.

**D-045 · 2026-11-02 · 19 Duelista (P-19.1 a P-19.3)**
- **Decisão:** a exigência de arma corpo a corpo em uma mão e a outra livre é dita uma vez, na introdução, e sai do começo de cada Nível. Na Superioridade Técnica saiu "corpo a corpo", redundante com a Vantagem Numérica. A penalidade do Desafio e da Condição Desafiado é fixa em -3 dados. Nova linha na lista de Competências.
- **Status:** aprovada.
- **Arquivos:** `Regras/Competências/Duelista.md`, `Regras/Condições/Desafiado.md`, `Regras/Competências/Competências.md` e as versões em `en/`.

**D-046 · 2026-11-02 · 20 Furioso (P-20.1 a P-20.3)**
- **Decisão:** o Sangue por Sangue continua com +1 por superficial e +2 por agravado, mesmo com o dano agravado por padrão. Recusar a Queda usa a Condição Incapacitado. A introdução diz que a Fúria é um estado da Competência, não uma Condição, e saíram duas frases redundantes (Investida Furiosa e Além da Dor). Nova linha na lista. O custo de Vontade da Fúria foi reavaliado (acompanhamento da D-028) e fica como está.
- **Status:** aprovada.
- **Arquivos:** `Regras/Competências/Furioso.md`, `Regras/Competências/Competências.md` e as versões em `en/`.

**D-047 · 2026-11-02 · 21 Guardião (P-21.1)**
- **Decisão:** a restrição de uso enquanto surpreendido, Incapacitado ou Paralisado foi para a introdução e vale para o Cobrir Aliado e o Interpor-se, com link para a Condição Incapacitado. O custo de Vontade do Interpor-se e dos usos extras do Cobrir Aliado foi reavaliado (acompanhamento da D-028) e fica como está.
- **Status:** aprovada.
- **Arquivos:** `Regras/Competências/Guardião.md` e a versão em `en/`.

**D-048 · 2026-11-02 · 22 Inspirador (P-22.1 e P-22.2)**
- **Decisão:** a tabela de Progressão perdeu a coluna "Inspiração", que era sempre +2. Nova linha na lista. O valor da Ajuda ampliada foi avaliado (pedido da D-011) e não muda, e o custo de Vontade do Refrão também fica como está (acompanhamento da D-028).
- **Status:** aprovada.
- **Arquivos:** `Regras/Competências/Inspirador.md`, `Regras/Competências/Competências.md` e as versões em `en/`.
