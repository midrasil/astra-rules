# 29 · Criaturas (índice) + Tipos de Criatura

**Arquivos:** `Regras/Criaturas/Criaturas.md` e `Regras/Criaturas/Tipos de Criatura.md` (e `en/`)
**Relacionadas:** Caçador (seção 17; D-043), Personagens (índice, grupo Natureza), Readme, Perícias (Conhecimento Específico), Características de NPC (seção 30)
**Status:** concluída (PR #51, mergeado em 2026-11-02)

## O que está estabelecido

- **Índice de Criaturas:** duas páginas, Tipos de Criatura e Características de NPC.
- **Tipos de Criatura:** dez tipos (Humanoide, Besta, Monstruosidade, Morto-vivo, Constructo, Elemental, Espírito, Aberração, Planta, Dragão). O padrão é Humanoide. Uma criatura pode ficar **Sem tipo**. A página diz que o Tipo **não tem efeito mecânico** por enquanto e que cenários e módulos podem acrescentar tipos.

## Análise

### Mecânica

1. **"Não possui efeito mecânico" não é mais verdade (problema objetivo).** O Caçador usa o Tipo de duas formas:
   - a **presa** é qualquer criatura que não seja Humanoide;
   - o estudo usa **Natureza** contra Besta, Planta, Monstruosidade e Dragão, e **Ocultismo** contra Morto-vivo, Constructo, Elemental, Espírito e Aberração.

   A frase engana quem lê só esta página.
2. **"Sem tipo" fica sem resposta no Caçador (lacuna).** A presa é "uma criatura de qualquer Tipo, exceto Humanoide". Uma criatura Sem tipo pode ser presa? Se pode, qual Perícia o estudo usa? Nenhuma das duas páginas responde.
   - **Opção A: tirar "Sem tipo".** Toda criatura passa a ter um Tipo; se nenhum servir, o cenário cria um. A lacuna desaparece, e a regra fica mais simples.
   - **Opção B: manter e definir no Caçador**, por exemplo, Sem tipo conta como presa e usa Ocultismo. Isso acrescenta uma regra para um caso que talvez nunca apareça.
3. **Tipos novos de cenários e módulos também ficam sem resposta no Caçador (lacuna pequena).** Se um cenário cria o tipo "Fada", o Caçador não sabe se usa Natureza ou Ocultismo. Basta dizer que quem cria um tipo diz como as regras que citam tipos o tratam.
4. **Uma criatura pode ter mais de um Tipo? (lacuna pequena).** Um dragão morto-vivo é Dragão ou Morto-vivo? Para o Caçador, isso decide a Perícia. A regra mais simples é um Tipo por criatura, escolhido pelo que ela é agora (o dragão morto-vivo é Morto-vivo).
5. **Os tipos não têm descrição (observação).** A lista só tem nomes. A fronteira entre Besta e Monstruosidade, ou entre Morto-vivo e Espírito (um fantasma é o quê?), fica com o Narrador. Isso pesa pouco hoje, porque só o Caçador usa o Tipo, e nas duas fronteiras mais confusas os dois lados usam a mesma Perícia: Besta e Monstruosidade usam Natureza; Morto-vivo e Espírito usam Ocultismo. Não proponho descrições agora; fica para quando mais regras usarem o Tipo.

### Texto e estrutura

6. **O índice de Criaturas está claro e enxuto.** A linha do Readme também.
7. **A Tipos de Criatura está no lugar certo,** mas também aparece no índice de Personagens (grupo Natureza), o que é útil, porque personagens também têm Tipo.

## Propostas

### P-29.1 · Efeito mecânico e tipos novos (problema objetivo)

Trocar o último parágrafo por:

> O Tipo de Criatura só tem efeito quando uma regra o cita, como o [Caçador](../Compet%C3%AAncias/Ca%C3%A7ador.md). Fora isso, ele serve como referência para o Narrador e como base para regras futuras, como Capacidades, Resistências ou efeitos que afetem apenas certos tipos. Cenários e módulos podem adicionar novos tipos e devem dizer como as regras que citam tipos os tratam.

### P-29.2 · "Sem tipo" e um Tipo por criatura (lacuna)

- **(a) Tirar "Sem tipo"** e trocar a frase por:

> Cada criatura tem **um único Tipo**: o que melhor descreve o que ela é agora. Um dragão morto-vivo, por exemplo, é Morto-vivo.

- **(b) Manter "Sem tipo"**, acrescentar a frase do Tipo único, e definir no Caçador que uma criatura Sem tipo é presa e usa Ocultismo.

**Recomendo (a).** Fecha as duas lacunas com uma frase e não cria regra nova no Caçador.

## Decisões do autor (2026-11-02)

- **P-29.1:** aprovada (D-055).
- **P-29.2:** opção (a). Não existe criatura sem tipo: cada criatura tem um único Tipo, o que ela é agora (D-055).
