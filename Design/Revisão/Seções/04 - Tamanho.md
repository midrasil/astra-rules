# 04 · Tamanho

**Arquivo:** `Regras/Personagens/Tamanho.md` (e a versão em `en/`)
**Status:** em discussão

## O que está estabelecido

- **Seis categorias:**

  | Categoria | Espaço no mapa |
  | --- | --- |
  | Minúsculo | ½ quadrado |
  | Pequeno | 1 quadrado |
  | Médio | 1 quadrado |
  | Grande | 2×2 |
  | Enorme | 3×3 |
  | Colossal | 4×4 |

  O padrão é Médio. Uma criatura que ocupa vários quadrados é adjacente a tudo que está ao redor de qualquer um deles.
- **Mover outra criatura.** Só é possível mover alguém do mesmo Tamanho ou menor (Reposicionar, arrastar alguém Agarrado). Uma criatura menor "ainda pode tentar Derrubar, Agarrar ou Desarmar uma maior, mas não consegue tirá-la do lugar".
- **Tamanho no Ataque.** Alvo 2 categorias maior dá +2 dados, 3 ou mais categorias maior dá +4, e alvo 2 ou mais categorias menor dá -2. Uma categoria de diferença não muda nada.

## Análise

1. **Uma criatura pequena consegue imobilizar uma enorme (problema objetivo).** Agarrar aplica Movimentação 0, e Derrubar aplica Caído, sem nenhum limite de Tamanho. Pela regra atual, um gato que vence o teste de Força + Atletismo deixa um dragão sem se mover, porque ele "não consegue tirá-la do lugar", mas a imobiliza. Isso contradiz a própria intenção da página. Na prática, a disputa de Força + Atletismo costuma barrar casos extremos. Mas um personagem Pequeno e forte contra um ogro Grande, ou várias criaturas pequenas se revezando, passam pela regra.
2. **Minúsculo não diz como dividir o espaço (lacuna).** Meio quadrado sugere que várias criaturas cabem num quadrado, mas a página não diz se uma criatura Minúscula pode estar no quadrado de outra, nem se pode ser atravessada. Hoje a Movimentação proíbe atravessar inimigos, então um rato inimigo bloquearia o corredor.
3. **Pequeno e Médio ocupam o mesmo espaço (pergunta).** A diferença aparece só em mover alguém: um personagem Pequeno não pode Reposicionar nem arrastar um Médio. Se o cenário tiver espécies jogáveis Pequenas, isso restringe Manobras para elas. Pode ser intencional.
4. **A tabela de Ataque funciona.** A assimetria (até +4 contra alvos maiores, só -2 contra menores) é deliberada e está clara. O texto é bom e curto.

## Propostas

### P-04.1 · Limite de Tamanho para Agarrar e Derrubar (problema objetivo)

> Uma criatura só pode **Agarrar** ou **Derrubar** um alvo de no máximo **uma categoria maior** que ela.

- **Consequência:** um humano ainda agarra um ogro (uma categoria), mas não um gigante. Desarmar continua livre. A frase "uma criatura menor ainda pode tentar…" passa a citar só Desarmar e o limite.
- **Alternativa:** aplicar a tabela de Tamanho no Ataque também às Manobras (o alvo maior recebe os dados de bônus para resistir). Isso cria mais uma situação de consulta à tabela.

### P-04.2 · Espaço de criaturas Minúsculas (lacuna)

> Uma criatura **Minúscula** pode ocupar o mesmo quadrado de outra criatura e pode ser atravessada por qualquer uma.

- **Consequência:** resolve ratos, insetos e familiares sem regras novas de frações de quadrado. A tabela passa a dizer "divide um quadrado" em vez de "½ × ½".
- **Alternativa:** manter ½ × ½ e definir quantas cabem por quadrado. Isso é mais preciso e mais trabalhoso no mapa.

### P-04.3 · Pequeno não move Médio (pergunta ao autor)

É intencional que personagens Pequenos não possam Reposicionar nem arrastar um alvo Médio? Se não for, a alternativa é tratar Pequeno e Médio como **iguais para mover outra criatura**. Eles já ocupam o mesmo espaço.
