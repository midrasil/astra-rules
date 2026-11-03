# 40 · Saltar

**Arquivo:** `Regras/Movimento/Saltar.md` (e `en/`)
**Relacionadas:** Movimentação (D-064, Queda), Ação (lista de Ações Básicas), Correr, Mirando
**Status:** decidida (D-066) e aplicada; aguardando o merge do PR

## O que está estabelecido

- Saltar é uma **Ação**, sem teste.
- Distância base = Força ÷ 2. Cada quadrado percorrido antes do salto soma +1 (Impulso), até o valor de Atletismo (mínimo 1).
- Altura = distância ÷ 2.
- 1 quadrado = 1,5 m, só como referência.

## Análise

### Mecânica

1. **As fórmulas são boas.** Força dá a base, Atletismo limita o Impulso, e não há rolagem. Os números ficam realistas: um personagem forte e atlético (Força 5, Atletismo 5) salta até 7 quadrados (10,5 m) com corrida; sem corrida, 2 quadrados.
2. **Saltar custar a Ação pesa muito (observação de design).** Pular um buraco de 2 quadrados no meio do combate custa o Turno inteiro do personagem, que não ataca nem faz Manobras. Isso torna o salto raro em Cenas Táticas, justamente onde o terreno deveria importar. No D&D 5e, saltar é parte do movimento: cada pé saltado custa um pé de deslocamento, sem ação. Como você pediu o modelo do 5e em Iluminação e Queda, proponho o mesmo aqui (P-40.2): o salto gasta Movimentação, não a Ação. As fórmulas de distância continuam as do Astra.
3. **O Impulso não diz como deve ser feito (lacuna pequena).** "Cada quadrado percorrido antes do salto" pode ser lido como qualquer movimento anterior no Turno, até em zigue-zague. O sentido é uma corrida em linha reta logo antes do salto. Proponho dizer isso.
4. **Saltar além do limite (observação).** A página não diz o que acontece se o personagem tentar um salto maior que o seu limite. Pela regra, ele simplesmente não consegue; se o Narrador deixar tentar, a [Queda](../../../Regras/Movimento/Movimentação.md#queda) já resolve o resultado. Não proponho nada.

### Texto e estrutura

5. **A conversão de medida está no lugar errado.** "1 quadrado = 5 pés = 1,5 metro" vale para todo o sistema (a Queda usa metros), mas está escondida em Saltar. Proponho levá-la para Movimentação, logo depois da Movimentação base.

## Propostas

### P-40.1 · Impulso e medida (texto)

- Impulso: "Cada quadrado percorrido **em linha reta, logo antes do salto**, adiciona **+1 quadrado** à distância."
- A frase "1 quadrado = 5 pés = 1,5 metro" sai de Saltar e vai para Movimentação, depois da Movimentação base.

### P-40.2 · Saltar como parte da Movimentação (mudança de regra, modelo do 5e)

- Saltar deixa de ser uma Ação. O salto faz parte da Movimentação: **cada quadrado saltado custa 1 ponto de Movimentação**, como andar, e o Impulso também é pago normalmente. O personagem ainda tem sua Ação para atacar.
- A distância e a altura continuam com as fórmulas atuais (metade da Força + Impulso; altura = metade da distância).
- Saltar sai da lista de Ações Básicas em Ação.md e passa a ser listado em Movimentação. A seção "Salto" de Movimentação diz: "Saltar faz parte da Movimentação. Consulte [Saltar](Saltar.md)."
- O exemplo da página passa a dizer que os 3 quadrados de Impulso e os 5 do salto custam 8 pontos (o personagem precisaria de Correr para fazer o salto inteiro no mesmo Turno com Movimentação 6).
- **Alternativa:** manter Saltar como Ação, como está.

## Decisões do autor (2026-11-03)

- **P-40.1 e P-40.2:** aprovadas (D-066).
