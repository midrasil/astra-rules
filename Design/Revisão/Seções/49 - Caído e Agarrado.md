# 49 · Caído + Agarrado

**Arquivos:** `Regras/Condições/Caído.md`, `Regras/Condições/Agarrado.md` e `en/`
**Relacionadas:** Manobras (Derrubar, Agarrar), Tamanho (limite de Tamanho), Movimentação (Movimentação Especial), Trocar Equipamento (D-074), Características de NPC (Voadora, Constritora, Teia), Condições (Regras gerais, D-076)
**Pendências que chegam aqui:** Q-017 (fim do agarrão e mão livre)
**Status:** concluída (PR #71, mergeado em 2026-11-05)

## O que está estabelecido

**Caído**
- Rastejar é Movimentação Especial (2 pontos por quadrado).
- Ataques corpo a corpo contra o Caído têm +2 dados; Ataques à distância contra ele, -2 dados.
- O Caído tem -2 dados em todas as suas Reservas.
- Para se levantar, ele gasta metade da Movimentação no próprio Turno, sem usar a Ação. Com Movimentação 0, não pode se levantar.

**Agarrado**
- O personagem fica com Movimentação 0 e tem -2 dados para atacar qualquer alvo que não seja quem o agarra.
- Quem agarra pode arrastar ou carregar o alvo como Movimentação Especial, se o alvo for no máximo uma categoria de Tamanho maior.
- Para escapar, o Agarrado usa a Ação: Força + Atletismo contra Força + Atletismo. Um empate mantém o agarrão.

## Análise

### Caído

1. **"Metade da Movimentação" sem arredondamento e sem saldo.** Com Movimentação 6, levantar custa 3 pontos. Com Movimentação 5 (por Lento, por exemplo), não fica claro se custa 2 ou 3. Também não fica claro se dá para se levantar depois de já ter gastado mais da metade. Proponho usar **metade da Movimentação base, arredondada para cima**, gasta da Movimentação que ainda resta no Turno. Arredondar para cima evita que uma Movimentação 1 deixe a pessoa levantar de graça.
2. **O peso total de Derrubar.** Contra um alvo Caído, os aliados ganham +2 dados no corpo a corpo, e o alvo responde com -2 dados: uma diferença de 4 dados. É forte, mas a Condição sai barata (meia Movimentação, sem Ação), e Derrubar custa uma Ação e um Confronto. Na prática, o efeito dura até o Turno do alvo. Recomendo manter.

### Agarrado (Q-017)

3. **Quem agarra não pode soltar.** Hoje o agarrão só termina quando o alvo escapa. Proponho que quem agarra **possa soltar a qualquer momento, sem usar a Ação**.
4. **O agarrão não termina por outras causas.** Proponho que ele termine também quando:
   - os dois **deixam de estar adjacentes**, por exemplo por um Reposicionar ou um Repelir;
   - quem agarra fica **Incapacitado** ou **Paralisado**.
   Atordoado não encerra o agarrão. Ele tira a Ação, e manter o agarrão não usa a Ação.
5. **Mão livre.** Hoje dá para agarrar empunhando uma arma de duas mãos. Proponho que **agarrar exija uma mão livre, e que ela fique ocupada enquanto durar o agarrão**. Isso conversa com Trocar Equipamento (D-074): soltar a arma é sempre livre. Criaturas sem mãos agarram com a parte do corpo que a ficha indicar, como a Constritora, que agarra com o próprio Ataque natural.
6. **Efeito sem quem agarre.** A Teia deixa o alvo Agarrado "pela teia" e já define a própria forma de escapar. As regras de soltar e de adjacência não fazem sentido para ela. Proponho uma frase: "Quando a Condição vem de um efeito sem um personagem que agarre, como a Teia, o efeito define como escapar." Nesse caso, a penalidade de -2 vale contra qualquer alvo, o que é coerente: preso numa teia, o personagem ataca mal qualquer um.
7. **Escapar só com Força.** Um personagem ágil não tem como se soltar a não ser pela Força. A Manobra Agarrar também se resiste só com Força + Atletismo. Proponho permitir que o Agarrado escolha **Força + Atletismo ou Agilidade + Acrobacia** para escapar, sempre contra Força + Atletismo de quem agarra. É uma opção a mais sem regra nova, e dá saída ao arquétipo ágil. **É opcional:** sem ela, o agarrão continua sendo a ferramenta do personagem forte contra o ágil, o que também é uma leitura válida.

8. **Arrasto e deslocamento forçado (pedido do autor).** Hoje o texto diz só que quem agarra "pode arrastar ou carregar" o alvo como Movimentação Especial. Ele não diz onde o alvo termina, se o arrasto conta como deslocamento forçado nem o que acontece numa borda ou num perigo. O termo "deslocado à força" já aparece em Mirando, no Atirador e na Sentinela, mas não é definido em lugar nenhum. Proponho duas coisas:
   - **Uma definição geral em Movimentação:** é deslocamento forçado todo movimento que outro personagem ou efeito impõe, como Reposicionar, Repelir, Deslocar e o arrasto do agarrão. Ele não gasta a Movimentação de quem é deslocado e não provoca Ataque de Oportunidade, o que já é a regra da Sentinela. Também aplica as regras de obstáculos e bordas do Reposicionar.
   - **O arrasto no Agarrado:** quem agarra se move por Movimentação Especial (2 pontos por quadrado), e o alvo vai junto. A cada quadrado, quem agarra põe o alvo em um quadrado adjacente a si. Para o alvo, isso é deslocamento forçado. Por isso, quem agarra pode arrastar o alvo para um perigo ou para fora de uma borda, com as consequências resolvidas normalmente, mas não pode largá-lo longe sem soltar, porque o agarrão termina quando os dois deixam de estar adjacentes.

### Conferido, sem mudança

- **Agarrado e Caído juntos:** com Movimentação 0, o personagem não levanta até escapar. A combinação é forte e já está escrita.
- **Voadora:** uma criatura que fica Caída ou Agarrada no ar cai, como já dizem as Características de NPC.
- **Duração:** as duas Condições têm forma própria de terminar, como a regra geral da D-076 já prevê.
- **Tamanho:** o limite de uma categoria vale para agarrar e para arrastar.

## Propostas

### P-49.1 · Levantar-se (Caído)

> Para deixar de estar Caído, o personagem gasta **metade da sua Movimentação base, arredondada para cima**, da Movimentação que ainda tem no Turno. Levantar-se não exige uma Ação. Sem Movimentação suficiente, como com Movimentação 0, ele não pode se levantar.

### P-49.2 · Fim do agarrão (Agarrado, nova seção "Fim do agarrão")

> Quem agarra pode soltar o alvo a qualquer momento, sem usar a Ação. O agarrão também termina quando os dois deixam de estar adjacentes ou quando quem agarra fica [Incapacitado](Incapacitado.md) ou [Paralisado](Paralisado.md).

### P-49.3 · Mão livre (Agarrado e Manobra Agarrar)

> Agarrar exige uma **mão livre**, que fica ocupada enquanto o agarrão durar. Criaturas sem mãos agarram com a parte do corpo que a ficha indicar.

### P-49.4 · Efeitos sem quem agarre (Agarrado)

> Quando a Condição vem de um efeito sem um personagem que agarre, como a [Teia](../Criaturas/Caracter%C3%ADsticas%20de%20NPC.md#teia), as regras de soltar e de adjacência não se aplicam, e o efeito define como escapar.

### P-49.5 · Escapar com Agilidade (opcional)

> **Personagem Agarrado:** Força + Atletismo **ou** Agilidade + Acrobacia, à sua escolha.
> **Quem mantém o agarrão:** Força + Atletismo.

### P-49.7 · Deslocamento forçado (Movimentação, nova subseção)

> **Deslocamento forçado** é todo movimento que outro personagem ou um efeito impõe a um personagem, como [Reposicionar](...), Repelir, Deslocar ou o arrasto de um [agarrão](../Condi%C3%A7%C3%B5es/Agarrado.md). Ele não gasta a Movimentação de quem é deslocado e não provoca Ataque de Oportunidade. Obstáculos e bordas seguem as regras do Reposicionar.

### P-49.8 · Arrastar (Agarrado, substitui o parágrafo atual)

> Quem mantém o agarrão pode arrastar o alvo enquanto se movimenta, desde que ele seja no máximo **uma categoria de Tamanho maior**. Esse movimento é uma **Movimentação Especial** para quem agarra. A cada quadrado, quem agarra põe o alvo em um quadrado adjacente a si. Para o alvo, isso é um [deslocamento forçado](...).

### P-49.6 · Q-017

Fechar a Q-017 com as P-49.2 e P-49.3.

## Decisões do autor (2026-11-05)

- **P-49.1 a P-49.6:** aprovadas como propostas, incluindo a P-49.5 (escapar com Agilidade + Acrobacia).
- **P-49.7 e P-49.8:** acrescentadas a pedido do autor, que quis definir o deslocamento forçado do agarrão. Aprovadas.
