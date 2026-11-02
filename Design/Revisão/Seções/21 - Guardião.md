# 21 · Guardião

**Arquivo:** `Regras/Competências/Guardião.md` (e `en/`)
**Relacionadas:** Confrontar (Defender, Esquivar), Escudos, Zonas (Zonas de dano), Aparador, Incapacitado (D-023), Paralisado, Vontade (Romper Limite, D-028)
**Status:** decidida (D-047) e aplicada; aguardando o merge do PR

## O que está estabelecido

Todas as Capacidades exigem um Escudo empunhado e usam só a Proteção dele, nunca o Aparar.

| Nível | Capacidade | Efeito |
| ---: | --- | --- |
| 1 | Cobrir Aliado | Uma vez por Rodada, um aliado adjacente atacado soma a Proteção do seu Escudo ao Defender (mesmo sem Escudo) ou ao Esquivar. Não soma com o Escudo dele: vale a maior Proteção. Você decide antes da resposta, e o uso se perde se ele Aceitar o Confronto. |
| 2 | Domínio do Escudo | Força mínima do Escudo -1 e sem o -1 dado ao Atacar do Escudo Pesado. |
| 3 | Interpor-se | 1 superficial de Vontade: troca de lugar com o aliado adjacente atacado e vira o alvo, respondendo com Defender. Cobrir Aliado pode ser usado de novo na Rodada por 1 superficial de Vontade a cada uso. |
| 4 | Abrigo | Proteção do Escudo no teste contra Zona de dano, para você ou para um aliado adjacente. |
| 5 | Bastião | Ao Defender com a Proteção do seu Escudo, você vence o empate. Vale também para o aliado coberto. |

## Análise

### Mecânica

1. **A Competência está bem resolvida.** O papel é claro (proteger o aliado ao lado), cada Nível acrescenta uma forma de fazer isso, e o Nível 5 é um Ápice que muda a regra do empate. O texto já é preciso sobre o momento da decisão e sobre Proteções que não se somam.
2. **Custo de Vontade (acompanhamento da D-028).**
   - Interpor-se não tem limite por Rodada; cada uso custa 1 superficial.
   - Os usos extras de Cobrir Aliado também custam 1 superficial cada.
   - Com a trilha cheia, cada uso vira Romper Limite (agravado). O Guardião pode continuar protegendo sem limite, mas paga com dano que demora sessões para curar.
   - O preço é alto e combina com a fantasia de quem se sacrifica pelo grupo. **Não proponho mudança.**
3. **A restrição de "surpreendido, incapacitado ou Paralisado" só vale para o Cobrir Aliado (lacuna).** O Interpor-se também é uma reação fora do seu Turno, e pela mesma lógica não deveria ser possível nessas situações. Hoje o texto não impede.
4. **"Incapacitado" sem a Condição (problema objetivo).** Igual ao Furioso (D-046): desde a D-023, Incapacitado é uma Condição, e o texto o escreve em minúsculas e sem link.
5. **Domínio do Escudo é o Nível mais fraco (observação).** Reduz a Força mínima em 1 e tira o -1 do Escudo Pesado. Na prática, permite usar um Escudo Pesado com Força 2 sem perder Movimentação e sem penalidade ao atacar. É útil, mas pequeno ao lado dos outros Níveis. A comparação entre armas grandes com Aparador e Escudos (Q-013) fica para as seções 42 e 45.

### Texto e estrutura

6. **O texto está no formato atual e enxuto.** A linha da lista também está boa.

## Propostas

### P-21.1 · Restrição para as duas reações (lacuna e problema objetivo)

Tirar a frase do fim do Cobrir Aliado e pôr na introdução, depois da exigência de Escudo:

> Você não pode usar [Cobrir Aliado](#n%C3%ADvel-1--cobrir-aliado) nem [Interpor-se](#n%C3%ADvel-3--interpor-se) enquanto estiver surpreendido, [Incapacitado](../Condi%C3%A7%C3%B5es/Incapacitado.md) ou [Paralisado](../Condi%C3%A7%C3%B5es/Paralisado.md).

- **Por quê:** fecha a lacuna do Interpor-se e usa a Condição Incapacitado, numa frase só.
- **Alternativa:** deixar a frase no Cobrir Aliado e repetir no Interpor-se.

## Decisões do autor (2026-11-02)

- **P-21.1:** aprovada (D-047). O custo de Vontade do Guardião foi reavaliado (acompanhamento da D-028) e fica como está.
