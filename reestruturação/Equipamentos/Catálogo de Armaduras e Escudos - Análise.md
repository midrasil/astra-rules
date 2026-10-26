> [!archive] Implementado
> Este planejamento foi consolidado em [[Regras/Equipamentos/Catálogo de Armaduras|Catálogo de Armaduras]], [[Regras/Equipamentos/Catálogo de Escudos|Catálogo de Escudos]] e [[Regras/Equipamentos/Catálogo de Armas|Catálogo de Armas]]. O arquivo permanece apenas como histórico.

Rascunho de trabalho. Regras de categoria para armaduras e escudos, a proposta do catálogo do núcleo para o compêndio de **Equipamentos** e o **Valor** de todos os equipamentos.

Legenda do status: ⬜ não analisado · 🟨 em discussão · ✅ decidido · ❌ descartado

## Regras de categoria ✅

A [Absorção](../../Regras/Equipamentos/Armaduras.md#absor%C3%A7%C3%A3o) continua como está: converte dano agravado em superficial nos Ataques. O que muda é o custo de cada armadura, pela **categoria**.

| Categoria | Absorção | Ao Esquivar | Força mínima | Carga |
|---|---|---|---|---|
| **Leve** | 1 | sem penalidade | — | 1 |
| **Média** | 2 a 3 | **-2 a -3 dados** | 2 | 2 |
| **Pesada** | 4 a 5 | **-4 a -5 dados** | 3 | 3 a 4 |

- **Esquivar:** com armadura Média ou Pesada, a Reserva de Esquivar perde dados iguais à **Absorção da armadura**. A Absorção base (pele, escamas) e as Resistências não contam.
- **Força mínima:** abaixo dela, o personagem tem **-2 de Movimentação** enquanto veste a armadura.
- Não há penalidade em Furtividade ou Atletismo: a da Esquiva já é o custo.

Os **escudos** seguem a mesma ideia, pela [Proteção](../../Regras/Equipamentos/Escudos.md#prote%C3%A7%C3%A3o):

| Categoria | Proteção | Força mínima | Carga | Outro custo |
|---|---|---|---|---|
| **Leve** | 1 | — | 1 | — |
| **Médio** | 2 | 2 | 1 | — |
| **Pesado** | 3 | 3 | 2 | -1 dado ao Atacar |

## Valor ✅

O Valor é só um número, sem nome de moeda (pense numa única moeda, como peças de ouro). Pode ter casas decimais para itens baratos.

## Armaduras ✅

| Armadura | Categoria | Absorção | Força mín. | Carga | Valor | Propriedades |
|---|---|---|---|---|---|---|
| Gibão Acolchoado | Leve | 1 | — | 1 | 5 | — |
| Armadura de Couro | Leve | 1 | — | 1 | 10 | — |
| Peles Grossas | Leve | 1 | — | 1 | 10 | — |
| Couro Batido | Leve | 1 | — | 1 | 45 | Resistência a Corte 1 |
| Camisão de Malha | Média | 2 | 2 | 2 | 50 | Vulnerabilidade a Elétrico 1 |
| Brunea de Escamas | Média | 2 | 2 | 2 | 50 | Resistência a Perfurante 1, Vulnerabilidade a Elétrico 1 |
| Placa Peitoral | Média | 3 | 2 | 2 | 400 | Vulnerabilidade a Elétrico 1 |
| Cota de Malha | Pesada | 4 | 3 | 3 | 75 | Resistência a Corte 1, Vulnerabilidade a Elétrico 1 |
| Armadura de Talas | Pesada | 4 | 3 | 4 | 200 | Vulnerabilidade a Elétrico 1 |
| Armadura Completa | Pesada | 5 | 3 | 4 | 1500 | Vulnerabilidade a Elétrico 1 |

- **Placa Peitoral** fica Média, com Absorção 3, a do Orc Líder Tribal. A **Armadura Completa** chega a 5 sem Resistências, para não passar do teto. Toda armadura de metal (Média ou Pesada) tem **Vulnerabilidade a Elétrico 1**. Armadura de Couro e Peles Grossas são as das Criaturas e já estão com Absorção 1.

## Escudos ✅

| Escudo | Categoria | Proteção | Força mín. | Carga | Valor |
|---|---|---|---|---|---|
| Broquel | Leve | 1 | — | 1 | 5 |
| Escudo | Médio | 2 | 2 | 1 | 10 |
| Escudo de Corpo | Pesado | 3 | 3 | 2 | 40 |

## Valor das armas ✅

| Arma | Valor | Arma | Valor |
|---|---|---|---|
| Adaga | 2 | Montante | 50 |
| Espada Curta | 10 | Machado Grande | 30 |
| Machadinha | 5 | Malho | 10 |
| Porrete | 0,1 | Alabarda | 20 |
| Lança Curta | 1 | Bordão | 0,2 |
| Chicote | 2 | Lança | 2 |
| Cimitarra | 25 | Arco Curto | 25 |
| Espada Longa | 15 | Arco Longo | 50 |
| Maça | 5 | Besta | 25 |
| Martelo de Guerra | 15 | Funda | 0,1 |
| Mangual | 10 | Dardo | 0,05 |
| Machado de Batalha | 10 | Arma Improvisada | 0 |
| Clava Massiva | 0,5 | Porrete com Espinhos | 1 |

## Implementação ✅

1. Armadura ganha **Categoria** (Leve, Média, Pesada) e **Força mínima**; escudo ganha **Categoria** e **Força mínima**.
2. A Reserva de **Esquivar** desconta a Absorção da armadura Média ou Pesada vestida.
3. Abaixo da Força mínima, **-2 de Movimentação**.
4. Escudo Pesado: **-1 dado ao Atacar**.
5. Catálogo novo no compêndio de Equipamentos e Valor em todas as armas, armaduras e escudos.
6. Atualizar [Armaduras](../../Regras/Equipamentos/Armaduras.md) e [Escudos](../../Regras/Equipamentos/Escudos.md) com o texto final.
