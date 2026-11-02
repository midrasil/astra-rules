# 13 · Ambidestro

**Arquivo:** `Regras/Competências/Ambidestro.md` (e `en/`), mais a linha na lista de Competências
**Relacionadas:** Confrontar (Combate com Duas Armas, Esquivar, Aceitar o Confronto), Aparador, Armas, Catálogo de Armas
**Status:** decidida (D-039) e aplicada; aguardando o merge do PR

## O que está estabelecido

**Requisito:** uma arma corpo a corpo em cada mão. A secundária precisa ser Leve e alcançar o alvo.

| Nível | Capacidade | Efeito |
| ---: | --- | --- |
| 1 | Golpe Duplo | Ao atacar corpo a corpo ou Aceitar o Confronto, soma o Dano da arma secundária em dados. O dano é o da principal. |
| 2 | Guarda Cruzada | Ao Esquivar ou Aparar um Ataque corpo a corpo, também soma o Dano da secundária em dados. |
| 3 | Ambidestria | A secundária pode ser qualquer arma corpo a corpo de uma mão, não só Leve. |

## Análise

### Mecânica

1. **A progressão funciona.**
   - Todas as armas Leves do catálogo têm Dano 1 (o Chicote, 0), então os Níveis 1 e 2 dão +1 dado.
   - No Nível 3, uma arma de uma mão com Dano 2 (Cimitarra, Maça, Mangual) passa a dar +2.
   - O ganho cresce sem acumular bônus em cima da mesma coisa: primeiro no ataque, depois na defesa, depois na escolha da arma.
2. **A dependência do Aparador está certa.** Guarda Cruzada fala em "Aparar", que só existe com o Aparador. Sem ele, o Nível 2 vale só ao Esquivar. É uma combinação entre Competências, prevista no Fundamento.
3. **"Alcançar o alvo" não serve para a defesa (lacuna pequena).** O requisito fala do alvo, mas, quando o personagem Esquiva ou Apara, o alvo é ele mesmo. A leitura natural é que a secundária precisa alcançar o **oponente** do Confronto. Exemplo: contra uma Lança (Alcance 2), uma adaga na outra mão (Alcance 1) não soma.
4. **Arma Flexível na outra mão (lacuna pequena).** No Nível 3, uma Espada Longa (Flexível) conta como "arma de uma mão"? Ela pode ser usada com uma mão, então a leitura natural é que sim, sem o +1 de Dano de duas mãos. Vale uma frase, porque o Dano usado na Reserva depende disso.
5. **O Ápice é modesto (observação).**
   - O Nível 3 amplia as armas permitidas e vale, na prática, +1 dado.
   - O Fundamento pede um "Ápice reconhecível", mas permite Competências curtas que condensam funções. Ambidestria é coerente com o tema.
   - Não proponho mudança. Fica para você avaliar se quer algo mais marcante no Nível 3.

### Texto

6. **Linha da lista (P-11.3).** Hoje: "lutar com uma arma em cada mão, somando o Dano da arma secundária em dados ao Atacar, ao Esquivar e ao Aparar". Está correta, mas não cita o Nível 3.

## Propostas

### P-13.1 · "Alcançar o oponente" (lacuna pequena)

No requisito, trocar "alcançar o alvo" por "alcançar o oponente do Confronto".

### P-13.2 · Arma Flexível (lacuna pequena)

No Nível 3, acrescentar: "Uma arma Flexível conta como arma de uma mão e usa seu Dano de uma mão."

### P-13.3 · Linha da lista

Acrescentar ", e no Nível 3 qualquer arma de uma mão como secundária".

## Decisões do autor (2026-11-02)

- **P-13.1:** aprovada. O alcance é exigido só ao atacar ou Aceitar o Confronto (D-039).
- **P-13.2:** aprovada. A arma Flexível só vale como secundária no Nível 3 (D-039).
- **P-13.3:** aprovada (D-039).
