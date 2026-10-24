# Atributos e Perícias Vinculados

Este documento resume a direção discutida para os **Atributos**, as **Perícias**, os ataques, as propriedades de armas e as substituições concedidas por Capacidades. Também registra as partes do sistema que precisarão ser revisadas antes que essa mudança seja incorporada às regras oficiais.

> [!warning] Estado do documento
> As **Etapas 1 a 6** foram incorporadas: Reserva de Dados, Atributos, Perícias, criação, Iniciativa, características derivadas, Confrontos, Manobras, Agarrado, Zonas, Mira, Armas, Pesado, catálogo, Trunfos legados, Arqueiro, criaturas e NPCs. As categorias de criaturas ainda sem ficha deverão ser criadas diretamente com as novas fórmulas. Ficha digital e automações permanecem como uma implementação separada, caso existam.

## Estado da implementação

- [x] Etapa 1 — Reserva de Dados, Atributos, Perícias e criação.
- [x] Etapa 2 — Iniciativa e características derivadas.
- [x] Etapa 3 — Confrontos, Manobras, Agarrado e Zonas.
- [x] Etapa 4 — Armas, Pesado e catálogo.
- [x] Etapa 5 — Mira, Trunfos legados e Competências.
- [x] Etapa 6 — Criaturas, NPCs e migração de fichas.

## Objetivo da mudança

Atualmente, uma mesma Perícia pode ser combinada livremente com diferentes Atributos, conforme a situação e a decisão do Narrador. A nova direção é dar a cada Perícia um **Atributo vinculado**, formando uma Reserva padrão estável.

Essa mudança pretende:

- tornar previsível qual Reserva cada ação utiliza;
- diferenciar melhor as funções dos Atributos;
- reduzir discussões sobre qual combinação representa cada abordagem;
- permitir que propriedades de armas e Capacidades modifiquem uma base conhecida;
- transformar substituições de Atributo em uma ferramenta real de construção de personagem.

A descrição narrativa continua importante para determinar a ação, suas consequências, Dificuldade e circunstâncias, mas não troca livremente o Atributo de uma Perícia. Substituições passam a depender de regras expressas.

## Direção consolidada

### Perícias possuem Atributos vinculados

Cada Perícia possui um Atributo padrão. Quando uma regra solicitar um teste com aquela Perícia, a Reserva normalmente será formada pelo Atributo vinculado e pela Perícia.

> **Atributo vinculado + Perícia = Reserva padrão**

Quando nenhuma Perícia se aplicar, testes apenas com um Atributo continuam existindo. Reservas formadas por dois Atributos também continuam existindo quando uma regra as determinar expressamente.

### Substituições são diretas

Propriedades, Capacidades e outras regras podem substituir o Atributo utilizado por uma Perícia, Ação, Reserva ou fórmula. A substituição não precisa possuir uma condição narrativa além daquela escrita na própria regra.

Exemplo de substituição em uma Perícia:

> Você pode utilizar **Astúcia** no lugar de **Carisma** em testes de Persuadir.

Exemplo de substituição em uma característica derivada:

> Sua Vida utiliza **Astúcia** no lugar de **Vigor**.

### Limites das substituições

- Uma substituição **troca** um Atributo; ela não soma o Atributo novo ao anterior.
- Duas substituições não formam uma cadeia nem permitem reunir vários Atributos na mesma parcela da Reserva.
- Quando mais de uma substituição estiver disponível, o personagem escolhe uma delas, salvo quando uma regra determinar expressamente outra coisa.
- A regra precisa indicar seu escopo exato. Substituir Vigor no cálculo da Vida não altera testes de Vigor, recuperação ou qualquer outra regra.
- Valores derivados são recalculados quando o Atributo que passou a compor sua fórmula é alterado.
- A categoria Física ou Espiritual da rolagem acompanha o Atributo efetivamente utilizado, inclusive depois de uma substituição.

## Ataques

### Fórmulas padrão

A direção adotada para os ataques comuns é:

| Ataque | Reserva padrão |
| --- | --- |
| Corpo a corpo | **Agilidade + Lutar** |
| Arma de disparo | **Agilidade + Atirar** |
| Arma arremessada | **Força + Arremessar** |

Agilidade representa a execução, a coordenação e a precisão necessárias para atingir o alvo. Força continua importante para Manobras, escudos, Carga, saltos, determinadas armas e Capacidades.

Como o dano de um Ataque é igual à **Margem + Dano da arma**, o Atributo usado no Ataque já influencia indiretamente o dano. Uma mesma regra não deve normalmente substituir Agilidade por Força no Ataque e também somar Força ao dano, pois isso faria o Atributo contribuir duas vezes para o mesmo resultado.

### Arremessar

**Arremessar** torna-se uma Perícia própria, vinculada a Força. Ela abrange objetos impulsionados diretamente pelo personagem, como facas, machados, lanças, pedras, granadas e armas improvisadas.

**Atirar** permanece reservado às armas que disparam projéteis, como arcos, bestas e armas de fogo.

Essa divisão cria uma opção à distância própria para personagens de Força sem transformar toda arma de disparo em uma arma de Força.

## Propriedade de arma baseada em Força

Armas cuja utilização ofensiva depende principalmente de potência, peso, impulso ou tensão podem determinar Força como Atributo do Ataque. O nome aprovado da propriedade é **Pesado**.

> **Pesado** — Ataques realizados com esta arma utilizam **Força no lugar de Agilidade**.

A propriedade é uma substituição, não um bônus. Ela não concede dados nem dano adicional por si mesma.

Ela pode existir em armas corpo a corpo e à distância, por exemplo:

- martelos de guerra;
- malhos;
- machados grandes;
- clavas massivas;
- determinados arcos de guerra ou de grande tensão.

Pesado não deve ser vinculado automaticamente ao Tipo de Dano **Contusão**. Um cassetete ou bordão pode continuar baseado em Agilidade, enquanto um machado pesado de Corte pode possuir Pesado. A propriedade representa o modo de utilização da arma, não o Tipo de Dano.

### Arcos

Nem todo arco precisa utilizar o mesmo Atributo.

| Arma | Reserva esperada |
| --- | --- |
| Arco curto ou comum | Agilidade + Atirar |
| Arco de guerra com Pesado | Força + Atirar |
| Besta | Agilidade + Atirar |

Isso permite arqueiros de Agilidade e arqueiros de Força sem tornar uma das duas construções universal.

## Atletismo, Acrobacia e Esquiva

### Divisão proposta

**Atletismo** fica vinculado a **Força** e representa potência e deslocamento corporal:

- correr;
- saltar;
- escalar;
- nadar;
- agarrar;
- empurrar;
- resistir a deslocamentos físicos.

**Acrobacia** é adicionada como Perícia vinculada a **Agilidade** e representa controle e precisão corporal:

- esquivar;
- equilibrar-se;
- amortecer quedas;
- realizar acrobacias;
- atravessar espaços estreitos ou instáveis.

Não é necessário criar Natação, Escalar ou outras Perícias físicas muito específicas no núcleo. Essas atividades permanecem reunidas em Atletismo. Cenários especializados ainda podem criar Perícias próprias.

### Esquiva padrão

> **Esquivar: Agilidade + Acrobacia**

Atletismo deixa de ser utilizado na Esquiva padrão. Oferecer Agilidade + Acrobacia e Força + Atletismo como opções básicas idênticas faria o jogador simplesmente escolher a maior Reserva e reduziria a importância das vinculações.

Força + Atletismo pode retornar por uma Capacidade:

> **Evasão Explosiva:** ao Esquivar, você pode utilizar **Força + Atletismo** no lugar de **Agilidade + Acrobacia**.

## Proposta de vinculação das Perícias

| Atributo | Perícias vinculadas |
| --- | --- |
| **Força** | Arremessar, Atletismo |
| **Agilidade** | Acrobacia, Atirar, Cavalgar, Dirigir, Furtividade, Lutar, Pilotar, Prestidigitação |
| **Vigor** | nenhuma Perícia padrão; resistência e Vida |
| **Carisma** | Empatia Animal, Intimidar, Mentir, Performance, Persuadir |
| **Astúcia** | Curar, Erudição, Navegar, Ocultismo, Perceber, Pesquisar, Sobrevivência |
| **Determinação** | nenhuma Perícia padrão; resistência e Vontade |

A ausência de Perícias vinculadas a Vigor e Determinação não significa que esses Atributos não sejam importantes. Eles já sustentam resistências, Vida, Vontade e outras fórmulas. Entretanto, a distribuição completa precisa ser testada junto às características derivadas.

## Ponto de atenção: concentração de funções

Com a nova estrutura, Agilidade passa a governar:

- ataques corpo a corpo comuns;
- ataques com armas de disparo comuns;
- Esquiva;
- Furtividade;
- várias Perícias de coordenação e condução.

Astúcia também concentra Percepção, investigação, conhecimento, cura, o limite de Mirando e metade da nova Iniciativa.

Por isso, não basta alterar as fórmulas de Ataque. A distribuição completa das funções foi revisada, retirando Agilidade da Iniciativa:

> **Astúcia + Determinação = Reserva de Iniciativa**

Essa fórmula representa percepção, prontidão, foco e decisão, reduz a concentração de funções em Agilidade e concede a Determinação uma participação ativa frequente. A alteração foi aprovada para a futura implementação.

## Ordem para determinar uma Reserva

Uma ordem geral evita conflitos entre Perícias, equipamentos e Capacidades:

1. a Perícia determina seu Atributo vinculado;
2. uma Ação ou propriedade de equipamento pode estabelecer uma fórmula diferente;
3. uma Capacidade pode substituir o Atributo da fórmula resultante e **sempre prevalece** sobre a Perícia, a Ação e a propriedade do equipamento;
4. bônus, penalidades e demais modificadores são aplicados;
5. apenas um Atributo ocupa cada parcela da Reserva, salvo quando a própria regra define uma Reserva de dois Atributos.

Uma Capacidade destinada a funcionar com qualquer arma deve dizer que define o **Atributo do Ataque**, em vez de dizer apenas que substitui Agilidade. Isso permite que ela também funcione com uma arma Pesada, cujo Atributo anterior seria Força.

## Mapa de alterações necessárias

### 1. Fundação da Reserva de Dados

#### `Regras/Mecânica Básica/Reserva de Dados.md`

Revisão estrutural necessária:

- remover a regra de que o Narrador escolhe livremente diferentes combinações;
- remover ou reescrever a seção **Diferentes Combinações**;
- apresentar Atributos vinculados como padrão;
- acrescentar as regras gerais de substituição;
- esclarecer Reservas de um Atributo e de dois Atributos;
- esclarecer que a categoria da rolagem acompanha o Atributo efetivamente utilizado.

### 2. Atributos e Perícias

#### `Regras/Personagens/Atributos.md`

- esclarecer a função de cada Atributo dentro da nova distribuição;
- registrar Agilidade como padrão de precisão e execução de ataques;
- reforçar Força em Atletismo, Arremessar, Manobras, escudos, Carga e armas Pesadas;
- registrar Astúcia e Determinação como componentes da Iniciativa;
- incluir referência às substituições de fórmulas e características derivadas.

#### `Regras/Personagens/Perícias.md`

Reescrita principal da mudança:

- adicionar uma coluna **Atributo vinculado**;
- adicionar **Acrobacia** e **Arremessar**;
- retirar arremessos da descrição de Atirar;
- retirar a flexibilidade geral de Atributos;
- remover os exemplos de Intimidar e Lutar com diferentes Atributos;
- remover as categorias Físico e Espiritual das Perícias, pois atualmente não possuem efeito mecânico e a categoria relevante já é a do Atributo utilizado;
- manter a liberdade de cenários adicionarem ou removerem Perícias.

#### `Criação de Personagem/2 - Atributos e Perícias.md`

- mencionar os Atributos vinculados;
- considerar o aumento de 20 para 22 Perícias na distribuição inicial;
- testar se os perfis Generalista, Equilibrado e Especialista continuam oferecendo pontos suficientes depois da inclusão de Acrobacia e Arremessar.

Não é necessário aumentar os pontos automaticamente, mas a diluição adicional precisa ser observada em criação e jogo.

### 3. Confrontos e defesas

#### `Regras/Cenas e Conflitos/Ações/Confrontar.md`

Revisão estrutural necessária:

- fixar **Agilidade + Lutar** para ataques corpo a corpo comuns;
- fixar **Agilidade + Atirar** para armas de disparo;
- fixar **Força + Arremessar** para armas arremessadas;
- explicar que propriedades e Capacidades podem alterar o Atributo;
- remover o exemplo padrão de Força + Lutar e a flexibilidade decidida pela abordagem;
- manter Defender com Força e escudo;
- alterar Esquivar para **Agilidade + Acrobacia**;
- remover Força + Atletismo como opção básica de Esquiva;
- verificar Aceitar o Confronto com armas Pesadas ou arremessadas.

#### `Regras/Equipamentos/Escudos.md`

Defender já possui um espaço próprio para Força. A regra pode permanecer baseada em Força, mas as referências à Reserva de Defender devem ser conferidas depois da revisão de Confrontar.

#### `Regras/Equipamentos/Armaduras.md`

A penalidade à Esquiva pode continuar incidindo sobre qualquer Reserva usada para Esquivar, inclusive quando uma Capacidade substituir Agilidade + Acrobacia. O texto precisa apenas ser conferido para não vincular a penalidade a uma Perícia específica.

### 4. Manobras

#### `Regras/Cenas e Conflitos/Ações/Manobras.md`

- remover a escolha livre de combinações pelo Narrador;
- manter Reposicionar, Derrubar e Agarrar com **Força + Atletismo**;
- estabelecer as Reservas de resistência dessas Manobras;
- fixar Desarmar em uma única fórmula, provavelmente **Agilidade + Lutar**;
- definir como a propriedade **Manobra** de uma arma interage com o Atributo do Ataque e com Pesado;
- manter Mirar aplicável a ataques à distância, e não apenas à Perícia Atirar.

#### `Regras/Condições/Agarrado.md`

- substituir a escolha narrativa das Reservas para escapar por uma fórmula fixa, provavelmente **Força + Atletismo** contra **Força + Atletismo**;
- permitir que Capacidades específicas substituam essa fórmula.

### 5. Zonas e Esquiva de área

#### `Regras/Cenas e Conflitos/Zonas.md`

- alterar a resistência padrão de **Agilidade + Atletismo** para **Agilidade + Acrobacia**;
- manter a possibilidade de uma Zona determinar outra Reserva quando sua natureza exigir;
- revisar as criaturas, pois a troca de Atletismo por Acrobacia altera significativamente suas Reservas contra Zonas.

### 6. Armas e propriedades

#### `Regras/Equipamentos/Armas.md`

- adicionar a propriedade **Pesado**;
- fazer Pesado funcionar em armas corpo a corpo e de disparo;
- alterar **Arremesso (valor)** para utilizar a Perícia Arremessar;
- esclarecer que uma arma arremessada usa Força + Arremessar, salvo substituição;
- definir a interação de Pesado com Capacidades que estabelecem outro Atributo de Ataque;
- manter Dano separado do Atributo usado no Ataque.

#### `Regras/Equipamentos/Catálogo de Armas.md`

Cada arma foi avaliada inicialmente em [[Análise de Armas e Propriedade Pesado]]. A proposta atual aplica Pesado a:

- Maça;
- Martelo de Guerra;
- Mangual;
- Montante;
- Machado Grande;
- Malho;
- Alabarda;
- Machado de Batalha;
- Clava Massiva;
- Porrete com Espinhos;
- Arco Longo, representando um arco de guerra de grande tensão.

Também será necessário:

- mover Adaga, Machadinha, Lança Curta e Dardo para Arremessar quando usados à distância;
- conferir se alguma arma leve deve possuir uma propriedade ou Capacidade que permita Arremessar com Agilidade;
- diferenciar claramente Arco Curto, Arco Longo e Besta;
- revisar as tabelas para que propriedades de armas à distância sejam exibidas corretamente.

#### `Regras/Equipamentos/Armas.md` e `Regras/Equipamentos/Maestrias.md`

- adicionar Pesado à análise das propriedades;
- revisar as propriedades Manobra, pois as Manobras deixarão de aceitar combinações abertas;
- conferir textos que assumem Atletismo ou a antiga flexibilidade de Atributos.

### 7. Mira e capacidades de ataque à distância

#### `Regras/Condições/Mirando.md`

- trocar “Ataque com Atirar” por **Ataque à distância**, fazendo Mirar beneficiar também Arremessar;
- remover a menção de que armas de arremesso utilizam Atirar;
- manter Astúcia como limite de acúmulos, salvo decisão posterior.

#### `reestruturação/Competências/Competências/Arqueiro.md`

A Competência já utiliza principalmente “ataque com arco”, portanto funciona tanto com arcos de Agilidade quanto com arcos Pesados de Força. Ainda assim, deve ser conferido:

- se todas as Capacidades usam “Reserva de ataque com o arco” em vez de citar uma fórmula antiga;
- se Passo do Arqueiro e Recuo Tático devem continuar metrificados por Agilidade mesmo para arqueiros de Força;
- se alguma futura Capacidade permitirá estabelecer Astúcia ou outro Atributo como Atributo de Ataque com arco.

### 8. Iniciativa e características derivadas

#### `Regras/Cenas e Conflitos/A Cena.md`

- alterar a Iniciativa de Agilidade + Astúcia para **Astúcia + Determinação**;
- revisar desempates e qualquer Capacidade que use a Reserva inteira de Iniciativa.

#### `Criação de Personagem/3 - Características Derivadas.md`

- atualizar a fórmula da Iniciativa para Astúcia + Determinação;
- registrar que Capacidades podem substituir o Atributo de Vida, Vontade, Carga, Iniciativa ou outras fórmulas;
- esclarecer o recálculo desses valores.

#### `Regras/Personagens/Vida.md`, `Vontade.md` e `Progressão.md`

- manter as fórmulas padrão atuais;
- acrescentar compatibilidade com substituições de Atributo;
- atualizar a regra de recálculo para observar o Atributo efetivamente usado pela fórmula modificada.

### 9. Movimento

#### `Regras/Movimento/Saltar.md`

A fórmula atual já utiliza Força e Atletismo de maneira coerente com a nova vinculação. Em princípio, não precisa mudar.

#### `Regras/Movimento/Movimentação.md` e `Correr.md`

- manter a movimentação automática;
- esclarecer, em testes narrativos de natação ou escalada, que a Reserva padrão é Força + Atletismo;
- testes prolongados de exaustão podem continuar utilizando Vigor separadamente.

### 10. Trunfos legados e futuras Competências

#### `Regras/Personagens/Trunfos/Combate.md`

#### `reestruturação/Competências/Trunfos não convertidos em Privilégios.md`

- substituir referências que tratam armas arremessadas como Atirar;
- revisar Atirador, Mirando, Esquiva e capacidades relacionadas à Iniciativa;
- converter alternativas de Reserva em Capacidades explícitas;
- considerar uma Capacidade semelhante a **Evasão Explosiva**;
- considerar Capacidades que estabeleçam Força, Astúcia, Carisma ou Determinação como Atributo de Ataque;
- revisar capacidades que somem novamente ao dano o mesmo Atributo já utilizado no Ataque.

As substituições diretas podem ser utilizadas para criar identidades completas, não apenas exceções circunstanciais. Exemplos:

- Mentalista usando Astúcia com Persuadir;
- combatente usando Força em todos os ataques corpo a corpo;
- duelista usando Agilidade com Arremessar;
- personagem cuja Vida utiliza outro Atributo;
- combatente sobrenatural estabelecendo Carisma ou Determinação como Atributo de Ataque.

### 11. Criaturas e NPCs

#### `Regras/Personagens/Criaturas em Análise.md`

A migração será significativa:

- Arremessar não deve mais ser convertido em Atirar;
- criaturas com valores antigos separados de Atirar e Arremessar precisam recuperar esses valores da fonte ou receber uma nova distribuição;
- ataques naturais passam a usar Agilidade + Lutar por padrão;
- criaturas baseadas em potência precisarão de ataques naturais Pesados ou de uma característica que estabeleça Força como Atributo de Ataque;
- armas de ogros, trolls, minotauros e outras criaturas precisam ser classificadas individualmente;
- Acrobacia precisa ser distribuída, especialmente porque ela substituirá Atletismo contra Zonas;
- animais ágeis que atualmente possuem Atletismo elevado podem precisar transferir parte desse valor para Acrobacia.

Essa etapa exige recalcular as Reservas ofensivas e defensivas de todas as criaturas. Apenas trocar os nomes das Perícias alteraria bastante o equilíbrio existente.

#### `Regras/Personagens/Características de NPC em Análise.md`

- manter testes explícitos de resistência formados por dois Atributos;
- manter Força + Atletismo para escapar de Teia, se essa for a fórmula final de libertação;
- verificar toda Característica que diga apenas “ataque à distância” para determinar qual Perícia e Atributo utiliza.

### 12. Condições e referências secundárias

Arquivos que precisam ao menos de conferência textual:

- `Regras/Condições/Condições.md`;
- `Regras/Condições/Fúria.md`;
- `Regras/Equipamentos/Catálogo de Armaduras.md` e `Regras/Equipamentos/Catálogo de Escudos.md`;
- `Readme.md` e índices de criação;
- quaisquer fichas, compêndios ou automações que contenham a lista fixa de Perícias.

## Implementação em ficha ou automação

Caso a ficha digital ou o Foundry já automatizem essas regras, também será necessário:

- adicionar Acrobacia e Arremessar ao modelo de personagem;
- migrar os valores existentes de Atirar e Atletismo sem apagar dados;
- armazenar o Atributo vinculado de cada Perícia;
- permitir que itens e Capacidades estabeleçam o Atributo final de uma Reserva;
- impedir soma ou encadeamento indevido de substituições;
- atualizar os seletores de Ataque, Esquiva, Zona, Manobra e Arremesso;
- recalcular características derivadas a partir do Atributo substituto;
- atualizar fichas de NPC e ataques naturais;
- exibir no card da rolagem qual Atributo foi utilizado e qual regra o substituiu.

## Sequência recomendada de implementação

1. **Consolidar as decisões:** Acrobacia, Arremessar, Pesado, Astúcia + Determinação para Iniciativa e a lista separada de Manobras.
2. **Reescrever a fundação:** Reserva de Dados, Atributos e Perícias.
3. **Atualizar criação e progressão:** lista de Perícias, pontos iniciais e recálculo.
4. **Atualizar combate:** Confrontar, Esquivar, Manobras, Agarrado e Zonas.
5. **Atualizar equipamentos:** propriedades, catálogo e armas arremessadas.
6. **Atualizar Mira, Trunfos legados e Competências.**
7. **Migrar criaturas e NPCs**, recalculando Reservas.
8. **Atualizar ficha e automações**, se aplicável.
9. **Realizar testes de criação e combate** antes de considerar a mudança finalizada.

## Testes necessários

A implementação deve ser testada com pelo menos estes arquétipos:

- duelista de Agilidade;
- guerreiro de Força com arma Pesada;
- arqueiro de Agilidade com arco curto;
- arqueiro de Força com arco de guerra;
- arremessador de Força;
- arremessador ágil por Capacidade;
- defensor de escudo;
- acrobata especializado em Esquiva;
- atleta de Força com Evasão Explosiva;
- personagem social de Carisma;
- Mentalista que substitui Carisma por Astúcia;
- criatura forte e lenta;
- criatura pequena e ágil.

Os testes devem comparar:

- tamanho das Reservas de Ataque e defesa;
- Margens e dano médio;
- concentração de funções em Agilidade e Astúcia;
- valor de Força fora do combate corpo a corpo;
- sobrevivência contra Zonas;
- quantidade de Perícias exigidas por cada arquétipo;
- impacto das substituições sobre penalidades Físicas e Espirituais.

## Pendências antes da alteração oficial

- [x] Confirmar **Acrobacia** como nova Perícia de Agilidade.
- [x] Confirmar **Arremessar** como nova Perícia de Força.
- [x] Adotar **Pesado** como nome da propriedade.
- [x] Produzir uma análise inicial das armas que recebem Pesado em [[Análise de Armas e Propriedade Pesado]].
- [x] Fazer Mirar beneficiar qualquer Ataque à distância, incluindo Arremessar.
- [x] Montar uma lista separada de Manobras e Reservas em [[Manobras e Reservas]].
- [x] Alterar a Iniciativa para Astúcia + Determinação.
- [ ] Conversar posteriormente sobre os pontos iniciais de Perícia; por enquanto, não os alterar.
- [x] Capacidades sempre prevalecem sobre Pesado e outras regras anteriores que estabeleçam o Atributo do Ataque.
- [ ] Conversar posteriormente sobre uma Capacidade que permita usar Força + Atletismo para Esquivar, como **Evasão Explosiva**; por enquanto, não adicioná-la.
- [ ] Revisar a distribuição de Perícias e funções entre os seis Atributos depois dos primeiros testes.
