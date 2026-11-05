# 44 · Armaduras + Catálogo de Armaduras

**Arquivos:** `Regras/Equipamentos/Armaduras.md`, `Regras/Equipamentos/Catálogo de Armaduras.md` (e `en/`)
**Relacionadas:** Resistência e Vulnerabilidade (Absorção Efetiva), Confrontar (Esquivar), Perfurar (D-071), Características de NPC (ignorar a Absorção da armadura), Zonas, Furtividade
**Pendências que chegam aqui:** nenhuma
**Status:** decidida (D-072) e aplicada; aguardando o merge do PR

## O que está estabelecido

- **Absorção:** converte dano agravado em superficial. Absorção total = Absorção base + Absorção da armadura.
- **Categorias:** Leve (Absorção 1, sem penalidade), Média (2 a 3, Força 2) e Pesada (4 a 5, Força 3). Médias e Pesadas tiram da Reserva de Esquivar dados iguais à Absorção; abaixo da Força mínima, o personagem tem -2 de Movimentação.
- **Propriedades:** Resistência e Vulnerabilidade a um Tipo; armaduras de metal têm Vulnerabilidade a Elétrica 1.
- **Catálogo:** dez armaduras, com Valores do D&D 5e (Gibão 5, Couro 10, Placa Peitoral 400, Armadura Completa 1500 etc.).

## Análise

### Texto

1. **A tabela de campos não bate com o catálogo.** Tem "Descrição", que o catálogo não usa, e a ordem é outra. Proponho alinhar com as colunas do catálogo, como fizemos em Armas (D-068).
2. **Nada diz quantas armaduras se pode vestir.** O texto fala em "Absorção das armaduras equipadas", no plural, e a fórmula da Absorção Efetiva também. Lido ao pé da letra, um personagem poderia vestir Couro por baixo da Cota de Malha e somar as duas. Proponho dizer: **o personagem veste uma armadura por vez**, e trocar o plural por "a armadura vestida".
3. **Vestir e tirar não têm regra.** Hoje, nada impede de vestir uma Armadura Completa no meio de uma luta, com Trocar Equipamento. Proponho o modelo do 5e, em minutos: vestir Leve 1, Média 5 e Pesada 10; tirar Leve 1, Média 1 e Pesada 5. Uma Cena Tática dura poucos segundos, então ninguém veste armadura durante uma.

### Catálogo

Aplicando a mesma pergunta da 43 ("cada armadura tem um motivo para ser escolhida?"):

4. **Leves:** Gibão (5), Couro (10) e Peles Grossas (10) são idênticos, só mudam o nome e o Valor. O Gibão é melhor em tudo que os outros dois, porque é mais barato. O Couro Batido tem Resistência a Corte e custa 45; ser melhor por custar mais é uma escolha legítima.
5. **Médias:** o Camisão de Malha e a Brunea de Escamas custam 50 e têm Absorção 2, mas a Brunea ainda tem Resistência a Perfurante. A Brunea é melhor em tudo que o Camisão.
6. **Pesadas:** a Armadura de Talas tem a mesma Absorção da Cota de Malha (4), sem a Resistência a Corte, e Carga maior (4 contra 3). A Cota é melhor em tudo, e ainda mais barata.
7. **O que o 5e usa para diferenciar armaduras do mesmo nível: a desvantagem em Furtividade.** Ela vale no Gibão Acolchoado, na Brunea de Escamas e em todas as Pesadas. O Astra tem Furtividade, mas nenhuma armadura pesa nela. Proponho uma Propriedade nova, **Ruidosa: -2 dados em Furtividade**. Com ela e uma Resistência em cada caso, cada armadura passa a ter um motivo (tabela substituída pelo orçamento, mais abaixo):

| Armadura | Hoje | Proposta | Motivo para escolher |
|---|---|---|---|
| Gibão Acolchoado | — | **Ruidosa** | a mais barata |
| Armadura de Couro | — | — | sem penalidade nenhuma |
| Peles Grossas | — | **Resistência a Gelo 1, Ruidosa** | frio |
| Couro Batido | Resistência a Corte 1 | (igual) | a melhor Leve, e a mais cara |
| Camisão de Malha | Vulnerabilidade a Elétrica 1 | **+ Resistência a Corte 1** | silenciosa, contra Corte |
| Brunea de Escamas | Resistência a Perfurante 1, Vulnerabilidade a Elétrica 1 | **+ Ruidosa** | contra Perfurante |
| Placa Peitoral | Vulnerabilidade a Elétrica 1 | (igual) | a melhor Média, e a mais cara |
| Cota de Malha | Resistência a Corte 1, Vulnerabilidade a Elétrica 1 | **+ Ruidosa** | contra Corte, a mais barata |
| Armadura de Talas | Vulnerabilidade a Elétrica 1, Carga 4 | **+ Resistência a Perfurante 1, Ruidosa; Carga 3** | contra Perfurante |
| Armadura Completa | Vulnerabilidade a Elétrica 1 | **+ Ruidosa** | a maior Absorção |

8. **Por que -2 dados.** É a penalidade padrão do Astra, a mesma da Penumbra no Perceber. Não proponho penalidade em mais nada, porque as Médias e as Pesadas já pagam no Esquivar, na Força mínima e na Carga.

### Conferido, sem mudança

- **Esquivar:** a penalidade igual à Absorção da armadura, sem contar a Absorção base nem as Resistências, está clara.
- **Força mínima:** -2 de Movimentação é o mesmo que os 10 pés do 5e.
- **Perfurar** (D-071) e a característica de NPC que ignora a Absorção da armadura convivem bem com a regra atual.
- **Valores:** batem com o 5e.

## Orçamento de armaduras (pedido do autor em 2026-11-05)

O autor pediu para rever as armaduras com a mesma lógica do orçamento das armas (D-070). Esta parte substitui a tabela do item 7 e a P-44.3 original.

### Análise

1. **O que a Categoria já fixa:** a Absorção base, a Força mínima, a penalidade ao Esquivar e a Carga. É o equivalente ao Dano base da Empunhadura nas armas.
2. **O que diferencia armaduras da mesma Categoria:** mais Absorção e Resistências. Isso faz o papel das vantagens.
3. **Uma desvantagem compra mais uma vantagem**, como nas armas. A desvantagem que existe é **Ruidosa** (-2 dados em Furtividade), a do 5e.
4. **Nas Pesadas, Ruidosa é da Categoria.** No 5e, todas as armaduras pesadas atrapalham a furtividade. Proponho que Ruidosa faça parte do custo da Categoria Pesada, como a Força 3, e não conte como desvantagem.
5. **+1 de Absorção se paga sozinho em parte.** Nas Médias e Pesadas, a penalidade ao Esquivar é igual à Absorção. Quem escolhe a armadura de Absorção maior também perde mais dados ao Esquivar. Mesmo assim, conto o +1 como vantagem, porque a Absorção vale contra todo Ataque e o Esquivar é só uma das três respostas.
6. **A Vulnerabilidade a Elétrica do metal fica fora da conta**, como o Material nas armas. Ela muda contra o que a armadura é ruim, não o quanto ela é boa.
7. **Leves não ganham +1 de Absorção.** Uma Leve com Absorção 2 teria a proteção de uma Média sem nenhuma penalidade. A vantagem das Leves é sempre uma Resistência.

### Orçamento

| Categoria | Absorção base | Custo da Categoria |
|---|---:|---|
| Leve | 1 | nenhum |
| Média | 2 | Força 2, Esquivar -Absorção, Carga 2 |
| Pesada | 4 | Força 3, Esquivar -Absorção, Carga 3 ou 4, Ruidosa |

- Toda armadura tem **uma vantagem**, escolhida entre:
  - **+1 de Absorção** (só Média e Pesada);
  - **Resistência 1** a um Tipo.
- **Ruidosa**, numa Leve ou Média, compra **mais uma vantagem**.
- **Fora da conta:** Valor, Carga dentro da faixa da Categoria e a Vulnerabilidade a Elétrica do metal.

### Catálogo com o orçamento

| Armadura | Absorção | Vantagem | Desvantagem | Muda em relação a hoje |
|---|---:|---|---|---|
| Gibão Acolchoado | 1 | Resistência a Contusão 1 e a Perfurante 1 | Ruidosa | + as duas Resistências, + Ruidosa |
| Armadura de Couro | 1 | Resistência a Corte 1 | — | + Resistência a Corte 1 |
| Peles Grossas | 1 | Resistência a Gelo 1 | — | + Resistência a Gelo 1 |
| Couro Batido | 1 | Resistência a Perfurante 1 | — | Resistência a Corte → **Perfurante** |
| Camisão de Malha | 2 | Resistência a Corte 1 | — | + Resistência a Corte 1 |
| Brunea de Escamas | **3** | Resistência a Perfurante 1 e +1 de Absorção | Ruidosa | Absorção 2 → **3**, + Ruidosa |
| Placa Peitoral | 3 | +1 de Absorção | — | (igual) |
| Cota de Malha | 4 | Resistência a Corte 1 | (Ruidosa da Categoria) | + Ruidosa |
| Armadura de Talas | 4 | Resistência a Perfurante 1 | (Ruidosa da Categoria) | + Resistência a Perfurante 1, + Ruidosa; Carga 4 → **3** |
| Armadura Completa | 5 | +1 de Absorção | (Ruidosa da Categoria) | + Ruidosa |

Como fica a escolha:
- **Leves:** cada uma protege contra um Tipo. O Gibão protege contra dois, mas faz barulho. O Couro e o Couro Batido custam valores diferentes pelo mesmo orçamento, como o 5e; o Valor fica fora da conta.
- **Médias:** a Placa Peitoral é a de Absorção 3 silenciosa. A Brunea tem a mesma Absorção e ainda Resistência a Perfurante, mas é Ruidosa. O Camisão é o mais leve no Esquivar (-2).
- **Pesadas:** a Cota protege contra Corte, a de Talas contra Perfurante e a Completa tem a maior Absorção (e a maior penalidade ao Esquivar, -5).

### Onde o critério fica

Proponho juntar as armaduras ao arquivo do critério das armas e renomeá-lo para `Design/Equipamentos/Critério de Equilíbrio de Equipamentos.md`. A seção 45 (Escudos) pode usar o mesmo arquivo.

## Propostas

### P-44.1 · Texto

- Tabela de campos na ordem do catálogo: Nome, Categoria, Absorção, Força mínima, Carga, Valor e Propriedades; sai "Descrição".
- "O personagem veste **uma armadura por vez**." "Absorção das armaduras equipadas" vira "Absorção da armadura vestida", também na fórmula de Resistência e Vulnerabilidade.

### P-44.2 · Vestir e tirar

> Vestir uma armadura leva **1 minuto** (Leve), **5 minutos** (Média) ou **10 minutos** (Pesada). Tirá-la leva **1 minuto** (Leve ou Média) ou **5 minutos** (Pesada). Não é possível vestir ou tirar uma armadura durante uma Cena Tática.

### P-44.3 · Orçamento, Ruidosa e catálogo

- Propriedade nova: **Ruidosa** — "a armadura impõe **-2 dados** nos testes de [Furtividade](../Personagens/Per%C3%ADcias.md)." Toda armadura Pesada é Ruidosa.
- Orçamento de armaduras gravado no critério, que passa a se chamar `Critério de Equilíbrio de Equipamentos.md`.
- Catálogo conforme a tabela "Catálogo com o orçamento".

## Decisões do autor (2026-11-05)

- "podemos rever o funcionamento das armaduras seguindo a linha orçamentária que fizemos para as armas": a P-44.3 original foi substituída pelo orçamento de armaduras.
- "concordo": P-44.1, P-44.2 e P-44.3 (com o orçamento) aprovadas (D-072). O critério passou a se chamar `Critério de Equilíbrio de Equipamentos.md`.
