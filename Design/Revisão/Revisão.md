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
- [x] 16 · [Atirador](Seções/16%20-%20Atirador.md)
- [x] 17 · [Caçador](Seções/17%20-%20Ca%C3%A7ador.md)
- [x] 18 · [Cativante](Seções/18%20-%20Cativante.md)
- [x] 19 · [Duelista](Seções/19%20-%20Duelista.md)
- [x] 20 · [Furioso](Seções/20%20-%20Furioso.md)
- [x] 21 · [Guardião](Seções/21%20-%20Guardi%C3%A3o.md)
- [x] 22 · [Inspirador](Seções/22%20-%20Inspirador.md)
- [x] 23 · [Mentalista](Seções/23%20-%20Mentalista.md)
- [x] 24 · [Robusto](Seções/24%20-%20Robusto.md)
- [x] 25 · [Sentinela](Seções/25%20-%20Sentinela.md)

**Criação de Personagem**
- [x] 26 · [Visão geral + Identidade](Seções/26%20-%20Vis%C3%A3o%20geral%20%2B%20Identidade.md)
- [x] 27 · [Atributos e Perícias + Características Derivadas](Seções/27%20-%20Atributos%20e%20Per%C3%ADcias%20%2B%20Caracter%C3%ADsticas%20Derivadas.md)
- [x] 28 · [Competências + Equipamento Inicial](Seções/28%20-%20Compet%C3%AAncias%20%2B%20Equipamento%20Inicial.md)

**Criaturas**
- [x] 29 · [Criaturas (índice) + Tipos de Criatura](Seções/29%20-%20Criaturas%20%2B%20Tipos%20de%20Criatura.md)
- [x] 30 · [Características de NPC](Seções/30%20-%20Caracter%C3%ADsticas%20de%20NPC.md)

**Cenas e Conflitos**
- [x] 31 · [Cenas e Conflitos (índice) + Cenas Táticas + A Cena](Seções/31%20-%20Cenas%20e%20Conflitos%20%2B%20Cenas%20T%C3%A1ticas%20%2B%20A%20Cena.md)
- [x] 32 · [Ação](Seções/32%20-%20A%C3%A7%C3%A3o.md)
- [x] 33 · [Confrontar](Seções/33%20-%20Confrontar.md)
- [x] 34 · [Manobras](Seções/34%20-%20Manobras.md)
- [x] 35 · [Aguardar](Seções/35%20-%20Aguardar.md)
- [x] 36 · [Zonas](Seções/36%20-%20Zonas.md)
- [x] 37 · [Iluminação](Seções/37%20-%20Ilumina%C3%A7%C3%A3o.md)

**Movimento**
- [x] 38 · [Movimento (índice) + Movimentação](Seções/38%20-%20Movimento%20%2B%20Movimenta%C3%A7%C3%A3o.md)
- [x] 39 · [Correr](Seções/39%20-%20Correr.md)
- [x] 40 · [Saltar](Seções/40%20-%20Saltar.md)

**Equipamentos**
- [x] 41 · [Equipamentos (índice, carga e Sobrecarga)](Seções/41%20-%20Equipamentos.md)
- [x] 42 · [Armas](Seções/42%20-%20Armas.md)
- [x] 43 · [Catálogo de Armas](Seções/43%20-%20Cat%C3%A1logo%20de%20Armas.md)
- [x] 44 · [Armaduras + Catálogo de Armaduras](Seções/44%20-%20Armaduras.md)
- [x] 45 · [Escudos + Catálogo de Escudos](Seções/45%20-%20Escudos.md)
- [x] 46 · [Trocar Equipamento](Seções/46%20-%20Trocar%20Equipamento.md)

**Resistência e Vulnerabilidade**
- [x] 47 · [Resistência e Vulnerabilidade (índice) + Resistência + Vulnerabilidade + Imunidade](Seções/47%20-%20Resist%C3%AAncia%20e%20Vulnerabilidade.md)

**Condições**
- [x] 48 · [Condições (índice e regras gerais)](Seções/48%20-%20Condi%C3%A7%C3%B5es.md)
- [x] 49 · [Caído + Agarrado](Seções/49%20-%20Ca%C3%ADdo%20e%20Agarrado.md)
- [x] 50 · [Debilitado + Lento + Abalado + Envenenado](Seções/50%20-%20Debilitado%2C%20Lento%2C%20Abalado%20e%20Envenenado.md)
- [x] 51 · [Paralisado + Atordoado + Medo](Seções/51%20-%20Paralisado%2C%20Atordoado%20e%20Medo.md)
- [~] 52 · [Mirando + Lido + Desafiado](Seções/52%20-%20Mirando%2C%20Lido%20e%20Desafiado.md)

**Fechamento**
- [ ] 53 · Revisão estrutural final: ordem das áreas, índices, ordem da wiki e questões em aberto acumuladas
