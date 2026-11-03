# Questões em aberto

Itens para revisitar. Cada um tem um **gatilho**: o momento da revisão em que deve ser retomado.

---

**Q-001 · Ordem das áreas: Readme × wiki**
- **Origem:** diagnóstico e seção 00.
- **Descrição:** o Readme lista Mecânica Básica, Personagens, Competências, Criaturas, Cenas e Conflitos… A árvore da wiki usa Mecânica Básica, Personagens, Criação de Personagem, Cenas e Conflitos, Competências, Criaturas… Dentro de Cenas e Conflitos, o índice e a wiki também diferem (Cenas Táticas e A Cena aparecem invertidas). A ordem da wiki é decidida pelo gerador do astra-engine.
- **Gatilho:** seção 53, ou antes se decidido na seção 00.

**Q-002 · Competências revisadas antes de Cenas e Conflitos**
- **Origem:** diagnóstico.
- **Descrição:** Capacidades dependem de Ações, Manobras e Condições, que só serão revisadas depois. Capacidades afetadas por decisões posteriores devem ser reabertas.
- **Gatilho:** seções 31 a 52.

**Q-003 · Resíduos em `Design/`**
- **Origem:** diagnóstico.
- **Descrição:** notas já incorporadas (*Manobras e Reservas*, *Atributos e Perícias Vinculados*) e nomes que ainda citam Privilégios (*Trunfos não convertidos em Privilégios*). Estão fora da wiki e fora do escopo das regras.
- **Gatilho:** seção 53.
- **Nota (seção 11):** `Design/Competências/Fundamento.md`, leitura obrigatória pelo `CLAUDE.md`, está desatualizado: aviso de "estado da reestruturação" e exemplos com Competências que não existem (Escaramuçador, Atirador de Guerra).
- **Nota (seção 24):** o Fundamento deve prever Competências que só aumentam um valor, sem Capacidades e sem Ápice, como o Robusto (D-050), e Níveis que só aumentam valores, como o Nível 5 do Assassino (D-041).

**Q-004 · Termo "array" e "perfis" na Criação de Personagem**
- **Origem:** seção 00.
- **Descrição:** o Readme e a Criação de Personagem usam "array fixo", um anglicismo. Avaliar um termo em português.
- **Gatilho:** seção 27.
- **Resolvida (2026-11-02):** "array fixo" virou "valores" na página e "valores fixos" na visão geral; "perfis" ficou (D-053).

**Q-005 · O que é núcleo e o que é módulo**
- **Origem:** seção 00.
- **Descrição:** a Introdução apresenta o Astra como "núcleo + módulos", mas as regras não indicam o que é núcleo e o que é opcional. Verificar se alguma regra deveria ser marcada como módulo.
- **Gatilho:** seção 53.
- **Atualização (2026-11-01):** o autor confirmou que haverá módulos adicionais, distribuídos no Foundry como módulos (pacotes de extensão). Falta definir como as regras do núcleo e as de módulo serão separadas no vault e na wiki.

**Q-006 · Valor da Ajuda em combate**
- **Origem:** seção 01.
- **Descrição:** ajudar gasta a Ação inteira por +1 dado (cerca de +0,5 Sucesso esperado). Fora do Inspirador, isso raramente compensa numa Cena Tática.
- **Gatilho:** seções 32 (Ação) e 33 (Confrontar).
- **Resolvida (2026-11-02):** a Ajuda é fraca de propósito e serve de base para Competências que a ampliam (D-011).

**Q-007 · Atributos acima de 5 e padrão das Reservas de resistência**
- **Origem:** seção 02.
- **Descrição:** a escala de 1 a 5 é definida para personagens, e não está dito se criaturas podem passar de 5. As Reservas de resistência usam pares de Atributos definidos caso a caso (Vigor + Determinação, Determinação + Astúcia, Vigor + Força), sem um padrão geral.
- **Gatilho:** seções 30 (Características de NPC) e 48 (Condições).
- **Nota (D-026):** a Vontade é um recurso. Só deve haver dano externo se uma regra específica o definir, nunca por decisão livre do Narrador.
- **Resolvida (2026-11-02, D-056):** criaturas que não são humanas podem ter Atributos acima de 5; personagens ficam em 5. Reservas padrão para resistir: Vigor + Determinação (corpo) e Determinação + Astúcia (mente); as características atuais mantêm as suas.

**Q-008 · Proficiências de combate e maestria de armas**
- **Origem:** seção 03, ideia do autor.
- **Descrição:** substituir Lutar, Arremessar e Atirar por proficiências (0 a 5) por arma ou grupo de armas. A proficiência máxima daria acesso a uma maestria da arma ou do grupo. Isso reabre a decisão de `Design/Equipamentos/Conversão de Maestrias em Propriedades.md` ("a arma determina o que ela faz; a Competência determina o que o personagem sabe fazer").
- **Afeta:** Perícias, Confrontar, Manobras, Defender, Desarmado, Armas e Propriedades Especiais, Competências de combate, Características de NPC, criação, custos de XP e o astra-engine.
- **Gatilho:** em discussão na seção 03. O detalhamento provavelmente fica para a seção 42 (Armas).
- **Discussão de 2026-11-02:**
  - **Decidido pelo autor:** Lutar, Atirar e Arremessar continuam como Perícias, sem divisão por arma ou grupo.
  - **Decidido pelo autor:** a maestria é uma propriedade da arma, tirada de um **catálogo de maestrias**, que exige domínio do personagem para ser usada. Cada arma tem a sua.
  - **Referência:** as maestrias de arma do D&D, por exemplo "ao andar 4 quadrados em linha reta, ganha X".
  - **Proposta em discussão:** unificar com a categoria Especial. Hoje todas as Propriedades Especiais (Letal, Varredura, Debilitante) vieram de antigas maestrias. A categoria "Especial" passaria a se chamar "Maestria", com no máximo uma por arma, e só pode usá-la quem tiver a Perícia de Ataque da arma no patamar exigido.
  - **Em aberto:** o patamar exigido (5, como o autor propôs, ou menor) e se a maestria vale para qualquer arma da Perícia ou só para armas escolhidas.
  - **Detalhamento do catálogo:** seção 42 (Armas).
- **Status:** fechada na seção 42 (D-068): a categoria Especial virou Maestria; domínio de uma arma com a Perícia de Ataque em 5 e +3 XP por arma.

**Q-009 · Item "material de cura"**
- **Origem:** seção 05 (D-025).
- **Descrição:** o Tratamento exige material de cura, mas esse item não existe em Equipamentos.
- **Gatilho:** seção 41 (Equipamentos).
- **Status:** fechada na seção 41 (D-067): Kit de Cura no Catálogo de Itens.

**Q-010 · Futura Competência de cura**
- **Origem:** seção 05.
- **Descrição:** o autor pretende criar uma Competência que permita Tratar durante a Cena Tática e/ou sem material de cura.
- **Gatilho:** quando as Competências forem revisadas (seções 11 a 25), ou depois disso.

**Q-011 · Dano de Vontade causado por fontes externas**
- **Origem:** seção 06.
- **Descrição:** nenhuma regra causa dano de Vontade de fora, salvo a decisão do Narrador. Avaliar se o Aterrorizante, alguma Condição ou alguma Ação social deve causar dano de Vontade, e se há teste para resistir.
- **Gatilho:** seções 30 (Características de NPC) e 48 (Condições).
- **Parte de NPCs resolvida (2026-11-02, D-056):** o Aterrorizante não causa dano de Vontade; o Medo basta. A parte das Condições segue para a seção 48.

**Q-012 · Outras fontes de recuperação de agravado de Vontade**
- **Origem:** seção 09 (D-035).
- **Descrição:** o autor quer outras formas de curar dano agravado de Vontade além do reparo de Fraturas. Hoje já existem:
  - a Ambição (1 por sessão);
  - a restauração de uma Convicção rompida (até 2).

  Avaliar se isso basta ou se deve haver outra fonte, como uma Competência (paralela à Q-010) ou um "tratamento" mental fora de cena.
- **Gatilho:** decisão do autor; revisitar nas Competências (seções 11 a 25).

**Q-013 · Armas grandes com Aparador contra Escudos**
- **Origem:** seção 14.
- **Descrição:** com Aparador, uma arma de Dano 4 dá +4 ao Defender, mais do que o Escudo de Corpo (+3), e ainda ataca. O Escudo não exige Competência, mas ocupa a mão e tem custos. Avaliar se o Escudo precisa de algo que a arma não tem.
- **Gatilho:** seções 42 (Armas) e 45 (Escudos).

**Q-014 · Ficha de criatura**
- **Origem:** seção 30.
- **Descrição:** o núcleo não diz como definir a Vida, a Vontade, a Absorção base e os Ataques naturais de NPCs, nem se eles seguem as fórmulas dos personagens. Hoje o Narrador usa as fórmulas dos personagens.
- **Gatilho:** seção 53, ou um futuro guia de criação de criaturas. Depende da Q-015.

**Q-015 · Lista única de Capacidades para personagens e NPCs**
- **Origem:** seção 30 (ideia do autor).
- **Descrição:** criar uma lista única de Capacidades, sem Nível nem restrição, usada de duas formas:
  - as Competências montam suas progressões fixas com Capacidades dessa lista;
  - NPCs recebem Capacidades soltas da lista, sem precisar de Competências.
- **Decidido em princípio:** as Competências continuam existindo para os jogadores (não viram feats compráveis um a um). Capacidades que hoje escalam com o Nível da Competência passam a ter um valor configurável, como "Nada Escapa (N)": na Competência, N é o Nível; no NPC, é o valor escolhido. As Características de NPC atuais entram na mesma lista.
- **Gatilho:** desenho à parte, com a Q-003 (Fundamento) na seção 53.

**Q-016 · Dano de queda**
- **Origem:** seção 34.
- **Descrição:** Reposicionar diz que a queda de uma borda é "resolvida normalmente", mas o núcleo não tem regra de dano de queda.
- **Gatilho:** seções 38 a 40 (Movimento, Correr, Saltar).
- **Status:** fechada na seção 38 (D-064).

**Q-017 · Fim do agarrão e mão livre**
- **Origem:** seção 34.
- **Descrição:** Agarrado só termina quando o alvo escapa. Falta dizer se quem agarra pode soltar, se o agarrão acaba quando os dois deixam de estar adjacentes ou quando quem agarra fica Incapacitado, e se agarrar exige uma mão livre.
- **Gatilho:** seção 48 (Condições).
