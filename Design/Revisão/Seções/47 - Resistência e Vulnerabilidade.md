# 47 · Resistência e Vulnerabilidade + Resistência + Vulnerabilidade + Imunidade

**Arquivos:** `Regras/Resistência e Vulnerabilidade/` (índice, Resistência, Vulnerabilidade, Imunidade) e `en/`
**Relacionadas:** Armaduras (D-072, Resistências nas armaduras), Armas (Material, Perfurar da D-071, Raspão), Zonas (D-062), Características de NPC (Ir para a Garganta, Investida), Vida
**Pendências que chegam aqui:** nenhuma
**Status:** decidida (D-075) e aplicada; aguardando o merge do PR

## O que está estabelecido

- **Absorção Efetiva** = Absorção total + Σ Resistências ao Tipo e ao Material − Σ Vulnerabilidades ao Tipo e ao Material.
- **Positiva:** converte esse número de pontos de dano agravado em superficial.
- **Negativa:** o valor é somado ao dano, e todo o dano fica agravado, mesmo o que era superficial.
- **Imunidade** ao Tipo ou ao Material: o dano é ignorado antes de qualquer cálculo.
- Resistências, Vulnerabilidades e Imunidades a Materiais ficam nas fichas; armaduras só dão Resistência a Tipos.
- Zonas usam o mesmo saldo, sem a Absorção (D-062).

## Análise

A estrutura é clara e os exemplos cobrem os casos principais. Achei três pontos de interação com o que mudou nas seções 42 a 45 e um detalhe de texto.

1. **Perfurar não diz qual Absorção reduz.** O texto da D-071 diz "a Absorção do alvo converte 1 ponto a menos". Não fica claro se reduz a Absorção total ou a Efetiva, nem se pode deixar a Absorção Efetiva negativa e, com isso, causar dano extra. Proponho: "a **Absorção Efetiva** do alvo é reduzida em 1, até no mínimo 0". Assim, Perfurar só fura a proteção e nunca cria Vulnerabilidade.
2. **"Ignorar a armadura" ficou ambíguo com as armaduras novas.** A característica de NPC **Ir para a Garganta** diz que o dano "ignora a Absorção da armadura". Depois da D-072, quase toda armadura também tem Resistência (Couro contra Corte, por exemplo). Não fica claro se essa Resistência também é ignorada. Proponho: "o dano ignora a **armadura** do alvo: a Absorção e as Propriedades dela não contam. A Absorção base continua valendo." Isso também deixa de contar a Vulnerabilidade a Elétrica da armadura de metal, o que é coerente: o golpe passou por fora da armadura.
3. **Absorção Efetiva negativa sem dano.** Com Absorção Efetiva -2, um Ataque que causa 0 de dano passaria a causar 2? O texto não diz. Proponho deixar claro que o valor negativo só se soma **quando o personagem sofre pelo menos 1 ponto de dano** daquela fonte.
4. **Dois "Investida" com números diferentes.** A característica de NPC é **Investida (+2 de Dano; 4 quadrados)**, e a Propriedade de arma da D-071 é Investida (+1 de Dano; 3 quadrados). Como a de NPC já traz os valores entre parênteses, as duas podem ser vistas como a mesma regra com valores diferentes. Proponho deixar como está e acrescentar uma frase na de NPC: "É a mesma regra da Propriedade de arma [Investida](...), com valores próprios."

### Conferido, sem mudança

- **Raspão e Não letal contra Vulnerabilidade:** o dano superficial vira agravado quando a Absorção Efetiva fica negativa. É uma consequência forte, mas coerente com a regra: a criatura vulnerável sofre mais com qualquer golpe daquele Tipo.
- **Soma de várias fontes:** Resistências de armadura, da criatura e de efeitos se somam sem limite. O texto já diz isso com o Σ.
- **Imunidade:** clara e sem exceções escondidas.

## Propostas

### P-47.1 · Perfurar (em Armas)

> **Perfurar** — ao vencer um Ataque, a [Absorção Efetiva](../Resist%C3%AAncia%20e%20Vulnerabilidade/Resist%C3%AAncia%20e%20Vulnerabilidade.md#absor%C3%A7%C3%A3o-efetiva) do alvo é reduzida em **1**, até no mínimo 0.

### P-47.2 · Ignorar a armadura (Ir para a Garganta)

> Ao vencer um Ataque com Margem 3 ou mais, o dano ignora a **armadura** do alvo: a Absorção e as Propriedades dela não contam. A Absorção base continua valendo.

### P-47.3 · Absorção Efetiva negativa

- Em Resistência e Vulnerabilidade e em Vulnerabilidade: "o valor negativo é somado ao dano recebido, **quando o personagem sofre pelo menos 1 ponto de dano daquela fonte**".

### P-47.4 · Investida de NPC

- Frase de ligação entre a Investida de NPC e a Propriedade de arma.

## Decisões do autor (2026-11-05)

- P-47.2 ajustada: Ir para a Garganta ignora **só a Absorção** da armadura; a Absorção base e as Resistências e Vulnerabilidades da armadura continuam valendo.
- P-47.1, P-47.3 e P-47.4: aprovadas como propostas.
- Registrada como D-075.
