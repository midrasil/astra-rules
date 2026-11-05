# 48 · Condições (índice e regras gerais)

**Arquivos:** `Regras/Condições/Condições.md` e `en/`; ajustes pontuais em Mirando, Atordoado, Paralisado, Envenenado e Desafiado
**Relacionadas:** Manobras, Características de NPC (Venenosa, Paralisante, Atordoante, Aterrorizante), Vida, Vontade (D-056)
**Pendências que chegam aqui:** Q-011 (parte das Condições); Q-017 segue para a seção 49 (Agarrado)
**Status:** em análise

## O que está estabelecido

O índice tem uma introdução de duas frases, a lista das 13 Condições e uma seção "Relações". Não há nenhuma regra geral: cada Condição define sozinha quanto dura e o que acontece se for aplicada de novo.

| Condição | Duração | Reaplicar |
|---|---|---|
| Caído | até se levantar (metade da Movimentação) | não se aplica |
| Agarrado | até escapar ou ser solto | não se aplica |
| Debilitado, Incapacitado | enquanto durar o estado da trilha de Vida | não se aplica |
| Lento | até o começo do próximo Turno de quem aplicou | não acumula, renova |
| Abalado | até o próximo Ataque ou o começo do próximo Turno de quem aplicou | não acumula, renova |
| Envenenado | Turnos iguais à Potência | **não diz** |
| Paralisado, Atordoado | "1 Turno", depois 1 Turno de imunidade | imune durante a imunidade |
| Medo | acumulável; perde 1 no fim de cada Turno do afetado | acumula |
| Mirando | até atacar, ser interrompido ou "**no fim do combate**" | acumula até a Astúcia |
| Lido, Desafiado | fim da Cena | não diz (pertence a quem aplicou) |

## Análise

1. **"N Turnos" não diz de quem.** Paralisado e Atordoado duram "1 Turno", e Envenenado dura "Turnos iguais à Potência". Fica a dúvida: é o Turno do afetado ou de quem aplicou? Quando começa a contar? Se a criatura paralisa no próprio Turno e a contagem é "1 Turno do afetado", o alvo perde exatamente o seu próximo Turno, que é a leitura esperada. Proponho uma regra geral: **"N Turnos" conta os Turnos do personagem afetado, e a Condição termina no fim do N-ésimo Turno dele.**
2. **Reaplicação sem regra geral.** Lento e Abalado repetem a mesma frase, e Envenenado não diz nada. Isso levanta a dúvida se dois venenos somam -4 dados. Proponho uma regra geral: **uma Condição aplicada de novo não acumula, só renova a duração, salvo quando ela se disser acumulável** (Medo, Mirando). Com isso, as frases em Lento e Abalado podem ficar como lembrete ou sair.
3. **Duas fontes com durações diferentes.** Um veneno de Potência 2 e depois um de Potência 4: vale a maior? A regra do item 2 resolve se "renovar" for entendido como **ficar com a duração que termina por último**. Proponho escrever isso explicitamente.
4. **Duração padrão.** Uma Condição sem duração definida, como uma aplicada por Capacidade nova, fica sem fim. Proponho: **salvo indicação, uma Condição termina no fim da Cena**. As Condições ligadas à trilha de Vida (Debilitado, Incapacitado) e as que têm saída própria (Caído, Agarrado) seguem as próprias regras.
5. **"Fim do combate" em Mirando.** É o único lugar que usa esse termo. O resto do sistema fala em Cena. Proponho trocar por "fim da Cena".
6. **Desafiado tem um título `# Desafiado`** no corpo, e as outras Condições não têm. É só formatação: proponho tirar o título, para padronizar com as demais.
7. **Q-011, parte das Condições.** A Q-011 pergunta se alguma Condição deveria causar dano de Vontade. Recomendo que nenhuma cause. O Medo já é o efeito mental de pressão em combate (D-056), e o dano de Vontade fica com as regras de Vontade e com a decisão do Narrador. Criar uma Condição para isso acrescenta complexidade sem uma necessidade que apareceu na revisão. Proponho fechar a Q-011.
8. **Nova Condição: Sangrando (pedido do autor, 2026-11-05).** É uma Condição acumulável, como o Medo: causa dano superficial igual aos acúmulos e perde 1 acúmulo a cada Turno. Por isso, a duração total é curta e o dano total é 1+2+…+N (3 acúmulos dão 6 de dano em três Turnos). Três pontos de encaixe:
   - **Quando conta:** proponho o fim do Turno do afetado, igual ao Medo, e não "a cada Rodada", porque o sistema conta as Condições por Turno.
   - **Absorção e Tipo:** o dano é superficial, e a Absorção só converte dano agravado, então ela não interage com o Sangrando. Proponho dizer que o Sangrando não tem Tipo de Dano, para que Resistências e Vulnerabilidades não se apliquem.
   - **Trilha cheia:** pela regra de Vida, cada ponto a mais com a trilha cheia converte superficial em agravado. Assim, o Sangrando pode piorar um personagem Debilitado, o que é coerente com sangrar.
   - **Estancar (opcional):** proponho que um aliado, ou o próprio personagem, use a Ação e teste Astúcia + Curar. Cada Sucesso remove 1 acúmulo (ajuste do autor). Isso dá uma resposta ativa sem precisar de regra nova de Tratamento.
   - Nenhuma regra aplica o Sangrando ainda. As fontes, como uma Maestria, uma característica de NPC ou uma Capacidade, ficam para quando forem criadas.
9. **Agrupar a lista do índice.** Considerei agrupar as 13 Condições por tipo (movimento, Vida, controle, mental, marcadores). Não recomendo: a lista é curta, e as descrições de uma linha já bastam. Fica registrado como opção.

### Conferido, sem mudança

- **Imunidade de Paralisado e Atordoado:** uma é independente da outra. Um alvo que acabou de sair de Paralisado pode ficar Atordoado. É coerente, porque são efeitos diferentes. Com a regra do item 1, "imune por 1 Turno" também passa a ser o próximo Turno do afetado.
- **Condições que pertencem a quem aplicou** (Lido, Desafiado): estão claras em cada arquivo.

## Propostas

### P-48.1 · Seção "Regras gerais" no índice (depois da introdução)

> ## Regras gerais
>
> - **Duração:** salvo indicação, uma Condição termina no fim da Cena. As Condições ligadas à trilha de Vida e as que têm forma própria de terminar, como Caído e Agarrado, seguem as próprias regras.
> - **Turnos:** uma duração em Turnos conta os Turnos do personagem afetado. A Condição termina no fim do último desses Turnos.
> - **Aplicar de novo:** uma Condição que o personagem já tem não acumula. Ela só renova a duração, e fica valendo a duração que terminar por último. As Condições **acumuláveis**, como Medo e Mirando, dizem como acumulam.

### P-48.2 · Mirando

"A Condição também termina no fim do combate." → "A Condição também termina no fim da Cena."

### P-48.3 · Desafiado

Tirar o título `# Desafiado` do corpo do arquivo (PT e EN).

### P-48.5 · Nova Condição Sangrando (`Regras/Condições/Sangrando.md`, EN *Bleeding*)

> **Sangrando** é uma Condição acumulável. No **fim de cada Turno** do personagem afetado, ele sofre **dano superficial igual ao número de acúmulos** e depois perde 1 acúmulo.
>
> Esse dano não tem Tipo de Dano: Absorção, Resistências e Vulnerabilidades não se aplicam a ele.
>
> **Estancar:** um personagem adjacente, ou o próprio afetado, pode usar sua Ação e testar **Astúcia + Curar**. Cada Sucesso remove **1 acúmulo**.

Entra também na lista do índice: "[Sangrando](Sangrando.md) — dano superficial acumulável no fim de cada Turno."

### P-48.4 · Q-011

Fechar a Q-011: nenhuma Condição causa dano de Vontade. O Medo cobre o efeito mental em combate.
