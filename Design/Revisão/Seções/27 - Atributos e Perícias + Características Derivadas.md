# 27 · Atributos e Perícias + Características Derivadas

**Arquivos:** `Criação de Personagem/2 - Atributos e Perícias.md` e `Criação de Personagem/3 - Características Derivadas.md` (e `en/`), mais a linha da visão geral
**Relacionadas:** Atributos (seção 02), Perícias (seção 03; Idiomas e Conhecimento Específico), Vida, Vontade, Progressão (seção 10), Robusto (D-050), Assassino (Iniciativa), A Cena (Iniciativa), Equipamentos (Carga), Q-004
**Status:** decidida (D-053) e aplicada; aguardando o merge do PR

## O que está estabelecido

- **Atributos:** seis, de 1 a 5. Na criação, distribua os valores 4, 3, 3, 2, 2 e 1. Nenhum passa de 4; o 5 só vem com XP.
- **Perícias:** 24 no núcleo, de 0 a 5, todas começam em 0. Escolha um perfil:

| Perfil | Valores | Perícias com pontos | Soma dos valores | Custo equivalente em XP |
| --- | --- | ---: | ---: | ---: |
| Generalista | uma em 3, seis em 2, sete em 1 | 14 | 22 | 93 |
| Equilibrado | duas em 3, quatro em 2, cinco em 1 | 11 | 19 | 87 |
| Especialista | uma em 4, duas em 3, duas em 2, duas em 1 | 7 | 16 | 90 |

  O custo equivalente usa a tabela da Progressão (novo nível × 3 XP): chegar a 1 custa 3, a 2 custa 9, a 3 custa 18 e a 4 custa 30.

- **Características Derivadas:** Vida 3 + Vigor, Vontade 3 + Determinação, Iniciativa Astúcia + Determinação, Carga máxima 5 + Força. Capacidades podem substituir o Atributo de uma fórmula, só nela. Quando o Atributo aumenta, o valor é recalculado.

## Análise

### Mecânica

1. **O array de Atributos funciona.** Seis valores fixos, soma 15, com um ponto forte (4) e uma fraqueza (1). É rápido e evita personagens desequilibrados. Não proponho mudança na mecânica.
2. **Os perfis de Perícias estão quase equilibrados (preferência de design).**
   - Em pontos, os perfis parecem muito diferentes (22, 19 e 16). Em XP, que é como as Perícias custam depois, ficam próximos: 93, 87 e 90.
   - O Equilibrado é o mais barato, 6 XP abaixo do Generalista (cerca de 3 sessões no ritmo sugerido).
   - Com uma mudança pequena, os três valem exatamente **90 XP**: o Generalista passa a ter **seis** Perícias em 1 (em vez de sete), e o Equilibrado, **seis** (em vez de cinco). Assim o perfil vira só uma escolha de formato, sem um ser mais vantajoso que o outro.
   - A diferença atual é pequena, então manter também é razoável.
3. **Conhecimento Específico e Idiomas não aparecem na criação (lacuna).**
   - A página de Perícias diz que o Conhecimento Específico "segue as mesmas regras de distribuição e de custo das demais Perícias", ou seja, pode receber pontos do perfil. Mas a Criação de Personagem fala em "24 Perícias" e não o menciona, e o jogador não sabe que pode escolher um.
   - Os Idiomas vêm de Erudição (um por Nível) e precisam ser escolhidos na criação. A página também não os cita.
4. **Novos espaços na trilha (lacuna pequena).** O Robusto diz que os novos espaços entram vazios. Quando o Vigor ou a Determinação aumentam, a Vida ou a Vontade crescem, mas a página não diz como entram os novos espaços. A leitura natural é a mesma do Robusto (vazios); uma palavra resolve.
5. **Trilha que diminui (observação).** Uma substituição pode reduzir a trilha (por exemplo, Vida com um Atributo menor que o Vigor). As regras não dizem o que acontece com o dano que não cabe. Hoje nenhuma Capacidade substitui o Atributo da Vida ou da Vontade (a única substituição em fórmula é a Iniciativa do Assassino), então não proponho regra agora. Fica anotado para quando uma Capacidade assim for criada.

### Texto e estrutura

6. **"Array fixo" (Q-004).** É um anglicismo. Proposta: "Distribua os valores abaixo" na página, e "valores fixos" na linha da visão geral. "Perfis" é português e claro, pode ficar.
7. **A lista de exemplos das 24 Perícias é arbitrária.** "Incluindo Acrobacia, Arremessar, Conhecimento Geral e Consertar" são simplesmente as primeiras em ordem alfabética (exceto Atirar e Atletismo) e não ajudam a entender nada. Parece sobra de uma versão antiga. O link para a lista basta.
8. **Os tetos são repetidos.** "Nenhum Atributo pode passar de 4" e "O teto na criação também é 4" descrevem algo que o array e os perfis já garantem. A informação útil é que o 5 só vem com XP. Uma frase só, no fim, cobre os dois.
9. **"perícias" em minúscula** na lista de perfis e na última frase, enquanto o resto do sistema escreve Perícia com maiúscula.
10. **A última frase das Características Derivadas é vaga.** "Capacidades sempre prevalecem sobre as fórmulas padrão e sobre outras regras anteriores que estabeleçam seus Atributos." A segunda parte não diz quais são essas regras. A primeira parte já basta.
11. **"Slots" na Carga.** É outro anglicismo, mas é o termo de Equipamentos. Fica para a seção de Equipamentos, onde ele é definido.
12. **A substituição nas fórmulas aparece em quatro lugares** (Atributos, Progressão, Vida/Vontade e aqui). Os textos concordam e são curtos, e a Progressão já aponta para esta página. Não proponho mudança.

## Propostas

### P-27.1 · "Array fixo" (Q-004)

- Atributos e Perícias: "Distribua o array fixo abaixo, escolhendo **onde cada valor entra**:" vira "Distribua os valores abaixo entre os seis Atributos, escolhendo **onde cada um entra**:".
- Visão geral: "Atributos (array fixo) e Perícias (perfis)" vira "Atributos (valores fixos) e Perícias (perfis)".
- **Fecha a Q-004.**

### P-27.2 · Texto de Atributos e Perícias

- Tirar "Nenhum Atributo pode passar de **4** durante a criação — o valor **5** só é alcançado com XP." e "O teto na criação também é **4**."
- Tirar "incluindo **Acrobacia**, **Arremessar**, **Conhecimento Geral** e **Consertar**". A frase fica: "O núcleo possui **24 Perícias**. Comece com todas em **0** e escolha **um** dos três perfis:".
- "perícia(s)" com maiúscula nos perfis e na última frase.
- Última frase da seção Perícias:

> As Perícias que não receberem pontos permanecem em **0**. Os pontos também podem ir para um [Conhecimento Específico](../Regras/Personagens/Per%C3%ADcias.md#conhecimento-espec%C3%ADfico), e cada Nível em Erudição dá um [idioma](../Regras/Personagens/Per%C3%ADcias.md#idiomas) adicional.

- No fim da página, antes do rodapé, uma seção curta:

> ## Teto na criação
>
> Na criação, nenhum Atributo ou Perícia passa de **4**. O valor **5** só é alcançado com [XP](../Regras/Personagens/Progress%C3%A3o.md).

- **Alternativa:** manter os dois tetos onde estão e só tirar a lista de exemplos.

### P-27.3 · Perfis com o mesmo valor (preferência de design)

- **(a) Igualar em 90 XP:** Generalista com **seis** Perícias em 1; Equilibrado com **seis** em 1.
- **(b) Manter como está.** A diferença é de no máximo 6 XP.

**Recomendo (a).** Muda só um número em cada perfil e tira a dúvida de qual perfil rende mais. Mas é preferência sua: se o Generalista ganhar um pouco mais for intencional (amplitude compensando a falta de foco), (b) também está certo.

### P-27.4 · Características Derivadas (texto)

- "Quando o Atributo que atualmente compõe uma característica derivada aumentar, o valor é recalculado imediatamente." vira "Quando o Atributo que atualmente compõe uma característica derivada aumentar, o valor é recalculado imediatamente, e os novos espaços de Vida ou Vontade entram vazios."
- "Capacidades sempre prevalecem sobre as fórmulas padrão e sobre outras regras anteriores que estabeleçam seus Atributos." vira "Capacidades sempre prevalecem sobre as fórmulas padrão."

## Decisões do autor (2026-11-02)

- **P-27.1, P-27.2 e P-27.4:** aprovadas (D-053). A Q-004 está resolvida.
- **P-27.3:** opção (a). Os três perfis valem 90 XP: Generalista e Equilibrado passam a ter seis Perícias em 1 (D-053).
- A trilha que diminui (item 5) e os "slots" da Carga (item 11) ficam anotados, sem mudança agora.
