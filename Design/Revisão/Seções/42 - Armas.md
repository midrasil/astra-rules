# 42 · Armas

**Arquivo:** `Regras/Equipamentos/Armas.md` (e `en/`)
**Relacionadas:** Catálogo de Armas (seção 43), Confrontar, Manobras, Progressão (custos de XP), Perícias, Criação (Teto na criação: 4), Ambidestro, Aparador (Q-013), Características de NPC, `Design/Equipamentos/Conversão de Maestrias em Propriedades.md`
**Pendências que chegam aqui:** Q-008 / D-020 (maestria de armas), Q-013 (Aparador × Escudo)
**Status:** concluída (PR #64, mergeado em 2026-11-04)

## O que está estabelecido

- Campos: Nome, Descrição, Dano, Tipo de Dano, Propriedades, Alcance, Carga, Valor.
- **Desarmado:** Dano +0, Contusão, superficial, sempre disponível.
- **Propriedades** em cinco categorias: Origem e Material (obrigatórias), Empunhadura, Uso e Especial (opcionais; Especial no máximo uma).
- **Especial:** Letal, Varredura, Debilitante (Abalado) e Debilitante (Lento). Hoje qualquer personagem que empunhe a arma usa a Propriedade Especial.
- **D-020 (direção aprovada na seção 03):** cada arma pode ter uma maestria, tirada de um catálogo. Quando uma Perícia de Ataque chega a 5, o personagem ganha a maestria de **uma arma específica**; cada arma a mais custa **3 XP**. Ficou para esta seção decidir se a categoria Especial vira o catálogo de maestrias, a linha de Progressão, a arma com duas Perícias, o Desarmado, os NPCs e as sobreposições com Competências.

## Análise

### Maestria (D-020)

1. **Especial deve virar Maestria (recomendação).** As quatro Propriedades Especiais vieram das antigas maestrias (ver `Conversão de Maestrias em Propriedades.md`), cada arma já tem no máximo uma, e o catálogo já está distribuído. Criar outro catálogo ao lado delas daria duas camadas parecidas para aprender. Proponho só renomear "Especial" para **Maestria** e exigir domínio da arma para usá-la.
2. **Consequência que você precisa pesar.** Com o Teto na criação em 4, **nenhum personagem começa com maestria**. Até alguém comprar uma Perícia de Ataque 5 (15 XP a partir de 4, cerca de 8 sessões no ritmo padrão), uma Espada Longa e uma Cimitarra diferem só em Dano, Tipo e Propriedades estruturais. Acho isso aceitável, porque a maestria passa a ser o marco do especialista, que é o objetivo da D-020. Se você quiser que a diferença apareça desde o início, a alternativa é manter a Propriedade Especial para todos e deixar a Maestria para um catálogo novo, mais forte, no futuro.
3. **Arma com duas Perícias.** A Adaga ataca com Lutar e é arremessada com Arremessar. Como a D-020 diz que a maestria é da arma, proponho: para dominar uma arma, basta ter 5 em **uma** das Perícias que ela usa; o domínio vale em qualquer Ataque com ela.
4. **Desarmado.** Hoje não tem Propriedade Especial, então não tem Maestria. Proponho manter assim; uma Competência de luta desarmada pode dar algo no futuro.
5. **NPCs.** NPCs não compram com XP. Proponho: um NPC domina as armas que o Narrador indicar na ficha, normalmente as de quem tem a Perícia de Ataque em 5.
6. **Competências.** Procurei menções a Letal, Varredura e Debilitante nas Competências: não há nenhuma. Nada a ajustar.

### Outras observações

7. **"Leve" não tem efeito próprio (clareza).** A descrição é só "arma ágil e equilibrada". O único efeito vem de Ambidestro, que exige arma Leve na mão secundária. Quem lê Armas pensa que falta uma regra. Proponho dizer: "não tem efeito próprio; algumas Capacidades exigem armas Leves, como [Ambidestro](...)".
8. **A tabela de campos não bate com o catálogo (texto).** Tem "Descrição", que o catálogo não usa, e não tem Empunhadura, Material e Especial, que o catálogo usa como colunas. Proponho alinhar a tabela às colunas do catálogo.
9. **Pesado tem uma frase sem sentido (texto).** "Não faz Força contribuir novamente para o dano": Força nunca soma ao dano no Astra. Proponho tirar "novamente para o dano" e deixar "não acrescenta dados nem Dano".
10. **Q-013 (Aparador × Escudo) fica para a seção 45.** A comparação é sobre o que o Escudo oferece; ela cabe melhor em Escudos.

## Propostas

### P-42.1 · Maestria (aplica a D-020)

- A categoria **Especial** passa a se chamar **Maestria**, com no máximo uma por arma. O texto diz: "A Maestria é um efeito característico do modelo da arma. Só a usa quem **domina** aquela arma."
- Nova seção **Domínio de arma**:
  - quando uma Perícia de Ataque (Lutar, Atirar ou Arremessar) chega a **5**, o personagem escolhe **uma arma específica** que use essa Perícia e passa a dominá-la;
  - cada arma a mais custa **3 XP**, desde que o personagem tenha 5 em uma das Perícias que ela usa;
  - o domínio é da arma, não do efeito: dominar a Espada Longa não libera Letal na Adaga;
  - o domínio vale em qualquer Ataque com a arma, qualquer que seja a Perícia usada;
  - o Desarmado não tem Maestria;
  - um NPC domina as armas que o Narrador indicar na ficha.
- **Progressão:** nova linha na tabela de custos: "Dominar uma arma a mais | 3 XP".
- **Catálogo de Armas:** a coluna "Especial" vira "Maestria" (a revisão do catálogo é a seção 43).
- **Alternativa:** manter a Propriedade Especial para todos e deixar a Maestria para um catálogo novo no futuro.

### P-42.2 · Texto

- **Leve:** "arma ágil e equilibrada. Não tem efeito próprio; algumas Capacidades exigem armas Leves, como [Ambidestro](../Compet%C3%AAncias/Ambidestro.md)."
- **Tabela de campos:** Nome, Dano, Tipo de Dano, Empunhadura, Alcance, Outras Propriedades, Maestria, Material, Carga e Valor, na ordem do catálogo; sai "Descrição".
- **Pesado:** sai "e não faz Força contribuir novamente para o dano".

## Decisões do autor (2026-11-03)

- "concordo com tudo, pode ir para maestria": P-42.1 e P-42.2 aprovadas como propostas (D-068). A Q-013 fica para a seção 45.
