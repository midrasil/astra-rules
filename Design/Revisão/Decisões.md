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

**D-049 · 2026-11-02 · 23 Mentalista (P-23.1 a P-23.3)**
- **Decisão:** na Leitura Fria, uma pergunta sobre forças e fraquezas pode ser repetida, como no Caçador (D-043). Em Eu Já Sabia, o limite é "até 5 pontos" de dano superficial de Vontade. Nova linha na lista. A Manipulação continua valendo contra qualquer alvo, e o custo de Vontade de Eu Já Sabia não muda (acompanhamento da D-028).
- **Status:** aprovada.
- **Arquivos:** `Regras/Competências/Mentalista.md`, `Regras/Competências/Competências.md` e as versões em `en/`.

**D-050 · 2026-11-02 · 24 Robusto (P-24.1)**
- **Decisão:** o Robusto continua como Competência de valor (+1 de Vida por Nível, sem Capacidades e sem Ápice). O Fundamento deve prever esse tipo de Competência; a nota foi para a Q-003 (seção 53).
- **Status:** aprovada.
- **Arquivos:** nenhum arquivo de regras; `Design/Revisão/Questões em aberto.md`.

**D-051 · 2026-11-02 · 25 Sentinela (P-25.1)**
- **Decisão:** na introdução, "incapacitado" passa a ser a Condição [Incapacitado], com link, como no Furioso (D-046) e no Guardião (D-047). A interação com o Acrobata não precisa de regra própria, e o custo de Vontade da Vigilância Incansável não muda (acompanhamento da D-028).
- **Status:** aprovada.
- **Arquivos:** `Regras/Competências/Sentinela.md` e a versão em `en/`.

**D-052 · 2026-11-02 · 26 Visão geral + Identidade (P-26.1 e P-26.2)**
- **Decisão:** a primeira frase da visão geral cita a identidade e usa "equipamento inicial", e a linha da Identidade inclui os Pilares. Na Identidade, uma frase diz que os Pilares são combinados com o Narrador, porque passam a fazer parte da história.
- **Status:** aprovada.
- **Arquivos:** `Criação de Personagem/0 - Criação de Personagem.md`, `Criação de Personagem/1 - Identidade.md` e as versões em `en/`.

**D-053 · 2026-11-02 · 27 Atributos e Perícias + Características Derivadas (P-27.1 a P-27.4)**
- **Decisão:**
  - "array fixo" vira "valores" na página e "valores fixos" na visão geral (fecha a Q-004);
  - sai a lista de exemplos das 24 Perícias; os dois tetos de 4 viram uma seção curta, "Teto na criação"; nova frase sobre Conhecimento Específico e idiomas de Erudição;
  - perfis de Perícias igualados em 90 XP: Generalista com seis Perícias em 1 (eram sete) e Equilibrado com seis (eram cinco);
  - Características Derivadas: os novos espaços de Vida ou Vontade entram vazios; sai a menção vaga a "outras regras anteriores".
- **Status:** aprovada.
- **Arquivos:** `Criação de Personagem/0 - Criação de Personagem.md`, `Criação de Personagem/2 - Atributos e Perícias.md`, `Criação de Personagem/3 - Características Derivadas.md` e as versões em `en/`.

**D-054 · 2026-11-02 · 28 Competências + Equipamento Inicial (P-28.1 a P-28.3)**
- **Decisão:**
  - os Pontos de Competência são usados na criação: não podem ser guardados nem convertidos em XP; o Nível Total ganhou link;
  - sem indicação do cenário, o orçamento inicial é de **100 de Valor**;
  - no Equipamento Inicial, Valor e Carga máxima viram links, sem repetir a fórmula da Carga e a regra de substituição.
- **Status:** aprovada.
- **Arquivos:** `Criação de Personagem/4 - Competências.md`, `Criação de Personagem/5 - Equipamento Inicial.md` e as versões em `en/`.

**D-055 · 2026-11-02 · 29 Criaturas + Tipos de Criatura (P-29.1 e P-29.2)**
- **Decisão:** não existe criatura sem tipo: cada criatura tem um único Tipo, o que melhor descreve o que ela é agora (um dragão morto-vivo é Morto-vivo). O Tipo só tem efeito quando uma regra o cita, como o Caçador; tipos novos de cenários e módulos devem dizer como essas regras os tratam.
- **Status:** aprovada.
- **Arquivos:** `Regras/Criaturas/Tipos de Criatura.md` e a versão em `en/`.

**D-056 · 2026-11-02 · 30 Características de NPC (P-30.1 a P-30.5)**
- **Decisão:**
  - "Ataque natural" definido: Ataque com o corpo da criatura, com Dano, Tipo de Dano e Alcance na ficha, como uma arma, usando Agilidade + Lutar salvo indicação;
  - criaturas que não são humanas podem ter Atributos acima de 5; personagens ficam limitados a 5;
  - Reservas padrão para resistir quando a característica não indicar: Vigor + Determinação (corpo) e Determinação + Astúcia (mente); as características atuais mantêm as suas (fecha a Q-007);
  - o Aterrorizante não causa dano de Vontade (fecha a parte de NPCs da Q-011);
  - Frenesi usa o Alcance; Teia ganha Alcance 6; sai a frase repetida do Aterrorizante; "token" vira "espaço que ela ocupa";
  - novas questões: Q-014 (ficha de criatura) e Q-015 (lista única de Capacidades, mantendo as Competências para os jogadores).
- **Status:** aprovada.
- **Arquivos:** `Regras/Criaturas/Características de NPC.md`, `Regras/Personagens/Atributos.md` e as versões em `en/`.

**D-057 · 2026-11-03 · 31 Cenas e Conflitos + Cenas Táticas + A Cena (P-31.1 a P-31.5)**
- **Decisão:**
  - nova seção **Surpresa** em A Cena: quem não percebe a ameaça no início da Cena Tática fica surpreendido (alvo sem resposta) até o seu primeiro Turno; o Narrador decide, com teste opcional de Astúcia + Perceber contra Agilidade + Furtividade;
  - sai a frase da Iniciativa sobre Reserva abaixo de 1 dado (a Reserva Mínima já cobre);
  - a Cena termina quando o lugar, o momento ou a situação mudam o bastante; quem entra depois rola a Iniciativa ao entrar;
  - "Narrativa vs Tática" passa para a página Cenas Táticas, que perde a lista "Estrutura"; A Cena fica com Rodadas, Turnos, Iniciativa, Surpresa e O Turno;
  - "Cena" com maiúscula.
- **Status:** aprovada.
- **Arquivos:** `Regras/Cenas e Conflitos/A Cena.md`, `Regras/Cenas e Conflitos/Cenas Táticas.md` e as versões em `en/`.

**D-058 · 2026-11-03 · 32 Ação (P-32.1 e P-32.2)**
- **Decisão:** a página Ação foi reescrita de forma enxuta, sem mudar regras: Ações Básicas (com a lista) antes das Ações Narrativas, sem as repetições, e "Confrontar" no lugar de "Atacar". Nova frase: falar algumas palavras, fazer um gesto ou soltar um objeto não exige Ação.
- **Status:** aprovada.
- **Arquivos:** `Regras/Cenas e Conflitos/Ação.md` e a versão em `en/`.

**D-059 · 2026-11-03 · 33 Confrontar (P-33.1 e P-33.2)**
- **Decisão:**
  - o Confronto usa a Ação; "derrotados" vira Incapacitados na Vantagem Numérica; Esquivar aponta a penalidade de armadura;
  - tabela das três respostas em "Respondendo ao Confronto"; Defender e Esquivar remetem a ela para empate e vitória do atacante; o alcance para Aceitar fica em um só lugar; Aparar e Cobrir Aliado passam para a seção Defender. Nenhuma regra muda.
- **Status:** aprovada.
- **Arquivos:** `Regras/Cenas e Conflitos/Ações/Confrontar.md` e a versão em `en/`.

**D-060 · 2026-11-03 · 34 Manobras (P-34.1, P-34.2 e P-34.3)**
- **Decisão:**
  - alcance padrão adjacente para Manobras com alvo; exceções ficam escritas na própria Manobra (Manobra (X) continua estendendo até o Alcance da arma);
  - um alvo pode aceitar a Manobra (funciona sem rolagem); quem não pode resistir segue Alvo sem Resposta (1 Sucesso);
  - Mirar remete à Condição Mirando, que concentra as regras; o bônus vale contra qualquer alvo e não se aplica às respostas a um Confronto;
  - tabela das Manobras e regras comuns (sem dano, limite de Tamanho) escritas uma vez; sai "Manobras e Capacidades".
- **Status:** aprovada.
- **Arquivos:** `Regras/Cenas e Conflitos/Ações/Manobras.md`, `Regras/Condições/Mirando.md` e as versões em `en/`.

**D-061 · 2026-11-03 · 35 Aguardar (P-35.1 e P-35.2)**
- **Decisão:**
  - Atrasar o Turno não é uma Ação e é decidido antes que o Turno comece; efeitos de começo do Turno acontecem só quando o personagem de fato age;
  - personagens atrasados que entram depois do mesmo Turno agem na ordem original da Iniciativa;
  - em Preparar uma Ação, "condição" vira "gatilho" ("trigger"); sai o exemplo repetido e o parágrafo duplicado sobre a nova posição.
- **Status:** aprovada.
- **Arquivos:** `Regras/Cenas e Conflitos/Ações/Aguardar.md` e a versão em `en/`.

**D-062 · 2026-11-03 · 36 Zonas (P-36.1, P-36.2 e P-36.3)**
- **Decisão:**
  - formatos de Zona, com diagramas: Explosão N, Rajada N e Linha N (padrão de grade com diagonal 1); o Sopro usa Rajada 3;
  - criatura que não pode resistir a uma Zona conta como 1 Sucesso (Alvo sem Resposta); Zona persistente afeta cada criatura no máximo uma vez por Rodada;
  - contra Zonas, Resistências e Vulnerabilidades são somadas como na Absorção Efetiva: saldo positivo converte agravado em superficial, saldo negativo aumenta o Dano.
- **Status:** aprovada.
- **Arquivos:** `Regras/Cenas e Conflitos/Zonas.md`, `Regras/Resistência e Vulnerabilidade/Resistência e Vulnerabilidade.md`, `Regras/Criaturas/Características de NPC.md` e as versões em `en/`.

**D-063 · 2026-11-03 · 37 Iluminação (P-37.3, modelo do D&D 5e)**
- **Decisão:**
  - três níveis: Claro (nenhum efeito), Penumbra (-2 dados em Perceber pela visão; Ataques não são afetados) e Escuro (quem está ali não pode ser visto: -4 dados em toda rolagem que dependa de vê-lo, inclusive Ataques, respostas e Perceber), com exemplos;
  - conta a iluminação de onde está o que se tenta ver;
  - Visão no Escuro sobe um nível (Penumbra → Claro, Escuro → Penumbra);
  - o Breu deixa de ser nível: a escuridão sobrenatural conta como Escuro e bloqueia a Visão no Escuro; o -6 sai;
  - fontes de luz: vela (1 + 1), tocha (4 + 4), lampião (6 + 6).
- **Status:** aprovada.
- **Arquivos:** `Regras/Cenas e Conflitos/Iluminação.md`, `Regras/Criaturas/Características de NPC.md` e as versões em `en/`.

**D-064 · 2026-11-03 · 38 Movimento + Movimentação (P-38.1, P-38.2 ajustada e P-38.3)**
- **Decisão:**
  - a Movimentação pode ser dividida antes e depois da Ação; só aliados podem ser atravessados; reduções à metade antes de somas e subtrações; mínimo 0;
  - nova seção Queda (modelo do D&D 5e): 1 de dano de Contusão a cada 2 quadrados, sem teste, sem Absorção, máximo 10; quem sofre dano termina Caído; quem salta para baixo de propósito desconta a altura do Salto Vertical (fecha a Q-016);
  - teste de exaustão: Vigor + Determinação.
- **Status:** aprovada.
- **Arquivos:** `Regras/Movimento/Movimentação.md` e a versão em `en/`.

**D-065 · 2026-11-03 · 39 Correr (P-39.1 e P-39.2)**
- **Decisão:** Correr dá pontos de Movimentação (não quadrados) iguais à Movimentação base; os efeitos de Correr se acumulam (Capacidade + Ação); página reescrita em três parágrafos.
- **Status:** aprovada.
- **Arquivos:** `Regras/Movimento/Correr.md` e a versão em `en/`.

**D-066 · 2026-11-03 · 40 Saltar (P-40.1 e P-40.2)**
- **Decisão:**
  - Saltar deixa de ser Ação e passa a fazer parte da Movimentação (modelo do D&D 5e): cada quadrado saltado custa 1 ponto; as fórmulas de distância e altura não mudam; Saltar sai da lista de Ações Básicas;
  - o Impulso é uma corrida em linha reta logo antes do salto;
  - a conversão 1 quadrado = 1,5 m vai para Movimentação.
- **Status:** aprovada.
- **Arquivos:** `Regras/Movimento/Saltar.md`, `Regras/Movimento/Movimentação.md`, `Regras/Cenas e Conflitos/Ação.md` e as versões em `en/`.

**D-067 · 2026-11-03 · 41 Equipamentos (P-41.1, P-41.2 ajustada e P-41.3)**
- **Decisão:**
  - "slots" sai: a Carga é um número inteiro; Carga máxima = 5 + Força;
  - novo Catálogo de Itens (preços do D&D 5e): Kit de Cura (Carga 1, Valor 5, 5 usos), fontes de luz, básicos de aventura; itens de Carga 0 contam 1 a cada 10 (fecha a Q-009);
  - acima do dobro da Carga máxima, o personagem não consegue se mover carregando tudo.
- **Status:** aprovada.
- **Arquivos:** `Regras/Equipamentos/Equipamentos.md`, `Regras/Equipamentos/Catálogo de Itens.md` (novo), `Armas.md`, `Armaduras.md`, `Escudos.md`, `Regras/Personagens/Vida.md`, `Regras/Cenas e Conflitos/Iluminação.md`, `Criação de Personagem/3 - Características Derivadas.md`, `Criação de Personagem/5 - Equipamento Inicial.md` e as versões em `en/`.

**D-068 · 2026-11-03 · 42 Armas (P-42.1 e P-42.2)**
- **Decisão:**
  - a categoria Especial passa a se chamar **Maestria** (no máximo uma por arma) e só pode ser usada por quem domina a arma;
  - Domínio de arma: quando uma Perícia de Ataque chega a 5, o personagem domina uma arma específica que use essa Perícia; cada arma a mais custa 3 XP e exige 5 em uma das Perícias que ela usa; o domínio é da arma, não do efeito, e vale em qualquer Ataque com ela; Desarmado não tem Maestria; NPCs dominam as armas que o Narrador indicar (fecha a Q-008);
  - Leve ganha texto explícito (sem efeito próprio, exigida por Capacidades como Ambidestro); a tabela de campos acompanha o catálogo; Pesado perde a frase redundante sobre Força no dano.
- **Status:** aprovada.
- **Arquivos:** `Regras/Equipamentos/Armas.md`, `Catálogo de Armas.md`, `Regras/Personagens/Progressão.md`, `Regras/Competências/Aparador.md`, `Regras/Cenas e Conflitos/Ações/Confrontar.md`, `Regras/Condições/Abalado.md`, `Lento.md` e as versões em `en/`.

**D-069 · 2026-11-04 · 43.A Munição e Recarga (P-43.A1 a P-43.A4)**
- **Decisão:**
  - nova Propriedade de Uso **Munição (tipo)**: cada disparo gasta 1 munição, inclusive ao Aceitar o Confronto; sacar a munição faz parte do Ataque; vale o Material da munição; ao fim da Cena, recupera-se metade da munição gasta;
  - nova Propriedade de Uso **Recarga**: a arma dispara no máximo uma vez por Rodada;
  - Flechas, Virotes e Balas de funda no Catálogo de Itens (pacotes de 20, Carga 1, preços do 5e);
  - Arcos, Besta e Funda recebem as Propriedades novas no Catálogo de Armas.
- **Status:** aprovada.
- **Arquivos:** `Regras/Equipamentos/Armas.md`, `Catálogo de Armas.md`, `Catálogo de Itens.md` e as versões em `en/`.

**D-070 · 2026-11-04 · 43.B Critério de equilíbrio (P-43.B1 e P-43.B2)**
- **Decisão:**
  - orçamento por arma: o Dano base vem da Empunhadura (Leve 1, uma mão 2, Duas mãos 4; à distância Leve 1, Duas mãos 2) e Alcance 2 tira 1 de Dano;
  - toda arma tem uma Maestria e uma vantagem; uma desvantagem compra +1 de Dano ou mais uma vantagem;
  - Versátil e Pesado são livres; Valor, Carga e Material ficam fora da conta;
  - o critério fica em `Design/Equipamentos/Critério de Equilíbrio de Armas.md`, fora das regras.
- **Status:** aprovada.
- **Arquivos:** `Design/Equipamentos/Critério de Equilíbrio de Armas.md` (novo).

**D-071 · 2026-11-05 · 43.C Maestrias novas e catálogo (P-43.C1 a P-43.C3)**
- **Decisão:**
  - quatro Maestrias novas: Embalo (+1 dado no próximo Ataque contra o mesmo alvo), Raspão (metade do Dano da arma, superficial, quando o alvo vence), Deslocar (move o alvo 1 quadrado) e Perfurar (a Absorção converte 1 ponto a menos);
  - duas Propriedades de Uso novas, que entram na lista de vantagens do critério: Investida (+1 de Dano depois de 3 quadrados em linha reta) e Guarda (+1 dado ao Esquivar); Disparo Rápido foi proposta e retirada;
  - 16 armas ajustadas para caber no orçamento da D-070 (tabela na seção 43), incluindo Arco Curto 18, Arco Longo Dano 2 e Alcance 24, Besta 18 e Funda 15.
- **Status:** aprovada.
- **Arquivos:** `Regras/Equipamentos/Armas.md`, `Catálogo de Armas.md`, `Design/Equipamentos/Critério de Equilíbrio de Armas.md` e as versões em `en/`.

**D-072 · 2026-11-05 · 44 Armaduras (P-44.1 a P-44.3)**
- **Decisão:**
  - tabela de campos na ordem do catálogo; o personagem veste uma armadura por vez;
  - vestir e tirar seguem os tempos do 5e (1, 5 ou 10 minutos para vestir; 1 ou 5 para tirar) e não cabem numa Cena Tática;
  - nova Propriedade **Ruidosa** (-2 dados em Furtividade); toda armadura Pesada é Ruidosa;
  - orçamento de armaduras (Absorção base pela Categoria, uma vantagem: +1 de Absorção ou Resistência 1; Ruidosa compra mais uma) e catálogo ajustado: Gibão, Couro, Peles e Camisão ganham Resistências, Couro Batido passa a Perfurante, Brunea sobe para Absorção 3, Talas ganha Resistência a Perfurante e Carga 3;
  - o critério de equilíbrio passa a cobrir armas e armaduras, em `Design/Equipamentos/Critério de Equilíbrio de Equipamentos.md` (antes `Critério de Equilíbrio de Armas.md`).
- **Status:** aprovada.
- **Arquivos:** `Regras/Equipamentos/Armaduras.md`, `Catálogo de Armaduras.md`, `Regras/Resistência e Vulnerabilidade/Resistência e Vulnerabilidade.md`, o critério em `Design/` e as versões em `en/`.

**D-073 · 2026-11-05 · 45 Escudos (fecha a Q-013)**
- **Decisão:**
  - Proteção por Categoria: Leve 2, Médio 3, Pesado 4 (antes 1, 2 e 3); o Aparar não muda e fica na mesma faixa;
  - Propriedades de escudo: **Cobertura** (+1 de Proteção contra Ataques à distância), **Repelir** (ao vencer ao Defender corpo a corpo, empurra o atacante 1 quadrado) e **Golpe de Escudo** (o escudo é também uma arma de uma mão, Dano 1, Contusão, sem Leve e sem Maestria; pode ser arma secundária);
  - catálogo: Broquel (Golpe de Escudo), Escudo (Repelir), Escudo de Corpo (Cobertura);
  - tabela de campos alinhada ao catálogo; sai a repetição do -1 dado do Escudo Pesado;
  - orçamento de escudos no critério de equipamentos.
- **Status:** aprovada.
- **Arquivos:** `Regras/Equipamentos/Escudos.md`, `Catálogo de Escudos.md`, `Regras/Cenas e Conflitos/Ações/Confrontar.md`, o critério em `Design/` e as versões em `en/`.

**D-074 · 2026-11-05 · 46 Trocar Equipamento (P-46.1 e P-46.2)**
- **Decisão:**
  - uma vez por Turno, sacar ou guardar um equipamento não exige Ação (modelo do 5e); soltar nunca exige; mais do que isso exige Trocar Equipamento; pegar do chão continua exigindo a Ação;
  - saem "pela primeira vez" e "Sacar não é Trocar", o que fecha a brecha de soltar uma arma e sacar outra de graça sem custo;
  - frase lembrando que armaduras não se trocam numa Cena Tática; descrição do link em Equipamentos atualizada.
- **Status:** aprovada.
- **Arquivos:** `Regras/Equipamentos/Trocar Equipamento.md`, `Regras/Equipamentos/Equipamentos.md` e as versões em `en/`.

**D-075 · 2026-11-05 · 47 Resistência e Vulnerabilidade (P-47.1 a P-47.4, P-47.2 ajustada)**
- **Decisão:**
  - Perfurar reduz a Absorção Efetiva do alvo em 1, até no mínimo 0;
  - Ir para a Garganta ignora só a Absorção da armadura; a Absorção base e as Resistências e Vulnerabilidades da armadura continuam valendo;
  - a Absorção Efetiva negativa só soma dano quando o personagem sofre pelo menos 1 ponto de dano daquela fonte;
  - a Investida de NPC remete à Propriedade de arma Investida, como a mesma regra com valores próprios.
- **Status:** aprovada.
- **Arquivos:** `Regras/Equipamentos/Armas.md`, `Regras/Criaturas/Características de NPC.md`, `Regras/Resistência e Vulnerabilidade/Resistência e Vulnerabilidade.md`, `Vulnerabilidade.md` e as versões em `en/`.

**D-076 · 2026-11-05 · 48 Condições (P-48.1 a P-48.5; fecha a Q-011)**
- **Decisão:**
  - o índice de Condições ganha a seção "Regras gerais": sem indicação, a Condição termina no fim da Cena; durações em Turnos contam os Turnos do afetado; aplicar de novo não acumula, só renova a duração, e vale a que terminar por último, salvo nas Condições acumuláveis;
  - Mirando termina no fim da Cena, e não mais no "fim do combate";
  - o título solto foi tirado do corpo de Desafiado;
  - nova Condição **Sangrando** (*Bleeding*), acumulável: no fim de cada Turno do afetado, ele sofre dano superficial igual aos acúmulos e depois perde 1; o dano não tem Tipo; Estancar usa a Ação e testa Astúcia + Curar, e cada Sucesso remove 1 acúmulo; nenhuma regra aplica o Sangrando ainda;
  - Q-011: nenhuma Condição causa dano de Vontade, porque o Medo cobre o efeito mental.
- **Status:** aprovada.
- **Arquivos:** `Regras/Condições/Condições.md`, `Mirando.md`, `Desafiado.md`, `Sangrando.md` (novo) e as versões em `en/`.

**D-077 · 2026-11-05 · 49 Caído + Agarrado (P-49.1 a P-49.8; fecha a Q-017)**
- **Decisão:**
  - levantar-se custa metade da Movimentação base, arredondada para cima, da Movimentação que resta no Turno;
  - agarrar exige uma mão livre, ocupada enquanto o agarrão durar; criaturas sem mãos usam a parte do corpo indicada na ficha;
  - quem agarra solta quando quiser, sem Ação; o agarrão termina se os dois deixam de estar adjacentes ou se quem agarra fica Incapacitado ou Paralisado;
  - efeitos sem quem agarre, como a Teia, definem a própria fuga;
  - para escapar, o Agarrado escolhe Força + Atletismo ou Agilidade + Acrobacia, contra Força + Atletismo;
  - nova subseção **Deslocamento forçado** em Movimentação: não gasta a Movimentação, acontece com Movimentação 0, não provoca efeitos que reagem ao movimento e usa as regras de obstáculos e bordas do Reposicionar;
  - arrastar: quem agarra usa Movimentação Especial e põe o alvo adjacente a cada quadrado; para o alvo, é deslocamento forçado.
- **Status:** aprovada.
- **Arquivos:** `Regras/Condições/Caído.md`, `Regras/Condições/Agarrado.md`, `Regras/Cenas e Conflitos/Ações/Manobras.md`, `Regras/Movimento/Movimentação.md` e as versões em `en/`.

**D-078 · 2026-11-05 · 50 Debilitado + Lento + Abalado + Envenenado (P-50.1 a P-50.3)**
- **Decisão:**
  - Abalado vale no próximo Ataque, iniciado ou feito ao Aceitar o Confronto; Manobras, Defender e Esquivar não contam nem encerram a Condição;
  - Envenenado dura o que a fonte indicar (na Venenosa, a Potência) e pode vir de características, Capacidades, itens e outros efeitos;
  - Envenenado entra nos exemplos de Ignorar Penalidades Físicas da Vontade;
  - Debilitado e Lento sem mudança.
- **Status:** aprovada.
- **Arquivos:** `Regras/Condições/Abalado.md`, `Regras/Condições/Envenenado.md`, `Regras/Personagens/Vontade.md` e as versões em `en/`.

**D-079 · 2026-11-05 · 51 Paralisado + Atordoado + Medo (P-51.1 a P-51.4)**
- **Decisão:**
  - Regras gerais: uma Condição aplicada durante o Turno do afetado não conta esse Turno na duração;
  - Paralisado não responde a Confrontos e entra na lista do Alvo sem Resposta;
  - Atordoado ainda responde a Confrontos;
  - Paralisado e Atordoado podem vir de qualquer fonte que os cite, e não só da Paralisante e da Atordoante;
  - uma criatura Voadora Paralisada no ar cai;
  - Medo sem mudança.
- **Status:** aprovada.
- **Arquivos:** `Regras/Condições/Condições.md`, `Paralisado.md`, `Atordoado.md`, `Regras/Cenas e Conflitos/Ações/Confrontar.md`, `Regras/Criaturas/Características de NPC.md` e as versões em `en/`.

**D-080 · 2026-11-05 · 52 Mirando + Lido + Desafiado (P-52.1 e P-52.2)**
- **Decisão:**
  - Desafiado também termina quando o Duelista fica Incapacitado ou deixa a Cena;
  - um personagem desafiado por mais de um Duelista sofre -3 dados uma vez só e não sofre a penalidade contra nenhum deles;
  - Mirando e Lido sem mudança; a perda da Mira pelo dano do Sangrando é mantida.
- **Status:** aprovada.
- **Arquivos:** `Regras/Condições/Desafiado.md` e a versão em `en/`.

**D-081 · 2026-11-05 · 53 Fechamento estrutural (53.A a 53.D; fecha Q-001, Q-002, Q-003 e Q-005)**
- **Decisão:**
  - Furioso: "fim do combate" virou "fim da Cena" (único ajuste da Q-002);
  - a lista "Regras do sistema" do Readme é a ordem oficial, por dependência: Mecânica Básica, Personagens, Cenas e Conflitos, Movimento, Equipamentos, Resistência e Vulnerabilidade, Condições, Competências, Criaturas; o astra-engine deve segui-la;
  - tudo em `Regras/` é núcleo; cada módulo terá pasta própria fora de `Regras/`; convenção registrada no `CLAUDE.md` e no Readme;
  - nove notas incorporadas foram movidas para `Design/Arquivo/`; o Fundamento perdeu as referências a Competências inexistentes e ganhou os formatos de Competência de valor e Nível de valor;
  - Q-010, Q-012, Q-014 e Q-015 seguem abertas, com gatilhos atualizados.
- **Status:** aprovada.
- **Arquivos:** `Readme.md`, `CLAUDE.md`, `Regras/Competências/Furioso.md`, `Design/Competências/Fundamento.md`, `Design/Arquivo/` e as versões em `en/`.
