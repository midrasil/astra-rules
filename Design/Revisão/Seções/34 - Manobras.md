# 34 · Manobras

**Arquivo:** `Regras/Cenas e Conflitos/Ações/Manobras.md` (e `en/`)
**Relacionadas:** Confrontar (D-059, Alvo sem Resposta), Mirando, Agarrado, Caído, Tamanho, Armas (Manobra (X), Pesado, Natural, Acoplada), Trocar Equipamento, Atirador, Sentinela
**Status:** em análise

## O que está estabelecido

- Uma Manobra custa a **Ação** e, quando tem alvo, é uma rolagem oposta. Empate: nada acontece. Nenhuma Manobra causa dano.
- As Reservas são fixas; só Capacidades, equipamentos e regras expressas as trocam.
- **Manobra (X)** numa arma permite a Manobra até o Alcance da arma, sem bônus.
- **Manobras Narrativas:** o Narrador monta Reserva, resistência e efeito para tentativas não previstas.

| Manobra | Quem inicia | Alvo resiste | Efeito | Limite de Tamanho |
| --- | --- | --- | --- | --- |
| Reposicionar | Força + Atletismo | Força + Atletismo | desloca o alvo 1 quadrado | até 1 categoria maior |
| Derrubar | Força + Atletismo | Força + Atletismo | alvo fica Caído | até 1 categoria maior |
| Agarrar | Força + Atletismo | Força + Atletismo | alvo fica Agarrado | até 1 categoria maior |
| Desarmar | Agilidade + Lutar | Agilidade + Lutar | alvo larga o item no próprio quadrado | nenhum |
| Mirar | sem rolagem | — | +1 acúmulo de Mirando (+2 dados no próximo Ataque à distância, até Astúcia acúmulos) | — |

## Análise

### Mecânica

1. **O desenho geral é bom.** Uma rolagem oposta, empate a favor do alvo (o contrário do Confronto, o que faz sentido: quem tenta controlar precisa vencer) e efeitos simples, sem dano. Não encontrei abuso.
2. **Falta o caso do alvo que não pode ou não quer resistir (lacuna).** Confrontar tem "Alvo sem Resposta" (o alvo conta como 1 Sucesso), mas Manobras não diz nada. Hoje não se sabe como Derrubar um alvo inconsciente nem se um aliado pode deixar-se Reposicionar para sair de perigo. Proponho usar a mesma regra do Confronto para quem não pode resistir, e deixar que o alvo aceite a Manobra sem rolagem.
3. **O alcance de Reposicionar é vago (problema objetivo pequeno).** "Adjacente ou dentro do alcance apropriado para a forma como o reposicionamento está sendo realizado" deixa a porta aberta para empurrar alguém de longe com uma descrição. As quatro Manobras com alvo exigem a mesma coisa: estar adjacente, ou até o Alcance da arma com Manobra (X). Isso pode ficar uma vez só em "Realizando uma Manobra".
4. **A queda de Reposicionar aponta para uma regra que não existe (lacuna).** "As consequências decorrentes da queda ou do ambiente são resolvidas normalmente", mas o núcleo não tem regra de dano de queda (procurei em Movimento, Saltar e Perícias). Isso não se resolve aqui: registro como Q-016 para as seções de Movimento (38 a 40).
5. **Força domina três das quatro Manobras (observação, preferência).** Reposicionar, Derrubar e Agarrar usam Força + Atletismo dos dois lados, e escapar do agarrão também. Um personagem ágil não tem uma defesa própria contra elas, ao contrário do Confronto, onde pode Esquivar. Daria para deixar o alvo resistir com Agilidade + Acrobacia em Reposicionar e Derrubar, mas isso adiciona uma escolha a cada Manobra. **Recomendo manter como está:** é simples, dá a Força um papel claro no combate e as Competências podem abrir exceções.
6. **Mirar sozinho rende pouco (observação).** Uma Ação de Mirar dá +2 dados (cerca de +1 Sucesso), e na maioria dos casos dois Ataques valem mais do que um Ataque com +1 Sucesso. Mirar compensa contra alvos com boa defesa ou além do Alcance (onde anula a penalidade de -2), e é a base de Atirador, que dá acúmulos sem gastar a Ação. **Não proponho mudança:** o papel dele é esse.
7. **Mirar não diz se o bônus vale para outro alvo (ambiguidade pequena).** "Concentrando-se no alvo" sugere um alvo fixo, mas a regra diz "próximo Ataque à distância". Proponho deixar claro que vale para qualquer alvo, o que evita controlar em quem se mirou.
8. **O fim do agarrão está incompleto (lacuna, fora desta página).** Agarrado só termina quando o alvo escapa. Não diz se quem agarra pode soltar, se o agarrão acaba quando os dois deixam de estar adjacentes (por um Reposicionar, por exemplo) ou quando quem agarra fica Incapacitado, nem se agarrar exige uma mão livre. Registro como Q-017 para a seção de Condições (48).

### Texto e estrutura

9. **Mirar está escrito duas vezes, e as duas versões divergem (problema objetivo).** A Manobra e a Condição [Mirando](../../../Regras/Condições/Mirando.md) repetem bônus, limite e perda da Mira, mas cada uma tem algo que a outra não tem:
   - só a Manobra diz que o bônus não serve para responder a um Ataque;
   - só a Condição diz que ela termina no fim do combate e que uma Capacidade pode manter a Mira depois do Ataque (Atirador usa isso).
   A Condição é a referência única das Condições, então as regras devem ficar nela. A Manobra só diz o custo e o efeito: "recebe 1 acúmulo de Mirando".
10. **Cada Manobra com alvo repete o mesmo bloco.** Alcance físico, "Em caso de empate ou vitória do alvo, nada acontece" e "não causa dano" aparecem quatro vezes, e o limite de Tamanho três. Uma tabela como a de cima, em "Realizando uma Manobra", com as regras comuns escritas uma vez, deixa cada Manobra com só o que é dela.
11. **"Manobras e Capacidades" diz pouco em três parágrafos.** O que importa (Capacidades podem melhorar Manobras e prevalecem) já está em "Realizando uma Manobra". Proponho tirar a seção.
12. **A introdução tem dois parágrafos que dizem a mesma coisa.** Dá para dizer em um.

## Propostas

### P-34.1 · Alvo que não resiste e alcance (lacunas)

Em "Realizando uma Manobra", acrescentar:

- "As Manobras com alvo exigem que você esteja adjacente a ele, ou até o Alcance de uma arma com [Manobra (X)](../../Equipamentos/Armas.md#uso-opcional)."
- "Um alvo pode aceitar a Manobra; nesse caso, ela funciona sem rolagem. Um alvo que não pode resistir segue a regra de [Alvo sem Resposta](Confrontar.md#alvo-sem-resposta): o resultado dele conta como 1 Sucesso."
- Em Reposicionar, Derrubar, Agarrar e Desarmar, sai a frase própria sobre alcance.

### P-34.2 · Mirar remete a Mirando (texto e lacuna)

- A seção Mirar fica assim: "Você usa sua Ação para se concentrar antes de um Ataque à distância e recebe 1 acúmulo de [Mirando](../../Condi%C3%A7%C3%B5es/Mirando.md). Cada acúmulo dá +2 dados no próximo Ataque à distância, contra qualquer alvo. Você pode se mover antes de Mirar, mas os acúmulos se perdem se você se mover depois, entre outros casos descritos na Condição."
- As regras (limite por Astúcia, perda da Mira, fim no Ataque e no fim do combate) ficam só em Mirando, que ganha a frase que faltava: "Os acúmulos não se aplicam às respostas a um Confronto." e "contra qualquer alvo" na primeira frase.
- O título "Mirar" continua o mesmo, porque Mirando aponta para ele.

### P-34.3 · Tabela e menos repetição (texto e estrutura)

- Introdução: um parágrafo só ("As **Manobras** são ações para obter vantagem numa Cena Tática sem causar dano: mudar a posição ou a Condição de outro personagem, tirar algo das mãos dele ou preparar um Ataque.").
- Em "Realizando uma Manobra", a tabela de Manobras e as regras comuns: "Nenhuma Manobra causa dano." e "Reposicionar, Derrubar e Agarrar só afetam alvos de até uma categoria de [Tamanho](../../Personagens/Tamanho.md#limite-de-tamanho) maior que você."
- Cada Manobra fica só com o que é dela: Reposicionar com a direção e "Obstáculos e Bordas" (sem a subseção "Sem Dano"); Derrubar e Agarrar com o link da Condição; Desarmar com o que pode ser desarmado e como recuperar o item.
- Sai a seção "Manobras e Capacidades".
- Os títulos das Manobras continuam os mesmos, porque outras páginas apontam para eles.
- **Alternativa:** só tirar as repetições, sem tabela.

### Fica para depois

- **Q-016 · Dano de queda** (seções 38 a 40).
- **Q-017 · Fim do agarrão e mão livre** (seção 48).
- Resistência por Agilidade (item 5): não proponho, a não ser que você prefira.
