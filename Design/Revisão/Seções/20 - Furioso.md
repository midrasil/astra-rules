# 20 · Furioso

**Arquivo:** `Regras/Competências/Furioso.md` (e `en/`), mais a linha na lista de Competências
**Relacionadas:** Vida (gravidade padrão e trilha preenchida), Vontade (Romper Limite, D-028; dano de Vontade, D-042), Debilitado, Incapacitado (D-023), Medo, Correr, Movimentação, Confrontar (Atributos de Ataque)
**Status:** decidida (D-046) e aplicada; aguardando o merge do PR

## O que está estabelecido

| Nível | Capacidade | Efeito |
| ---: | --- | --- |
| 1 | Fúria | 1 superficial de Vontade, sem Ação. Dura até o fim do próximo Turno e se prolonga a cada Confronto iniciado com Ataque corpo a corpo ou arremessado. Força no lugar do Atributo em Ataques corpo a corpo, +2 dados ao iniciar Confronto corpo a corpo, -2 ao Defender e Esquivar. |
| 2 | Sangue por Sangue | Na Fúria, o Dano da arma corpo a corpo ganha +1 por superficial e +2 por agravado na trilha de Vida, inclusive no empate. Não vale no revide. |
| 3 | Investida Furiosa | Na Fúria, +2 de Movimentação base. Ao entrar em Fúria, efeito de Correr sem gastar Ação. |
| 4 | Além da Dor | Na Fúria, ignora Debilitado e não recebe Medo. Ao entrar, perde os acúmulos de Medo. |
| 5 | Recusar a Queda | Na Fúria, a trilha de Vida toda agravada não incapacita. Cada Turno nessa situação custa 1 agravado de Vontade, e cada dano na Vida também. Fica incapacitado ao recusar o custo, com a Vontade toda agravada ou quando a Fúria acaba. |

## Análise

### Mecânica

1. **A identidade é forte e a progressão é boa.** Cada Nível acrescenta uma camada ao mesmo estado (Fúria), e o Nível 5 é um Ápice dramático, pago com Vontade agravada.
2. **Sangue por Sangue ficou muito mais forte depois da seção 05 (problema de equilíbrio).**
   - A regra dá +2 por ponto **agravado** na trilha de Vida. Ela foi escrita quando o dano superficial era o mais comum.
   - Desde a seção 05, **todo dano é agravado por padrão**. Quase todo ferimento que o Furioso sofre vale +2.
   - Exemplo: Vigor 3 dá Vida 6. Depois de dois golpes de 2, o Furioso tem 4 agravados e soma **+8 ao Dano da arma**. Se o inimigo tiver uma trilha de Vida do mesmo tamanho (3 + Vigor), um golpe desses o derruba. As regras de Criaturas não definem a Vida dos NPCs, então a comparação usa a regra dos personagens.
   - No Nível 5, com a Vida toda agravada, o bônus chega a +12 ou mais.
   - Vale também no empate, que normalmente causa só o Dano da arma.
3. **O custo de Vontade está bom (acompanhamento da D-028).** A Fúria custa 1 superficial por ativação, normalmente uma vez por combate, já que ela se prolonga sozinha enquanto o Furioso ataca. Com a trilha cheia, a ativação vira Romper Limite (agravado), o que combina com a fantasia. Não proponho mudança.
4. **Recusar a Queda não usa a Condição Incapacitado (problema objetivo).** O texto diz "incapacitado" em minúsculas e sem link, mas desde a D-023 Incapacitado é uma Condição com regras próprias (Caído, sem Ações, alvo sem resposta).
5. **Recusar a Queda e dano extra (observação).** Para um personagem Incapacitado que continua sofrendo dano, o destino fica a critério do Narrador. Com Recusar a Queda, o Furioso não está Incapacitado, então esse critério não se aplica. O preço passa a ser o agravado de Vontade por instância. É coerente e não proponho mudança.
6. **A Fúria em ataques arremessados (observação).** Um Ataque arremessado prolonga a Fúria, mas o +2 e o Sangue por Sangue só valem corpo a corpo. Parece intencional: o arremesso mantém a Fúria sem se beneficiar dela.

### Texto e estrutura

7. **"Fúria não é uma Condição do núcleo: suas regras são definidas somente nesta Competência."** É uma nota de design. Para o leitor, basta dizer que a Fúria é um estado desta Competência.
8. **Redundâncias:**
   - Na Investida Furiosa, "O aumento de Movimentação também vale para esse Correr" repete a regra geral: um aumento da Movimentação base vale para todas as regras que a usam, inclusive Correr.
   - Em Além da Dor, "Quando a Fúria termina, efeitos que voltariam a aplicar Medo funcionam normalmente a partir desse momento" repete o que "enquanto estiver em Fúria" já diz.
9. **A linha da lista** não cita a mobilidade, a imunidade ao Medo nem o Ápice.

## Propostas

### P-20.1 · Bônus do Sangue por Sangue (equilíbrio; decisão do autor)

- **(a) +1 por ponto de dano na trilha de Vida, qualquer que seja a gravidade.** Com o exemplo acima, +4 em vez de +8. Fica uma regra só, sem distinguir gravidade, e ainda cresce com os ferimentos.
- **(b) Manter +1 e +2.** O Furioso fica muito letal, mas paga com a própria Vida.
- **(c) Limitar o bônus ao Nível de Furioso.** Controla o pico, mas é mais uma regra para acompanhar.

**Recomendo (a).** É mais simples que a regra atual e devolve o equilíbrio que ela tinha antes da mudança de gravidade.

### P-20.2 · Incapacitado em Recusar a Queda (problema objetivo)

Trocar "não deixa você incapacitado imediatamente" por "não deixa você [Incapacitado]", e "Você fica incapacitado quando" por "Você fica [Incapacitado] quando", com link para a Condição.

### P-20.3 · Texto (simplificação)

- Introdução: "A **Fúria** é um estado desta Competência, não uma Condição."
- Tirar a frase redundante da Investida Furiosa.
- Em Além da Dor, deixar só "Os acúmulos perdidos ao entrar em Fúria não retornam quando ela termina."
- Linha da lista: "Fúria, agressão corpo a corpo, dano que cresce com os ferimentos, avanço rápido, imunidade ao Medo e recusa em cair."

## Decisões do autor (2026-11-02)

- **P-20.1:** opção (b), o Sangue por Sangue mantém +1 por superficial e +2 por agravado (D-046).
- **P-20.2 e P-20.3:** aprovadas (D-046).
