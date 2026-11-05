# 51 · Paralisado + Atordoado + Medo

**Arquivos:** `Regras/Condições/Paralisado.md`, `Atordoado.md`, `Medo.md`, `Condições.md` e `en/`; ajustes pontuais em Confrontar (Alvo sem Resposta) e em Características de NPC (Voadora)
**Relacionadas:** Características de NPC (Paralisante, Atordoante, Aterrorizante, Voadora), Confrontar, Furioso, Guardião, Sentinela, Condições (Regras gerais, D-076), Agarrado (D-077)
**Pendências que chegam aqui:** nenhuma
**Status:** concluída (PR #73, mergeado em 2026-11-05)

## O que está estabelecido

- **Paralisado:** sem Ação e sem Movimentação; quem o ataca usa a regra de alvo sem resposta (1 Sucesso). Dura 1 Turno, seguido de 1 Turno de imunidade.
- **Atordoado:** sem Ação, mas com Movimentação. Dura 1 Turno, seguido de 1 Turno de imunidade.
- **Medo:** acumulável, -1 dado em todas as Reservas por acúmulo; perde 1 no fim de cada Turno do afetado. O Furioso em Fúria é imune.
- Paralisado e Atordoado são aplicados pelas características Paralisante e Atordoante, e o Medo pela Aterrorizante.

## Análise

1. **Aplicação no próprio Turno do afetado.** A regra geral da D-076 diz que a duração em Turnos conta os Turnos do afetado e termina no fim do último deles. Há um caso que ela não cobre. Uma criatura Paralisante pode vencer um Ataque **durante o Turno do alvo**: o alvo ataca, a criatura Aceita o Confronto e vence. Se esse Turno contar como o "1 Turno", a paralisia dura só o resto de um Turno em que o alvo já agiu, e não tem efeito. Proponho acrescentar à regra geral: **se a Condição for aplicada durante o Turno do afetado, esse Turno não conta**. Isso vale para todas as durações em Turnos (Envenenado, Paralisado, Atordoado e as imunidades).
2. **Paralisado não está na lista do alvo sem resposta.** A Condição remete à regra, mas a regra de Confrontar lista apenas "surpreendido, inconsciente, Incapacitado ou sem nenhuma resposta válida". Proponho acrescentar Paralisado à lista e escrever na Condição, como em Incapacitado, que o personagem **não pode responder a Confrontos**.
3. **Atordoado e as respostas.** O Atordoado perde a Ação, mas o texto não diz se ele ainda responde a Confrontos. Responder não usa a Ação. Proponho escrever que **ele responde normalmente**. Isso mantém a diferença: o Atordoado perde a iniciativa, e o Paralisado fica indefeso.
4. **Fonte única.** Paralisado e Atordoado dizem "é aplicada pela característica...", o mesmo problema que o Envenenado tinha (D-078). Proponho o formato "pode ser aplicado por características de NPC, Capacidades ou outros efeitos; por exemplo, pela Paralisante".
5. **Voadora e Paralisado.** Uma criatura Voadora cai se ficar Caída ou Agarrada no ar. Não faz sentido que uma criatura Paralisada continue voando. Proponho acrescentar Paralisado à Voadora.

### Conferido, sem mudança

- **Imunidade:** com a regra do item 1, a imunidade garante que o personagem tenha pelo menos um Turno para agir antes de ser paralisado ou atordoado de novo. Uma imunidade não bloqueia a outra Condição.
- **Medo sem limite de acúmulos:** várias fontes de Aterrorizante se somam sem teto. Com a perda de 1 por Turno e a Potência padrão 2, o acúmulo prático é pequeno. Um limite seria complexidade sem necessidade.
- **Medo e a Vontade:** Ignorar Penalidades Físicas não cobre o Medo, porque ele é mental. Isso é coerente.
- **Paralisado e o agarrão:** quem agarra e fica Paralisado solta o alvo (D-077).
- **Guardião e Sentinela:** já listam Paralisado entre os estados que bloqueiam as Capacidades. O Atordoado não bloqueia, o que é coerente com o item 3.

## Propostas

### P-51.1 · Regras gerais (Condições, item Turnos)

> - **Turnos:** uma duração em Turnos conta os Turnos do personagem afetado. A Condição termina no fim do último desses Turnos. Se for aplicada durante o Turno do afetado, esse Turno não conta.

### P-51.2 · Paralisado

> Um personagem **Paralisado** não pode usar sua **Ação** nem sua **Movimentação** e não pode responder a Confrontos: é um [alvo sem resposta](...).
>
> Paralisado pode ser aplicado por características de NPC, Capacidades ou outros efeitos que façam referência a esta Condição, como a característica **Paralisante**.

Em Confrontar, a lista do Alvo sem Resposta passa a incluir [Paralisado](...).

### P-51.3 · Atordoado

> Um personagem **Atordoado** não pode usar sua **Ação**, mas ainda pode usar sua Movimentação e responder a Confrontos.
>
> Atordoado pode ser aplicado por características de NPC, Capacidades ou outros efeitos que façam referência a esta Condição, como a característica **Atordoante**.

### P-51.4 · Voadora

"Se ficar Caída ou Agarrada no ar, cai." → "Se ficar Caída, Agarrada ou Paralisada no ar, cai."

## Decisões do autor (2026-11-05)

- **P-51.1 a P-51.4:** aprovadas como propostas.
