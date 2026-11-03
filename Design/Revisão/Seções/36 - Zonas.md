# 36 · Zonas

**Arquivo:** `Regras/Cenas e Conflitos/Zonas.md` (e `en/`)
**Relacionadas:** Confrontar (Alvo sem Resposta, Esquivar), Manobras (Reposicionar), Resistência e Vulnerabilidade, Características de NPC (Sopro), Acrobata, Guardião, Movimentação (diagonal custa 1)
**Status:** concluída (PR #58, mergeado em 2026-11-03)

## O que está estabelecido

- Uma Zona é um efeito de área; quem a cria define formato, tamanho, alcance, duração, efeitos e Dano. Afeta todos dentro, inclusive aliados, e cada criatura uma vez só.
- **Zona de dano:** a criatura testa Agilidade + Acrobacia (ou a Reserva da fonte). Cada Sucesso primeiro converte 1 agravado em superficial; depois, remove 1 superficial. Para anular Dano N são precisos 2N Sucessos.
- Não é Ataque, não é Esquivar, não desloca, ignora a Absorção. Resistência converte agravado antes do teste, Vulnerabilidade aumenta o Dano, Imunidade anula.
- **Duração:** instantânea ou persistente; a fonte diz quando a persistente afeta.

## Análise

### Mecânica

1. **A resolução é boa.** Um só teste por criatura, sem rolagem de quem criou a Zona, e um resultado em degraus (agravado vira superficial, depois some) que dá valor a cada Sucesso. Ignorar a Absorção dá às Zonas um papel claro contra alvos muito blindados, e Acrobata e Guardião já têm respostas próprias. Não encontrei abuso.
2. **O formato "cone" é usado mas não é definido (lacuna, problema objetivo).** O Sopro das Características de NPC cria "um cone de 3 quadrados", e o núcleo não diz como desenhar um cone (nem uma área ou uma linha) na grade. Cada mesa vai desenhar de um jeito. Como a diagonal custa 1 no Astra, os formatos podem ser simples (ver P-36.1).
3. **Criatura que não pode resistir (lacuna).** Uma criatura inconsciente ou Incapacitada dentro de uma Zona não tem como fazer o teste. Proponho a mesma regra de Alvo sem Resposta: o resultado conta como 1 Sucesso.
4. **Zona persistente e deslocamento repetido (prevenção).** A fonte diz quando a Zona persistente afeta (ao entrar, ao começar o Turno nela). Sem um limite, Reposicionar alguém para dentro e para fora, ou uma criatura que entra e sai, sofre a Zona várias vezes na mesma Rodada. Hoje nenhuma regra cria Zona persistente, então isso é só prevenção; um limite de uma vez por Rodada resolve com uma frase.
5. **Resistência e Vulnerabilidade somadas de modo diferente do resto (inconsistência).** No dano comum, Resistências e Vulnerabilidades ao Tipo e ao Material são somadas num só valor (Absorção Efetiva). Na Zona, cada uma age separada: com Resistência 3 e Vulnerabilidade 3 contra uma Zona de Dano 2, o alvo sofre 5 de Dano e converte 3 (2 agravados e 3 superficiais), enquanto no dano comum os valores se anulariam. Proponho somar primeiro, como no resto do sistema: o saldo positivo converte agravado em superficial, o negativo aumenta o Dano. O mesmo texto está em Resistência e Vulnerabilidade e mudaria junto.

### Texto e estrutura

6. **A página está clara e curta.** A tabela de exemplo é boa. Só mudaria o que as propostas acima pedem.

## Propostas

### P-36.1 · Formatos de Zona (lacuna)

Nova seção "Formatos", depois do terceiro parágrafo:

- **Área N:** todos os quadrados a até N quadrados de um ponto escolhido (contando a diagonal como 1, isso forma um quadrado de lado 2N + 1).
- **Linha N:** N quadrados em linha reta, na horizontal, na vertical ou na diagonal, a partir de um quadrado adjacente a quem cria a Zona.
- **Cone N:** parte de quem cria a Zona numa das oito direções. Numa direção reta, a fileira a 1 quadrado tem 1 quadrado de largura, a fileira a 2 tem 3, e assim por diante até N. Numa diagonal, o cone é o quadrado de N × N quadrados que começa no canto escolhido.
- A fonte pode usar outro formato, desde que o descreva.
- **Alternativa:** definir só o Cone, que é o único usado hoje.

### P-36.2 · Quem não resiste e Zona persistente (lacunas)

- Em Zonas de Dano: "Uma criatura que não pode resistir segue a regra de [Alvo sem Resposta](A%C3%A7%C3%B5es/Confrontar.md#alvo-sem-resposta): o resultado dela conta como 1 Sucesso."
- Em Duração, no item Persistente: "Uma mesma Zona persistente afeta cada criatura no máximo uma vez por Rodada."

### P-36.3 · Resistência e Vulnerabilidade somadas (consistência)

- Em Interações, os itens de Resistência e Vulnerabilidade viram um: "[Resistências](...) e [Vulnerabilidades](...) ao Tipo de Dano e ao Material da Zona são somadas, como na Absorção Efetiva. Um saldo positivo converte esse número de pontos de dano agravado em superficial antes de aplicar os Sucessos do teste; um saldo negativo aumenta o Dano da Zona."
- A mesma frase substitui a de Zonas em `Resistência e Vulnerabilidade.md` (seção Relações).
- **Alternativa:** manter separadas, como está.

## Decisões do autor (2026-11-03)

- **P-36.1:** aprovada com ajuste: usar formatos já estabelecidos na indústria e mostrar um exemplo de cada. Como o Astra conta a diagonal como 1, adotei o padrão de grade que usa a mesma regra (o de D&D 4ª edição): **Explosão N** (quadrado de lado 2N + 1 em volta de um ponto), **Rajada N** (quadrado N × N adjacente a quem cria) e **Linha N**. A Rajada substitui o "cone" proposto: numa grade com diagonal 1, um cone triangular não tem desenho único, e o quadrado adjacente é o padrão que evita discussão. O Sopro passa a usar "Rajada 3". Cada formato tem diagrama (D-062).
- **P-36.2 e P-36.3:** aprovadas (D-062).
