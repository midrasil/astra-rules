# 01 · Mecânica Básica + Reserva de Dados

**Arquivos:** `Regras/Mecânica Básica/Mecânica Básica.md`, `Regras/Mecânica Básica/Reserva de Dados.md` (e as versões em `en/`)
**Status:** em discussão

## O que está estabelecido

- **Reserva de Dados.** Normalmente é **Atributo + Perícia**. Quando nenhuma Perícia se aplica, é só o Atributo. Também pode somar dois Atributos diferentes, nunca o mesmo duas vezes.
- **Atributo usado.** Cada Perícia tem um Atributo vinculado. Uma Ação, um equipamento ou outra regra pode substituí-lo, e uma Capacidade prevalece sobre tudo. As substituições trocam o Atributo, nunca o somam, e não formam cadeias. Descrever a ação de outro jeito não troca o Atributo.
- **Resolução.** Rola-se 1d10 por ponto. Cada resultado de **6 ou mais** é 1 Sucesso, e cada **par de 10** dá +1 Sucesso. O teste dá certo com Sucessos **iguais ou maiores que a Dificuldade**.
- **Dificuldade e excedente.** A escala de Dificuldade (1 a 6+) é uma sugestão. Os Sucessos acima da Dificuldade melhoram o resultado de forma narrativa.
- **Penalidades.** Elas se somam. A categoria da rolagem (Física ou Espiritual) segue o Atributo usado. Uma Reserva reduzida a **menos de 1 dado** não rola e vale **1 Sucesso**.
- **Ajuda.** Quem ajuda precisa estar adjacente e dá **+1 dado**. Esse bônus não se acumula com outras ajudas. Numa Cena Tática, ajudar gasta a Ação.
- **Arredondamento.** Divisões arredondam para baixo. Essa regra está no índice da área.

### Referência: chances por tamanho de Reserva

Calculado com sucesso em 6+ e par de 10.

| Dados | Média de Sucessos | ≥1 | ≥2 | ≥3 | ≥4 | ≥5 |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | 0,5 | 50% | 0% | — | — | — |
| 2 | 1,0 | 75% | 25% | 1% | — | — |
| 3 | 1,5 | 88% | 50% | 14% | 1% | — |
| 4 | 2,1 | 94% | 69% | 33% | 9% | 1% |
| 5 | 2,6 | 97% | 81% | 51% | 22% | 6% |
| 6 | 3,1 | 98% | 89% | 67% | 38% | 15% |
| 7 | 3,7 | 99% | 94% | 78% | 53% | 28% |
| 8 | 4,2 | 100% | 96% | 86% | 66% | 41% |

A escala de Dificuldade é coerente com isso. Uma Reserva de 4 dados passa na Dificuldade 2 em 69% das vezes e na Dificuldade 3 em 33%.

## Análise

### Mecânica

1. **A Reserva zerada vale mais que 1 dado (problema objetivo).** Com 1 dado, a chance de 1 Sucesso é de 50%. Com a Reserva abaixo de 1 dado, o personagem tem **1 Sucesso garantido**. Ou seja, quanto mais penalizado, melhor ele fica, justamente nos casos que mais importam:
   - contra Dificuldade 1, um personagem penalizado até zerar passa sempre, e um com 1 dado só passa metade das vezes;
   - num Confronto, um defensor com a Reserva zerada responde com 1 Sucesso certo.

   O próprio sistema também já trata o caso de dois jeitos: em Confrontar, um Ataque cuja Reserva chega a menos de 1 dado por causa do Alcance **não pode ser feito**.
2. **Não há regra geral de teste oposto (lacuna).** O texto diz que "em situações de oposição os Sucessos podem ser comparados diretamente", mas não diz quem vence no empate. Cada regra resolve isso por conta própria:
   - Confrontar: o atacante vence;
   - Manobras e Agarrado: nada acontece, ou seja, quem resiste vence;
   - Mentalista: resultado parcial.

   Um teste de Furtividade contra Percepção, por exemplo, não tem resposta.
3. **Ajuda fora de Cena Tática (lacuna pequena).** "Adjacente" só faz sentido no mapa, e a regra não diz o que vale fora dele.
4. **Os pares de 10, a Dificuldade e as substituições funcionam bem.** Não vejo motivo mecânico para mexer neles.

### Texto e estrutura

5. **A mesma regra aparece quatro vezes.** O Atributo vinculado e suas substituições são explicados no segundo parágrafo, no fim de "Montando", em "Determinando o Atributo" e em "Substituições de Atributo".
6. **O mesmo exemplo aparece duas vezes.** Agilidade 3 + Furtividade 2 = 5 dados está em "Montando" e de novo em "Realizando o Teste".
7. **A ordem obriga o leitor a pular para frente:**
   - "Realizando o Teste" fala no "valor necessário para um Sucesso" antes de dizer que ele é 6+;
   - "Penalidades" usa "1 Sucesso" antes da contagem de Sucessos;
   - "Penalidades" usa as categorias Física e Espiritual sem link para [Atributos](../../../Regras/Personagens/Atributos.md).

## Propostas

### P-01.1 · Reserva mínima de 1 dado (problema objetivo)

Penalidades não reduzem uma Reserva abaixo de **1 dado**, salvo quando a regra disser que a ação não pode ser feita (como o Alcance em Confrontar).

- **Por quê:** acaba com a inversão em que a penalidade ajuda. Um personagem muito penalizado ainda tem 50% de chance, mas nunca a garantia.
- **Consequências:**
  - em Confrontar, sai a frase "ou com a Reserva de Dados reduzida a menos de 1 dado" de *Alvo sem Resposta*;
  - *Alvo sem Resposta* passa a valer só para quem de fato não pode responder (surpreso, inconsciente);
  - nenhuma outra página cita a regra.
- **Alternativas:**
  - (b) Reserva zerada vale **0 Sucessos**. Fica mais punitivo e torna a falha automática.
  - (c) Manter como está.

### P-01.2 · Regra geral de teste oposto (lacuna)

Acrescentar uma seção curta:

> Em um **teste oposto**, os dois lados rolam suas Reservas e vence quem obtiver mais Sucessos. Em caso de empate, prevalece a situação atual: quem tenta mudar algo não consegue. Regras específicas, como [Confrontar](...), podem definir outro resultado para o empate.

- **Por quê:** dá uma resposta padrão para os testes que não estão em nenhuma regra específica.
- **Coerência:** esse padrão já é o de Manobras e Agarrado ("nada acontece"). Confrontar fica como exceção declarada.
- **Consequência:** nenhuma regra existente muda.

### P-01.3 · Reorganizar a página (texto e estrutura)

Juntar as quatro explicações sobre o Atributo numa única seção, tirar o exemplo repetido e seguir esta ordem:

1. Dados utilizados
2. Montando a Reserva (Atributo + Perícia, só Atributo, dois Atributos)
3. Sucessos e pares de 10
4. Dificuldade e Sucessos adicionais
5. Testes opostos (se P-01.2 for aprovada)
6. Penalidades e Reserva mínima
7. Substituições de Atributo
8. Ajuda

- **Por quê:** cada conceito aparece depois daquilo de que depende, e a página fica mais curta.
- **Consequência:** links com âncora para `#determinando-o-atributo` precisam ser conferidos. Nenhuma regra muda.

### P-01.4 · Ajuda dentro e fora da Cena Tática (lacuna pequena)

> Em uma Cena Tática, quem ajuda precisa estar adjacente e gasta sua Ação. Fora dela, basta que o ajudante possa de fato participar da tarefa, a critério do Narrador.

- **Consequência:** Inspirador (Ajuda a até 6 quadrados) continua coerente, porque é uma regra da Cena Tática.

### Fora das propostas

- **Tabela de chances na página.** Não proponho. Ela ajudaria o Narrador a calibrar, mas aumenta a página. A tabela fica registrada aqui como referência.
- **Valor da Ajuda em combate.** Gastar a Ação inteira por +1 dado (cerca de +0,5 Sucesso) parece fraco, a não ser com Inspirador. Isso fica para quando revisarmos Ação e Confrontar (Q-006).
