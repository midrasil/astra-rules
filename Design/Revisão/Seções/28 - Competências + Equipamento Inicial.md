# 28 · Competências + Equipamento Inicial

**Arquivos:** `Criação de Personagem/4 - Competências.md` e `Criação de Personagem/5 - Equipamento Inicial.md` (e `en/`)
**Relacionadas:** Competências (seção 11; D-037: a Criação de Personagem é a única fonte da regra de criação), Progressão, Equipamentos (Valor, Carga, Sobrecarga), Catálogos de Armas, Armaduras e Escudos, Características Derivadas (D-053), Q-003, Q-009
**Status:** concluída (PR #50, mergeado em 2026-11-02)

## O que está estabelecido

- **Competências:** 2 Pontos de Competência. Cada ponto dá 1 Nível: Nível 2 em uma Competência ou Nível 1 em duas. Os Níveis contam para o Nível Total. Pontos não usados não viram XP.
- **Equipamento Inicial:** o cenário define o equipamento, com um pacote pronto ou um orçamento em Valor para comprar dos catálogos. O núcleo tem catálogos de armas, armaduras e escudos. A Carga máxima é normalmente 5 + Força, e passar dela causa Sobrecarga.

## Análise

### Mecânica

1. **Os 2 Pontos de Competência funcionam.** Em XP, valem 9 (3 pelo primeiro Nível e 6 pelo segundo), o que é pouco perto das Perícias (90 XP, D-053) e dos Atributos. Mas o valor das Competências não está no custo: elas são o que diferencia os personagens, e começar com 1 ou 2 Níveis dá identidade sem dar poder demais. Não proponho mudança.
2. **"Pontos não utilizados não são convertidos em XP" deixa uma dúvida (lacuna).** A frase sugere que o jogador pode não usar os pontos, mas não diz se ele pode guardá-los para depois (por exemplo, para escolher a Competência na segunda sessão). Se a resposta é não, basta dizer que os pontos são usados na criação.
3. **O núcleo não tem equipamento inicial padrão (lacuna, decisão do autor).**
   - A página manda o cenário decidir, com pacote ou orçamento. Mas quem joga só com o núcleo não tem número nenhum: os catálogos têm Valor, e não há orçamento sugerido.
   - Um orçamento sugerido resolveria isso sem impor nada ao cenário. Pelos catálogos, **100 de Valor** monta um personagem típico de combate com alguma escolha:
     - Espada Longa (15) + Escudo (10) + Cota de Malha (75) = 100;
     - Arco Longo (50) + Couro Batido (45) = 95;
     - Montante (50) + Camisão de Malha (50) = 100.
     - A Placa Peitoral (400), a Armadura de Talas (200) e a Armadura Completa (1500) ficam fora, o que parece certo para o começo.
   - É um número novo, então a decisão é sua. A alternativa é manter tudo a cargo do cenário.
4. **Itens comuns e material de cura (Q-009).** A Carga fala em "itens comuns", mas o núcleo não tem catálogo deles. Isso já está na Q-009 (seção 41) e não muda aqui.

### Texto e estrutura

5. **A Carga máxima está repetida.** O último parágrafo do Equipamento Inicial repete a fórmula e a regra de substituição, que já estão em Características Derivadas. Ele também usa `5 + Força` em formato de código, enquanto o resto do sistema usa negrito. Basta um link.
6. **"Todo item tem um Valor, e a moeda usada varia conforme o cenário"** repete a seção Valor de Equipamentos sem link. Um link resolve.
7. **Nível Total sem link.** "Os Níveis adquiridos também determinam o Nível Total de Competências" não aponta para a regra.
8. **"Concedem progressões fixas de Capacidades".** O Robusto não tem Capacidades (D-050). Isso é parte da Q-003 (seção 53) e não muda aqui.

## Propostas

### P-28.1 · Pontos de Competência (lacuna)

Trocar "Pontos de Competência não utilizados não são convertidos em XP." por:

> Os pontos são usados na criação: não podem ser guardados nem convertidos em XP.

E pôr link em "Nível Total de Competências" para `../Regras/Compet%C3%AAncias/Compet%C3%AAncias.md#n%C3%ADvel-total-de-compet%C3%AAncias`.

### P-28.2 · Orçamento padrão do núcleo (decisão do autor)

- **(a) Orçamento sugerido.** Depois da lista "pacote inicial / orçamento", acrescentar:

> Sem indicação do cenário, use um orçamento de **100 de Valor**.

- **(b) Manter como está**, só a cargo do cenário.

**Recomendo (a).** É uma frase, o cenário continua podendo mudar, e o núcleo fica jogável sozinho. O número 100 é uma sugestão minha a partir dos catálogos; se preferir outro valor, é só dizer.

### P-28.3 · Equipamento Inicial (texto)

- "Todo item tem um **Valor**, e a **moeda** usada varia conforme o cenário." vira "Todo item tem um [Valor](../Regras/Equipamentos/Equipamentos.md#valor), e a **moeda** usada varia conforme o cenário."
- O último parágrafo vira:

> O personagem pode carregar itens até sua [Carga máxima](3%20-%20Caracter%C3%ADsticas%20Derivadas.md); passar disso o deixa em [Sobrecarga](../Regras/Equipamentos/Equipamentos.md#sobrecarga).

## Decisões do autor (2026-11-02)

- **P-28.1 e P-28.3:** aprovadas (D-054).
- **P-28.2:** opção (a). Sem indicação do cenário, o orçamento inicial é de 100 de Valor (D-054).
