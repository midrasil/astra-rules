# 53 · Fechamento estrutural

**Arquivos:** `Readme.md`, `Regras/Competências/Furioso.md`, `Design/` (organização e Fundamento), `Design/Revisão/` e `en/` quando couber
**Relacionadas:** todas as seções anteriores
**Pendências que chegam aqui:** Q-001, Q-002, Q-003, Q-005, Q-014, Q-015; Q-010 e Q-012 seguem abertas por decisão do autor
**Status:** concluída (PR #75, mergeado em 2026-11-05)

A seção fecha a revisão. Ela tem quatro partes, que podem ser decididas uma a uma, como na seção 43.

| Parte | Assunto | Questões |
|---|---|---|
| **53.A** | Competências afetadas pelas decisões das seções 31 a 52 | Q-002 |
| **53.B** | Ordem das áreas e o que é núcleo ou módulo | Q-001, Q-005 |
| **53.C** | Organização de `Design/` e atualização do Fundamento | Q-003 |
| **53.D** | O que fica aberto depois da revisão | Q-010, Q-012, Q-014, Q-015 |

## 53.A · Competências × decisões das seções 31 a 52 (Q-002)

A Q-002 pedia reabrir as Capacidades afetadas pelo que mudou depois da revisão das Competências. Conferi as 14 Competências contra as decisões D-057 a D-080, ou seja, Ações, Manobras, Movimento, Equipamentos, Resistências e Condições.

**O que precisa mudar:**

1. **Furioso usa "fim do combate" duas vezes:** na Fúria (Nível 1) e em Além da Dor (Nível 4). A D-076 trocou esse termo por "fim da Cena" em Mirando, e o sistema não define "combate". Proponho a mesma troca no Furioso.

**Conferido, sem mudança:**

- **Aparador:** usa "Maestria" desde a D-068. A faixa de Proteção dos escudos (D-073) é a mesma do Aparar.
- **Guardião:** o Escudo Pesado continua com Força mínima 3 e -1 dado ao Atacar, então o Domínio do Escudo segue válido. A lista "surpreendido, Incapacitado ou Paralisado" é coerente com a D-079.
- **Sentinela:** a frase "deslocamentos forçados ... não provocam o Ataque de Oportunidade" agora repete a definição de Movimentação (D-077). Ela não contradiz e pode ficar como lembrete.
- **Atirador:** as exceções de Mirando ("deslocado à força" e o movimento da Mira Estável) batem com a D-077 e a D-080.
- **Acrobata:** levantar-se por 1 ponto é uma exceção expressa à D-077 e continua valendo.
- **Ambidestro:** a partir do Nível 5, um escudo com Golpe de Escudo pode ser a arma secundária, porque vira uma arma de uma mão sem Leve (D-073). É coerente com a decisão da seção 45.
- **Duelista, Caçador e Mentalista:** batem com Desafiado e Lido (D-080).
- **Assassino, Cativante, Inspirador e Robusto:** não usam nada do que mudou.

**Proposta P-53.A:** trocar "no fim do combate" por "no fim da Cena" no Furioso (PT e EN) e fechar a Q-002.

## 53.B · Ordem das áreas e núcleo × módulo (Q-001, Q-005)

### Ordem das áreas (Q-001)

Hoje há três ordens diferentes:

- **Readme:** Mecânica Básica, Personagens, Competências, Criaturas, Cenas e Conflitos, Movimento, Equipamentos, Resistência e Vulnerabilidade, Condições.
- **Wiki (gerada pelo astra-engine):** Mecânica Básica, Personagens, Criação de Personagem, Cenas e Conflitos, Competências, Criaturas…
- **Índice de Cenas e Conflitos:** Cenas Táticas antes de A Cena. A wiki inverte as duas, provavelmente por ordem alfabética.

A revisão mostrou na prática uma ordem de dependência. As Competências e as Criaturas usam tudo o que vem antes, e por isso a Q-002 existiu. Proponho que o **Readme seja a ordem oficial** e siga essa dependência:

1. Mecânica Básica
2. Personagens
3. Cenas e Conflitos
4. Movimento
5. Equipamentos
6. Resistência e Vulnerabilidade
7. Condições
8. Competências
9. Criaturas

A Criação de Personagem continua em uma seção própria do Readme e na ordem de leitura recomendada, como hoje.

A ordem da wiki é definida no **astra-engine**, que é outro repositório. Esta revisão não o altera. Depois de decidida a ordem, ajustar o gerador fica como tarefa separada.

**Proposta P-53.B1:** reordenar a lista "Regras do sistema" do Readme (PT e EN) como acima e registrar que o astra-engine deve seguir essa ordem.

### Núcleo × módulo (Q-005)

Hoje não há nenhum módulo escrito. Tudo o que está em `Regras/` é núcleo. Proponho fixar só a convenção, sem criar estrutura vazia:

- tudo em `Regras/` é **núcleo**;
- cada módulo, quando existir, ganha uma pasta própria **fora de `Regras/`** (por exemplo, `Módulos/Magia/`), com a mesma organização por áreas e a mesma exigência de versão em `en/`;
- uma regra de módulo pode acrescentar ou substituir regras do núcleo, mas precisa dizer qual.

**Proposta P-53.B2:** acrescentar essa convenção ao `CLAUDE.md` e uma frase ao Readme ("Todas as regras desta página são do núcleo; os módulos ficam em pastas próprias"). Fechar a Q-005.

## 53.C · Organização de `Design/` e o Fundamento (Q-003)

### Notas já incorporadas

Várias notas de `Design/` descrevem decisões que já estão nas regras, ou que a revisão mudou depois. Uma delas contradiz o estado atual: a *Conversão de Maestrias em Propriedades* diz que "o subsistema de Maestrias foi removido", mas a D-068 trouxe a Maestria de volta como categoria de arma. Proponho mover para `Design/Arquivo/` as que já cumpriram seu papel, mantendo os subdiretórios por área:

| Nota | Destino |
|---|---|
| Manobras e Reservas | `Arquivo/` |
| Atributos e Perícias Vinculados | `Arquivo/` |
| Análise de Armas e Propriedade Pesado | `Arquivo/Equipamentos/` |
| Catálogo de Armas - Análise | `Arquivo/Equipamentos/` |
| Catálogo de Armaduras e Escudos - Análise | `Arquivo/Equipamentos/` |
| Propriedades e Maestrias - Análise | `Arquivo/Equipamentos/` |
| Conversão de Maestrias em Propriedades | `Arquivo/Equipamentos/`, com nota de que a D-068 a superou |
| Competências/Atirador (rascunho incorporado) | `Arquivo/Competências/` |
| Competências/Trunfos não convertidos em Privilégios | `Arquivo/Privilégios/` |

Continuam ativas: o Fundamento, o Acúmulo de Dados e Régua de Benefícios, a Lista inicial de Competências, o Critério de Equilíbrio de Equipamentos, as duas notas de Criaturas em análise e a pasta Revisão. Os links `[[...]]` do Obsidian procuram pelo nome, então mover as notas não quebra esses links. Vou conferir os links relativos ao aplicar.

### Fundamento das Competências

O `CLAUDE.md` manda ler o Fundamento, mas ele está desatualizado em três pontos:

1. **O aviso de "estado da reestruturação" e a seção "Transição do modelo anterior"** falam de Escaramuçador, Atirador de Guerra e Atirador Tático, que não existem. Hoje há 14 Competências. Proponho trocar a seção por uma frase que remeta à lista de Competências e tirar o aviso.
2. **Os exemplos de multiclasse** usam essas Competências inexistentes. Proponho trocá-los por Competências reais, como "Atirador 4; Atirador 2 e Acrobata 2; Atirador 1, Acrobata 1, Sentinela 1 e Mentalista 1".
3. **Faltam dois casos aprovados na revisão** (notas da Q-003):
   - Competências que só aumentam um valor, sem Capacidades nomeadas nem Ápice, como o Robusto (D-050);
   - Níveis que só aumentam valores, como o Nível 5 do Assassino (D-041).
   Proponho acrescentar os dois em **Progressão fixa**, como formatos válidos.

Também proponho atualizar **Decisões pendentes**: tirar as progressões do Arqueiro e manter a lista completa de Competências, o destino dos Trunfos, os testes de progressão e o Foundry.

**Propostas P-53.C1 (mover as notas) e P-53.C2 (atualizar o Fundamento).** Fechar a Q-003.

## 53.D · O que fica aberto depois da revisão

As questões abaixo não são problemas da revisão. São projetos novos que o autor já quer fazer, e por isso recomendo deixá-las abertas, com um gatilho claro:

- **Q-010 (Competência de cura)** e **Q-012 (outras curas de agravado de Vontade):** podem virar uma única Competência futura, que trate na Cena Tática e repare Vontade. O gatilho passa a ser a criação de novas Competências.
- **Q-014 (ficha de criatura)** e **Q-015 (lista única de Capacidades):** são o mesmo projeto, um **guia de criação de criaturas**. A Q-015 vem primeiro e mexe na estrutura das Competências, então o gatilho passa a ser esse guia, como desenho à parte.

**Proposta P-53.D:** atualizar o gatilho das quatro e registrar em `Revisão.md` que a revisão geral terminou, com um resumo do que fica aberto.

## Decisões do autor (2026-11-05)

- **53.A a 53.D:** aprovadas como propostas.
