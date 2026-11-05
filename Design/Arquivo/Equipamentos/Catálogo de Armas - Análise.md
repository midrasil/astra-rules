> [!archive] Implementado
> Este planejamento foi consolidado em [[Regras/Equipamentos/Catálogo de Armas|Catálogo de Armas]]. O arquivo permanece apenas como histórico das decisões e da régua de balanceamento.

Rascunho de trabalho. Proposta do catálogo de armas do núcleo para o compêndio de **Equipamentos**, com uma régua de balanceamento e a revisão das armas que já existem (as das Criaturas).

Legenda do status: ⬜ não analisado · 🟨 em discussão · ✅ decidido · ❌ descartado

## Régua de balanceamento ✅

O Dano da arma é somado à Margem no [Confronto](../../../Regras/Cenas%20e%20Conflitos/A%C3%A7%C3%B5es/Confrontar.md), então cada ponto pesa. A régua parte da empunhadura e desconta o que a arma ganha em troca.

| Empunhadura | Dano base | Carga |
|---|---|---|
| **Leve** | 1 | 1 |
| **Uma mão** (sem Leve) | 2 | 1 |
| **Flexível** | 2 (3 com as duas mãos) | 2 |
| **Duas mãos** | 4 | 2 |

Ajustes sobre o Dano base:
- **Alcance 2** (armas de haste): −1.
- **Arremesso** em arma de corpo a corpo: sem custo, desde que a arma seja Leve ou de uma mão.
- **Versátil** e **Manobra**: sem custo, porque são opções e não aumentam o dano.
- **Não letal**: sem ganho (o dano já é superficial).
- **Pesado:** sem ajuste de Dano; substitui Agilidade por Força nos Ataques, sem somar dados ou Dano.
- **À distância:** o Alcance é a vantagem. Armas de disparo de Duas mãos têm Dano 2 com Alcance até 12 e Dano 3 acima disso; as Leves (funda) têm Dano 1.
- **Origem Improvisada:** −1, mínimo 0.

## Revisão das armas atuais ✅

As armas das Criaturas vieram da tabela de conversão do livro (dado → Dano), sem a régua. Pela régua:

| Arma | Hoje | Problema | Proposta |
|---|---|---|---|
| Lança Curta | Dano 1, Perfurante, Arremesso 3 | ok | Leve, Arremesso 4 |
| Cimitarra | Dano 3, uma mão, sem Propriedades | dano de arma de duas mãos numa arma de uma mão | Dano 2, Versátil (Perfurante) |
| Machado de Batalha | Dano 4, uma mão | o mesmo | Flexível, Pesado, Dano 2 (3 com as duas mãos), pela régua |
| Clava Massiva | Dano 3, sem Propriedades | arma enorme sem Duas mãos | Duas mãos, Pesado, Dano 4, Manobra (Derrubar) |
| Porrete com Espinhos | Dano 3, uma mão | acima da régua | Flexível, Pesado, Dano 2 (3 com as duas mãos), Versátil (Perfurante) |
| Lança | Dano 2, Duas mãos, Alcance 2 | abaixo da régua (4 − 1 = 3) | Dano 3 |

Todas ficam sem Carga hoje (0); a proposta aplica a coluna Carga da régua.

## Armas novas ✅

### Corpo a corpo

| Arma | Dano | Tipo | Empunhadura | Alcance | Outras Propriedades | Material |
|---|---|---|---|---|---|---|
| Adaga | 1 | Perfurante | Leve | 1 | Arremesso (4), Versátil (Corte) | Metal comum |
| Espada Curta | 1 | Perfurante | Leve | 1 | Versátil (Corte) | Metal comum |
| Machadinha | 1 | Corte | Leve | 1 | Arremesso (4) | Metal comum |
| Porrete | 1 | Contusão | Leve | 1 | Não letal | Madeira |
| Espada Longa | 2 | Corte | Flexível | 1 | Versátil (Perfurante) | Metal comum |
| Maça | 2 | Contusão | Uma mão | 1 | Pesado | Metal comum |
| Martelo de Guerra | 2 | Contusão | Flexível | 1 | Pesado, Manobra (Derrubar) | Metal comum |
| Mangual | 2 | Contusão | Uma mão | 1 | Pesado, Manobra (Desarmar) | Metal comum |
| Montante | 4 | Corte | Duas mãos | 1 | Pesado | Metal comum |
| Machado Grande | 4 | Corte | Duas mãos | 1 | Pesado | Metal comum |
| Malho | 4 | Contusão | Duas mãos | 1 | Pesado, Manobra (Derrubar) | Metal comum |
| Alabarda | 3 | Corte | Duas mãos | 2 | Pesado, Versátil (Perfurante), Manobra (Derrubar) | Metal comum |
| Bordão | 2 | Contusão | Flexível | 1 | Não letal, Manobra (Derrubar) | Madeira |
| Chicote | 0 | Corte | Leve | 2 | Manobra (Desarmar) | Orgânico |

### À distância

| Arma | Dano | Tipo | Empunhadura | Alcance | Outras Propriedades | Material |
|---|---|---|---|---|---|---|
| Arco Curto | 2 | Perfurante | Duas mãos | 12 | — | Madeira |
| Arco Longo | 3 | Perfurante | Duas mãos | 20 | Pesado | Madeira |
| Besta | 3 | Perfurante | Duas mãos | 15 | — | Madeira |
| Funda | 1 | Contusão | Leve | 10 | — | Orgânico |
| Dardo | 1 | Perfurante | Leve | 1 | Arremesso (6) | Metal comum |

### Improvisada

| Arma | Dano | Tipo | Empunhadura | Alcance | Material |
|---|---|---|---|---|---|
| Arma Improvisada | 1 | Contusão | Uma mão | 1 | Madeira |

## Decisões

- **Valor:** fica em 0 no núcleo; cada cenário define os preços.
- **Besta:** igual ao arco por enquanto, sem Ação para recarregar.
- **Pesado:** Maça, Martelo de Guerra, Mangual, Montante, Machado Grande, Malho, Alabarda, Machado de Batalha, Clava Massiva, Porrete com Espinhos e Arco Longo.
- **Reservas:** armas corpo a corpo usam Agilidade + Lutar; armas de disparo usam Agilidade + Atirar; Pesado troca Agilidade por Força; Arremesso usa Força + Arremessar. Capacidades sempre prevalecem.

Uma **Arma Improvisada** recebe Pesado somente quando a massa, a alavanca ou a forma específica do objeto justificarem. Uma garrafa e uma viga, por exemplo, não precisam utilizar o mesmo Atributo de Ataque.
