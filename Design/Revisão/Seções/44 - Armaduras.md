# 44 · Armaduras + Catálogo de Armaduras

**Arquivos:** `Regras/Equipamentos/Armaduras.md`, `Regras/Equipamentos/Catálogo de Armaduras.md` (e `en/`)
**Relacionadas:** Resistência e Vulnerabilidade (Absorção Efetiva), Confrontar (Esquivar), Perfurar (D-071), Características de NPC (ignorar a Absorção da armadura), Zonas, Furtividade
**Pendências que chegam aqui:** nenhuma
**Status:** em análise

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
7. **O que o 5e usa para diferenciar armaduras do mesmo nível: a desvantagem em Furtividade.** Ela vale no Gibão Acolchoado, na Brunea de Escamas e em todas as Pesadas. O Astra tem Furtividade, mas nenhuma armadura pesa nela. Proponho uma Propriedade nova, **Ruidosa: -2 dados em Furtividade**. Com ela e uma Resistência em cada caso, cada armadura passa a ter um motivo:

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

## Propostas

### P-44.1 · Texto

- Tabela de campos na ordem do catálogo: Nome, Categoria, Absorção, Força mínima, Carga, Valor e Propriedades; sai "Descrição".
- "O personagem veste **uma armadura por vez**." "Absorção das armaduras equipadas" vira "Absorção da armadura vestida", também na fórmula de Resistência e Vulnerabilidade.

### P-44.2 · Vestir e tirar

> Vestir uma armadura leva **1 minuto** (Leve), **5 minutos** (Média) ou **10 minutos** (Pesada). Tirá-la leva **1 minuto** (Leve ou Média) ou **5 minutos** (Pesada). Não é possível vestir ou tirar uma armadura durante uma Cena Tática.

### P-44.3 · Ruidosa e catálogo

- Propriedade nova: **Ruidosa** — "a armadura impõe **-2 dados** nos testes de [Furtividade](../Personagens/Per%C3%ADcias.md)."
- Catálogo conforme a tabela da análise.
- **Alternativa:** manter o catálogo como está e aceitar as armaduras iguais, como diferenças só de aparência.
