# Revisão do Astra

Painel da revisão completa das regras do Astra. É o ponto de retomada: leia este arquivo, [Decisões](Decisões.md) e [Questões em aberto](Questões%20em%20aberto.md) antes de continuar.

## Objetivo

Percorrer todo o sistema, da Introdução às Condições, uma seção por vez, com revisão **textual** (clareza, terminologia), **mecânica** (coerência, abusos, lacunas, complexidade) e **estrutural** (ordem, dependências, consistência com a wiki).

## Regras de colaboração

- Nenhum arquivo de regra é alterado sem aprovação explícita do autor.
- Sugestões não são decisões. Cada proposta é aprovada ou rejeitada individualmente.
- Diferenciar **problema objetivo** de **preferência de design**.
- Considerar manter, simplificar ou remover uma regra problemática, e o impacto no restante do sistema.
- Não aproximar o Astra de outros sistemas só por aproximar. Não adicionar complexidade sem justificativa.
- Divergências entre astra-rules e astra-wiki são apresentadas antes de decidir qual prevalece.
- Não avançar de seção sem confirmação do autor.

## Fluxo de cada seção

1. Análise registrada em `Seções/NN - Nome.md`: resumo, problemas, propostas.
2. Discussão.
3. Aprovação ou rejeição de cada proposta.
4. Aplicação das aprovadas em português e em `en/`, com o hash de origem atualizado.
5. Registro em [Decisões](Decisões.md). O merge do PR da seção conta como confirmação do autor de que ela está concluída (combinado em 2026-11-02).

## Fontes

- `astra-rules`: fonte das regras.
- `astra-wiki`: site gerado do astra-rules pelo astra-engine. Não tem texto próprio. Divergências possíveis apenas na ordem de navegação.

## Progresso

Status: `[ ]` pendente · `[~]` em discussão · `[x]` concluída

**Introdução**
- [x] 00 · [Introdução](Seções/00%20-%20Introdução.md) (`Readme.md`)

**Mecânica Básica**
- [x] 01 · [Mecânica Básica (índice) + Reserva de Dados](Seções/01%20-%20Mecânica%20Básica.md)

**Personagens**
- [x] 02 · [Personagens (índice) + Atributos](Seções/02%20-%20Personagens%20e%20Atributos.md)
- [x] 03 · [Perícias](Seções/03%20-%20Perícias.md)
- [x] 04 · [Tamanho](Seções/04%20-%20Tamanho.md)
- [x] 05 · [Vida](Seções/05%20-%20Vida.md)
- [x] 06 · [Vontade](Seções/06%20-%20Vontade.md)
- [x] 07 · [Descanso Prolongado](Seções/07%20-%20Descanso%20Prolongado.md)
- [x] 08 · [Ambição e Desejo](Seções/08%20-%20Ambi%C3%A7%C3%A3o%20e%20Desejo.md)
- [x] 09 · [Convicções e Pilares](Seções/09%20-%20Convic%C3%A7%C3%B5es%20e%20Pilares.md)
- [x] 10 · [Progressão](Seções/10%20-%20Progress%C3%A3o.md)

**Competências**
- [x] 11 · [Competências (regras gerais)](Seções/11%20-%20Compet%C3%AAncias.md)
- [x] 12 · [Acrobata](Seções/12%20-%20Acrobata.md)
- [x] 13 · [Ambidestro](Seções/13%20-%20Ambidestro.md)
- [x] 14 · [Aparador](Seções/14%20-%20Aparador.md)
- [x] 15 · [Assassino](Seções/15%20-%20Assassino.md)
- [~] 16 · [Atirador](Seções/16%20-%20Atirador.md)
- [ ] 17 · Caçador
- [ ] 18 · Cativante
- [ ] 19 · Duelista
- [ ] 20 · Furioso
- [ ] 21 · Guardião
- [ ] 22 · Inspirador
- [ ] 23 · Mentalista
- [ ] 24 · Robusto
- [ ] 25 · Sentinela

**Criação de Personagem**
- [ ] 26 · Visão geral + Identidade
- [ ] 27 · Atributos e Perícias + Características Derivadas
- [ ] 28 · Competências + Equipamento Inicial

**Criaturas**
- [ ] 29 · Criaturas (índice) + Tipos de Criatura
- [ ] 30 · Características de NPC

**Cenas e Conflitos**
- [ ] 31 · Cenas e Conflitos (índice) + Cenas Táticas + A Cena
- [ ] 32 · Ação
- [ ] 33 · Confrontar
- [ ] 34 · Manobras
- [ ] 35 · Aguardar
- [ ] 36 · Zonas
- [ ] 37 · Iluminação

**Movimento**
- [ ] 38 · Movimento (índice) + Movimentação
- [ ] 39 · Correr
- [ ] 40 · Saltar

**Equipamentos**
- [ ] 41 · Equipamentos (índice, carga e Sobrecarga)
- [ ] 42 · Armas
- [ ] 43 · Catálogo de Armas
- [ ] 44 · Armaduras + Catálogo de Armaduras
- [ ] 45 · Escudos + Catálogo de Escudos
- [ ] 46 · Trocar Equipamento

**Resistência e Vulnerabilidade**
- [ ] 47 · Resistência e Vulnerabilidade (índice) + Resistência + Vulnerabilidade + Imunidade

**Condições**
- [ ] 48 · Condições (índice e regras gerais)
- [ ] 49 · Caído + Agarrado
- [ ] 50 · Debilitado + Lento + Abalado + Envenenado
- [ ] 51 · Paralisado + Atordoado + Medo
- [ ] 52 · Mirando + Lido + Desafiado

**Fechamento**
- [ ] 53 · Revisão estrutural final: ordem das áreas, índices, ordem da wiki e questões em aberto acumuladas
