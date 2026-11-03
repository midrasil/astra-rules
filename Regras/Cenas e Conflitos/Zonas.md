Uma **Zona** representa um efeito que ocupa uma área e afeta as criaturas que estiverem dentro dela.

A regra ou Capacidade que cria uma Zona define seu formato, tamanho, alcance, posição, duração, efeitos e, quando aplicável, seu Dano e Tipo de Dano.

Por padrão, uma Zona afeta todas as criaturas em seu interior, incluindo aliados de quem a criou. Uma criatura cujo espaço ocupe mais de um quadrado é afetada apenas uma vez pela mesma Zona.

## Formatos

Os formatos de Zona usam a grade como a Movimentação: a diagonal conta como 1 quadrado. Nos diagramas, **C** é quem cria a Zona, **■** é um quadrado afetado, **◆** é o ponto de origem (também afetado) e **·** está fora da Zona.

### Explosão N

Todos os quadrados a até N quadrados de um ponto de origem, escolhido dentro do alcance da fonte. Uma Explosão N forma um quadrado de lado 2N + 1. Se a origem for o próprio quadrado de quem cria a Zona, ele também é afetado.

Explosão 1 e Explosão 2:

```
· · · · ·      ■ ■ ■ ■ ■
· ■ ■ ■ ·      ■ ■ ■ ■ ■
· ■ ◆ ■ ·      ■ ■ ◆ ■ ■
· ■ ■ ■ ·      ■ ■ ■ ■ ■
· · · · ·      ■ ■ ■ ■ ■
```

### Rajada N

Um quadrado de N × N quadrados adjacente a quem cria a Zona, em qualquer direção, inclusive na diagonal. Quem cria a Rajada não é afetado por ela.

Rajada 3 para a frente e na diagonal:

```
■ ■ ■          ■ ■ ■ ·
■ ■ ■          ■ ■ ■ ·
■ ■ ■          ■ ■ ■ ·
· C ·          · · · C
```

### Linha N

N quadrados em linha reta, na horizontal, na vertical ou na diagonal, a partir de um quadrado adjacente a quem cria a Zona. Quem cria a Linha não é afetado por ela.

Linha 4 na horizontal e Linha 3 na diagonal:

```
C ■ ■ ■ ■      · · · ■
               · · ■ ·
               · ■ · ·
               C · · ·
```

Uma criatura que ocupa mais de um quadrado mede a Rajada e a Linha a partir de qualquer quadrado que ocupa (ver [Tamanho](../Personagens/Tamanho.md)). A fonte pode usar outro formato, desde que o descreva.

## Zonas de Dano

Quando uma criatura é atingida por uma Zona de dano, ela realiza um teste de:

> **Agilidade + Acrobacia**

A regra ou Capacidade que criou a Zona pode determinar outra Reserva de Dados.

Uma criatura que não pode resistir segue a regra de [Alvo sem Resposta](A%C3%A7%C3%B5es/Confrontar.md#alvo-sem-resposta): o resultado dela conta como **1 Sucesso**.

Cada Sucesso obtido no teste é aplicado da seguinte forma:

1. enquanto houver dano agravado, o Sucesso converte 1 ponto desse dano em superficial;
2. depois que todo o dano tiver sido convertido, cada Sucesso restante remove 1 ponto de dano superficial.

### Exemplo

Uma criatura é atingida por uma Zona de Dano 4.

| Sucessos | Dano recebido |
| ---: | --- |
| 0 | 4 agravados |
| 2 | 2 agravados e 2 superficiais |
| 4 | 4 superficiais |
| 5 | 3 superficiais |
| 8 ou mais | nenhum dano |

## Interações

- Uma Zona não é um Ataque nem um Confronto. As Respostas Aceitar o Confronto, Defender e Esquivar não são utilizadas.
- Resistir a uma Zona não é Esquivar. Bônus, penalidades e substituições específicos de Esquivar não se aplicam, salvo quando uma regra disser o contrário.
- Resistir a uma Zona não movimenta a criatura.
- A Absorção base e a concedida por armaduras não se aplicam ao dano de uma Zona.
- [Resistências](../Resist%C3%AAncia%20e%20Vulnerabilidade/Resist%C3%AAncia.md) e [Vulnerabilidades](../Resist%C3%AAncia%20e%20Vulnerabilidade/Vulnerabilidade.md) ao Tipo de Dano e ao Material da Zona são somadas, como na [Absorção Efetiva](../Resist%C3%AAncia%20e%20Vulnerabilidade/Resist%C3%AAncia%20e%20Vulnerabilidade.md#absor%C3%A7%C3%A3o-efetiva). Um saldo positivo converte esse número de pontos de dano agravado em superficial antes de aplicar os Sucessos do teste; um saldo negativo aumenta o Dano da Zona.
- [Imunidade](../Resist%C3%AAncia%20e%20Vulnerabilidade/Imunidade.md) ao Tipo de Dano ou ao Material da Zona impede completamente o dano.

## Duração

Uma Zona pode ser instantânea ou persistente.

- **Instantânea:** resolve seu efeito assim que é criada e desaparece em seguida.
- **Persistente:** permanece no local pela duração definida pela regra ou Capacidade que a criou. Essa fonte também determina quando a Zona afeta uma criatura, como ao entrar nela ou começar o Turno em seu interior. Uma mesma Zona persistente afeta cada criatura no máximo uma vez por Rodada.

---

← [Voltar para Cenas e Conflitos](Cenas%20e%20Conflitos.md)
