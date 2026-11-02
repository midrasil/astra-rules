# 16 · Atirador

**Arquivo:** `Regras/Competências/Atirador.md` (e `en/`), mais a linha na lista de Competências
**Relacionadas:** Mirando (Condição), Manobras (Mirar), Confrontar (Atacar Além do Alcance), Movimentação, Vontade (Romper Limite, D-028)
**Status:** concluída (PR #38, mergeado em 2026-11-02)

## O que está estabelecido

| Nível | Capacidade | Efeito |
| ---: | --- | --- |
| 1 | Postura de Tiro | Antes de atacar com Atirar, sem ter se movido no Turno: +2 dados, ignora o primeiro -2 de alcance, e não pode mais se mover no Turno. |
| 2 | Foco Imperturbável | No começo do Turno, sem nenhum acúmulo de Mirando, recebe 1 de graça. Ser deslocado à força não tira a Mira. |
| 3 | Mira Estável | Na Postura, pode se mover até metade da Movimentação base sem perder a Mira. |
| 4 | Postura de Tiro Aprimorada | Na Postura, cada ponto de dano superficial de Vontade dá 1 acúmulo de Mirando, até o limite. |
| 5 | Foco Inabalável | O acúmulo gratuito vem todo Turno, mesmo com acúmulos. O limite passa a Astúcia + Nível de Atirador. |

Mirando: +2 dados por acúmulo no próximo Ataque à distância, até Astúcia acúmulos. Os acúmulos se perdem ao usar a Movimentação depois de Mirar, ser deslocado à força, sofrer dano ou ficar Caído, e o Ataque encerra a Mira.

## Análise

### Mecânica

1. **A identidade é clara e a progressão é boa.** Cada Nível muda a forma de jogar: parar para atirar (1), começar com Mira (2), mover sem perdê-la (3), comprar Mira com Vontade (4) e manter a Mira crescendo (5). É a Competência com a progressão mais completa até aqui.
2. **O Vontade da Postura Aprimorada pode quebrar a própria Mira (problema objetivo).** Mirando se perde ao "sofrer dano", e o custo de usar Vontade é **dano** superficial de Vontade. Na leitura literal, cada ponto pago no Nível 4 dá 1 acúmulo e, ao mesmo tempo, faz perder todos. O mesmo vale para qualquer uso de Vontade antes do Ataque, como Ignorar Penalidades Físicas. A intenção clara é que só o dano na **Vida** tire a Mira.
3. **Acúmulos recebidos sem Mirar não se perdem ao mover (problema objetivo).** Mirando se perde ao "utilizar sua Movimentação **depois de Mirar**". O Foco Imperturbável e a Postura Aprimorada dão acúmulos **sem** a Manobra Mirar, então, na leitura literal, mover-se não os tira. A Mira Estável (Nível 3) só faz sentido se mover-se tirasse esses acúmulos, então a intenção é que tire.
4. **A Postura de Tiro e a Mira Estável não dizem se dá para se mover antes do Ataque (lacuna).** A Postura exige "ainda não ter se movimentado" no Turno. A Mira Estável permite mover metade da Movimentação "durante o Turno", mas não diz se o personagem pode se mover **antes** de assumir a Postura. A leitura mais coerente com o nome (andar e atirar sem perder a Mira) é que pode, antes ou depois do Ataque, desde que o total no Turno não passe de metade da Movimentação base.
5. **"Astúcia + Nível de Atirador" no Nível 5 é sempre Astúcia + 5 (simplificação).** O Foco Inabalável só existe no Nível 5, então o Nível de Atirador nessa fórmula é sempre 5.
6. **Teto de poder alto, mas pago (observação).** No Nível 5, com Astúcia 3, o limite é 8 acúmulos (+16 dados). Para chegar lá num único Ataque, o personagem paga cerca de 7 de Vontade, e com a trilha cheia isso vira Romper Limite (agravado, D-028). Sem gastar Vontade, a rotina é +4 dados por Turno (Postura e 1 acúmulo gratuito). O pico é um "tiro decisivo" caro, que combina com a fantasia. Não proponho mudança, mas é o maior bônus de dados que vi nas regras até agora, e vale lembrar dele na seção de Mentalista e de qualquer outra Competência que compre dados com Vontade.

### Texto e estrutura

7. **O texto está no formato atual e enxuto.** Só o Nível 1 abre com "Durante seu Turno, antes de realizar um Ataque..., caso ainda não tenha se movimentado, você pode assumir", que fica mais claro como "Você pode assumir uma **Postura de Tiro**...", no mesmo padrão de Aparar (D-040).
8. **Linha da lista** ("preparação, conservação da Mira, precisão e disparos a distância com a Perícia Atirar") é genérica e não diz o que a Competência faz.

## Propostas

### P-16.1 · Só dano na Vida tira a Mira (problema objetivo)

Em `Regras/Condições/Mirando.md`, trocar "sofrer dano;" por:

> sofrer dano na [Vida](../Personagens/Vida.md);

- **Por quê:** resolve o item 2 com uma palavra, sem exceção dentro do Atirador. Também cobre o uso de Vontade de qualquer personagem antes de um Ataque à distância.
- **Alternativa:** manter a Condição e escrever no Nível 4 que esse dano de Vontade não tira a Mira. Funciona só para o Atirador e deixa o caso geral em aberto.

### P-16.2 · Mover-se tira qualquer acúmulo (problema objetivo)

Em Mirando, trocar "utilizar sua Movimentação depois de Mirar;" por:

> utilizar sua Movimentação enquanto estiver Mirando;

- **Por quê:** vale para acúmulos de qualquer origem. Quem se move antes de Mirar continua sem perder nada, porque ainda não estava Mirando.
- **Observação:** P-16.1 e P-16.2 mexem numa Condição, que só seria revisada na seção 48. Proponho fazer aqui porque o Atirador depende delas. A seção 48 só confere.

### P-16.3 · Mira Estável: mover antes ou depois (lacuna)

Reescrever o Nível 3:

> Você pode assumir a Postura de Tiro mesmo depois de se movimentar, e, enquanto estiver nela, pode se movimentar. O total no Turno não pode passar de **metade da sua Movimentação base**.
>
> Esse deslocamento não provoca a perda dos seus acúmulos de [Mirando](../Condi%C3%A7%C3%B5es/Mirando.md).

- **Alternativa:** deixar claro que o movimento só vale depois do Ataque. Fica mais restrito e, para um atirador, menos útil.

### P-16.4 · Texto (simplificação)

- Nível 1 abre com "Você pode assumir uma **Postura de Tiro** antes de realizar um Ataque com Atirar, se ainda não tiver se movimentado no Turno. Ela dura até o final do Turno e, enquanto estiver nela:" (lista igual).
- Nível 5: "Astúcia + Nível de Atirador" vira **Astúcia + 5**.
- Linha da lista: "postura de tiro com bônus e alcance maior, Mira gratuita a cada Turno, mover-se sem perder a Mira e acúmulos de Mira pagos com Vontade."

## Decisões do autor (2026-11-02)

- **P-16.1:** o autor confirmou que dano de Vontade não conta como dano. Em vez de mexer só na Mirando, a regra geral foi para a Vontade: "O dano de Vontade não conta como sofrer dano: quando uma regra fala em sofrer dano sem citar a Vontade, ela se refere à Vida." Isso cobre a Mirando, a Manobra Mirar e o Foco Imperturbável sem alterar o texto deles (D-042).
- **P-16.2:** aprovada, só na Condição Mirando. A Manobra Mirar continua com "depois de Mirar", que está correto para quem ganha o bônus pela Manobra. A duplicação entre Manobras e Mirando fica para a seção de Manobras (D-042).
- **P-16.3 e P-16.4:** aprovadas (D-042).
