# 45 · Escudos + Catálogo de Escudos

**Arquivos:** `Regras/Equipamentos/Escudos.md`, `Regras/Equipamentos/Catálogo de Escudos.md` (e `en/`)
**Relacionadas:** Confrontar (Defender), Aparador, Guardião (Cobrir Aliado), Ambidestro (Guarda Cruzada), Guarda (D-071), Critério de Equilíbrio de Equipamentos
**Pendências que chegam aqui:** Q-013 (Aparador × Escudo)
**Status:** concluída (PR #67, mergeado em 2026-11-05)

## O que está estabelecido

- Com um Escudo, o personagem pode **Defender**: a Reserva é Força + Lutar + **Proteção**.
- **Categorias:** Leve (Proteção 1), Médio (2, Força 2) e Pesado (3, Força 3, Carga 2, -1 dado ao Atacar). Abaixo da Força mínima, o personagem tem -2 de Movimentação, que não se soma à da armadura.
- **Catálogo:** um escudo por Categoria (Broquel 5, Escudo 10, Escudo de Corpo 40), com os preços do 5e.
- **Aparar** (Aparador 1): Defender com a arma, usando a Reserva de Ataque da arma + o **Dano da arma** no lugar da Proteção. O Aparador 2 estende o Aparar a Ataques à distância.

## Análise

### Q-013 · Aparador × Escudo

1. **O problema continua de pé.** Com Aparar, uma arma de Dano 4 dá +4 ao Defender, mais que o Escudo de Corpo (+3). E o portador não paga Força 3, Carga 2, -1 dado ao Atacar, nem ocupa a outra mão. Um Montante com Aparador defende melhor que qualquer escudo e ainda ataca com Dano 4. A Guarda do Montante (D-071) aumenta a diferença, porque também ajuda no Esquivar.
2. **O que o Escudo já tem e a arma não:**
   - funciona contra Ataques à distância desde o início (o Aparador só chega lá no Nível 2);
   - não exige Competência.

   Isso não compensa os +4 contra os +3.
3. **O que proponho: limitar o bônus do Aparar a +2,** a Proteção de um Escudo Médio. O texto ficaria "adiciona o **Dano da arma, até no máximo 2**". Assim:
   - uma espada de uma mão defende como um Escudo Médio, que é o que o Aparador promete ("bloquear golpes com a própria arma, sem depender de um escudo");
   - o Escudo de Corpo continua sendo a melhor defesa, e paga por isso;
   - armas de Dano 3 e 4 continuam sendo boas para Aparar, mas não melhores que um escudo.
4. **Alternativa:** metade do Dano da arma, arredondada para cima (Dano 1 e 2 dão +1, Dano 3 e 4 dão +2). Pune mais as armas leves e de uma mão, que são justamente as do duelista que o Aparador quer representar. Não recomendo.
5. **A mudança é só de valor**, dentro da Capacidade existente. Li a seção **Progressão fixa** do Fundamento: o Nível 1 continua sendo o Fundamento do estilo, e nada muda na estrutura.

### Texto

6. **A tabela de campos não bate com o catálogo** (tem "Descrição" e outra ordem). Proponho alinhar, como em Armas e Armaduras.
7. **O -1 dado do Escudo Pesado aparece três vezes:** na tabela de Categorias, num parágrafo logo abaixo e no catálogo. Proponho deixar só na tabela e no catálogo.

### Orçamento

8. **(Substituído pelo orçamento de escudos, abaixo.)** Escudos não precisam de orçamento próprio. São três, um por Categoria, e cada passo troca mais Proteção por mais custo (Força, Carga e, no Pesado, -1 dado ao Atacar). Nenhum é melhor que outro em tudo. Proponho registrar isso no critério, em duas linhas, para quem criar escudos novos.

### Conferido, sem mudança

- **Força mínima:** igual à das armaduras, e as duas não se somam.
- **Guardião (Cobrir Aliado):** depende da regra de Defender, não do valor do bônus.
- **Ambidestro (Guarda Cruzada):** ao Aparar, soma também o Dano da arma secundária, que é Leve (Dano 1, ou 2 no Porrete). Com o limite de 2 na arma principal, o total chegaria a 3, ou 4 com um Porrete. Proponho limitar o total da Guarda Cruzada a **3**, a Proteção do Escudo de Corpo (ver a P-45.1).

## Orçamento de escudos (pedido do autor em 2026-11-05)

O autor pediu para montar o orçamento dos escudos antes de decidir a Q-013, porque o teto do escudo é a referência para o Aparar. Esta parte substitui o item 8 e a P-45.3 original.

### Como a defesa escala hoje

- **Defender com escudo:** Força + Lutar + Proteção. A Proteção é fixa por Categoria: 1, 2 ou 3.
- **Aparar:** Reserva de Ataque da arma (Agilidade ou Força + Lutar) + Dano da arma, de 0 a 4. Cresce com a arma escolhida.
- O escudo não tem nada além da Proteção. Por isso, hoje, escolher um escudo é escolher só um número.

### Análise

1. **A Categoria faz o papel da base**, como nas armaduras: Leve dá Proteção 1, sem custo; Médio dá 2 e custa Força 2; Pesado dá 3 e custa Força 3, Carga 2 e -1 dado ao Atacar.
2. **O que pode diferenciar escudos da mesma Categoria** são efeitos ligados a Defender ou ao uso do escudo, não mais Proteção. Mais Proteção pularia de Categoria.
3. **Três vantagens possíveis**, todas a partir de regras que já existem:
   - **Cobertura:** +1 de Proteção contra Ataques à distância. Representa o escudo grande que cobre o corpo todo.
   - **Repelir:** ao vencer ao Defender um Ataque corpo a corpo, o personagem pode empurrar o atacante **1 quadrado**, seguindo os limites de [Reposicionar](../Cenas%20e%20Conflitos/A%C3%A7%C3%B5es/Manobras.md#reposicionar). É a mesma ideia da Maestria Deslocar, mas na defesa.
   - **Golpe de Escudo:** o escudo também pode ser usado como arma corpo a corpo Leve, Dano 1, Contusão, Madeira ou Metal comum. Assim, ele pode ser a arma secundária do [Combate com Duas Armas](../Cenas%20e%20Conflitos/A%C3%A7%C3%B5es/Confrontar.md#combate-com-duas-armas).
4. **Não proponho desvantagem própria dos escudos.** O -1 dado do Pesado já é o custo da Categoria, e não achei outra desvantagem natural.

### Orçamento

| Categoria | Proteção | Custo da Categoria |
|---|---:|---|
| Leve | **2** | nenhum |
| Médio | **3** | Força 2 |
| Pesado | **4** | Força 3, Carga 2, -1 dado ao Atacar |

Decidido pelo autor em 2026-11-05: a Proteção começa em 2 no Leve e sobe 1 por Categoria (antes: 1, 2 e 3).

- Todo escudo tem **uma vantagem**: Cobertura, Repelir ou Golpe de Escudo.
- **Fora da conta:** Valor e Carga dentro da faixa da Categoria.

### Catálogo com o orçamento

| Escudo | Proteção | Vantagem | Motivo para escolher |
|---|---:|---|---|
| Broquel | 2 | **Golpe de Escudo** | o escudo do duelista, que também ataca |
| Escudo | 3 | **Repelir** | segura o inimigo longe |
| Escudo de Corpo | 4 | **Cobertura** (5 contra Ataques à distância) | a melhor defesa, sobretudo contra disparos |

Com três vantagens e três Categorias, o catálogo comporta até nove escudos. Proponho começar com estes três e deixar os outros para módulos e cenários.

### O que isso muda na Q-013

Com a Proteção de 2 a 4, o Aparar passa a acompanhar os escudos pelo tamanho da arma: uma arma de Dano 2 apara como um Broquel, e um Montante (Dano 4) apara como um Escudo de Corpo, sem passar dele. O escudo continua com a vantagem própria, deixa a outra mão com uma arma e funciona contra disparos desde o início. A Q-013 fica bem menor. O que sobra é que o Montante com Aparador defende como o melhor escudo sem pagar Força 3, Carga 2 nem -1 dado ao Atacar; em troca, ele gasta uma Competência. As opções para esse resto são:

- **nada além da escala nova** (a Competência já é o custo);
- **Aparar uma vez por Rodada** (recomendada): o escudo Defende todos os Ataques, o Aparador só o primeiro;
- **limitar o Aparar a +2**;
- **as duas juntas**, com limite de +3.


### P-45.1 · Limite do Aparar (fecha a Q-013)

**Recomendada agora:** Aparar **uma vez por Rodada** (a Guarda Cruzada segue a mesma regra, porque também é um Aparar). O limite de +2 abaixo fica como alternativa, ou junto, com +3.

- Alternativa, limite de valor. Aparador, Nível 1: "adiciona o **Dano da arma, até no máximo 2**". Fórmula: **Reserva para Aparar = Reserva de Ataque da arma + Dano da arma (máximo 2)**.
- **Guarda Cruzada (Ambidestro 2):** ao Aparar, a soma do Dano das duas armas fica limitada a **3**, a Proteção de um Escudo de Corpo. Assim, a Capacidade continua valendo a pena, sem passar do melhor escudo. Ao Esquivar, nada muda.
- **Alternativa:** metade do Dano da arma, arredondada para cima.

### P-45.2 · Texto

- Tabela de campos na ordem do catálogo: Nome, Categoria, Proteção, Força mínima, Carga e Valor; sai "Descrição".
- Sai o parágrafo que repete o -1 dado do Escudo Pesado.

### P-45.3 · Orçamento e catálogo de escudos

- Três Propriedades novas de escudo: **Cobertura**, **Repelir** e **Golpe de Escudo**, com os textos da análise.
- Catálogo conforme a tabela "Catálogo com o orçamento".
- Seção "Escudos" no critério, com o orçamento.

## Efeito da escala nova (2026-11-05)

- **Defender fica 1 dado mais forte para todos os escudos.** Defender passa a ser a resposta mais segura com mais frequência, e quem tem escudo tende a Defender em vez de Aceitar o Confronto. Isso combina com a ideia de que o escudo segura a linha, mas é bom observar em jogo se as lutas ficam mais lentas.
- **Guardião:** Cobrir Aliado, Interpor-se e Abrigo usam a Proteção, então ficam 1 ponto melhores.
- **Aparar:** passa a ir de +0 a +4, a mesma faixa do Broquel (2) ao Escudo de Corpo (4). Não muda nada no texto do Aparador.

## Decisões do autor (2026-11-05)

- Pediu o orçamento de escudos antes de decidir a Q-013.
- "vamos iniciar com leve dando proteção 2 e subir 1 por categoria": Proteção 2, 3 e 4.
- Sobre o Aparador: o Guardião, com o mesmo investimento, empata na defesa própria, protege aliados e passa à frente no Nível 5. A Q-013 fecha sem limite no Aparar.
- "concordo": orçamento, vantagens, catálogo, texto e critério aprovados.
- Golpe de Escudo: o escudo vira uma arma de uma mão, **sem Leve**, de modo que o Ambidestro não funciona com ele. A exceção "escudos não contam como arma secundária" passa a não valer para o escudo com Golpe de Escudo.
- Registrada como D-073.
