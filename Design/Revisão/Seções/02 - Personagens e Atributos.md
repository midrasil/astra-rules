# 02 · Personagens (índice) + Atributos

**Arquivos:** `Regras/Personagens/Personagens.md`, `Regras/Personagens/Atributos.md` (e as versões em `en/`)
**Status:** concluída (PR #24, mergeado em 2026-11-02)

## O que está estabelecido

- **Índice de Personagens.** Agrupa as páginas em Criação, Capacidades (Atributos e Perícias), Natureza (Tamanho e Tipos de Criatura), Recursos (Vida, Vontade e Descanso), Identidade e personalização (Ambição, Convicções e Competências) e Progressão.
- **Atributos.** São seis, em duas categorias:
  - **Físicos:** Força, Agilidade e Vigor.
  - **Espirituais:** Carisma, Determinação e Astúcia.

  A página repete as regras de categoria, de Atributo vinculado e de substituição. Ela acrescenta as substituições em fórmulas fixas (Vida, Vontade, Carga e Iniciativa). Cada Atributo tem uma descrição, as Perícias vinculadas e os usos derivados.
- **Escala.** A escala de valores (1 a 5, "1 = fraco, 2 = médio, 5 = auge humano") **não está nesta página**. Ela só aparece em `Criação de Personagem/2 - Atributos e Perícias.md`.

### Distribuição de uso

| Atributo | Perícias vinculadas | Outros usos |
| --- | --- | --- |
| Força | 2 (Atletismo, Arremessar) | Carga, armas Pesadas, maioria das Manobras, Defender |
| Agilidade | 8 | Ataques corpo a corpo e de disparo, Esquivar |
| Vigor | 0 | Vida, Descanso, resistência física (por exemplo veneno) |
| Carisma | 5 | — |
| Determinação | 0 | Vontade, Iniciativa, resistência mental |
| Astúcia | 9 | Iniciativa, limite de Mirando, resistência mental |

As listas de Perícias de cada Atributo conferem com a tabela de Perícias.

## Análise

1. **A página repete a Reserva de Dados (texto).** As seções "Categorias" (no parágrafo das penalidades) e "Atributos vinculados e substituições" repetem regras que a Reserva de Dados acabou de consolidar (D-009). A tabela de Perícias também tem uma seção com o mesmo nome; ela será revisada na seção 03. Só uma informação é exclusiva desta página: as substituições em fórmulas fixas.
2. **A escala de valores está no lugar errado (estrutura).** O que significa ter Força 1 ou 5 é regra do Atributo, não da criação. Hoje quem lê Atributos não descobre o intervalo nem o significado.
3. **"Capacidades" com dois sentidos (terminologia, objetivo).** No sistema, **Capacidade** é o termo definido para o que as Competências concedem. Mas:
   - o índice de Personagens usa "## Capacidades" como título do grupo Atributos e Perícias;
   - Atributos abre com "capacidades fundamentais".
4. **Vigor e Determinação não têm Perícias (design, pergunta ao autor).** Os dois funcionam como Atributos de **resistência**: entram sozinhos ou em par nas Reservas de resistência (Venenosa: Vigor + Determinação; Duelista: Determinação + Astúcia) e nas fórmulas de Vida, Vontade e Iniciativa. Por XP, eles compram menos usos que Agilidade ou Astúcia. Isso pode ser intencional, como Vigor e Autocontrole no Storyteller, mas o texto não diz.
5. **O índice de Personagens funciona.** Os links para outras áreas (Criação, Tipos de Criatura, Competências) ajudam a navegar. A única mudança proposta nele é a do item 3.

## Propostas

### P-02.1 · Tirar a repetição com a Reserva de Dados (texto)

- **Categorias:** fica a tabela e uma frase: "Algumas penalidades afetam apenas rolagens de uma categoria; veja [Penalidades](Reserva de Dados#penalidades)".
- **Atributos vinculados e substituições:** vira um parágrafo com link para [Substituições de Atributo]. A regra exclusiva das fórmulas fixas (Vida, Vontade, Carga e Iniciativa) fica na página.
- **Consequência:** a página fica menor e a regra passa a existir em um lugar só. Nenhuma regra muda.

### P-02.2 · Levar a escala de valores para Atributos (estrutura)

Acrescentar uma seção **Escala**:

> Atributos de personagens variam de **1 a 5**: 1 é fraco, 2 é a média de um adulto comum, 3 é notável, 4 é excepcional e 5 é o auge humano.

A Criação de Personagem fica só com a distribuição inicial e o limite de 4 na criação.

- **Por quê:** a regra fica onde o leitor a procura.
- **Questão:** criaturas podem passar de 5? Fica para a seção 30 (Q-007).
- **Atenção:** os níveis 3 e 4 ("notável" e "excepcional") são acréscimo meu. O original só define 1, 2 e 5. O autor pode preferir manter só esses três.

### P-02.3 · Tirar o conflito com "Capacidade" (terminologia)

- No índice de Personagens, "## Capacidades" passa a ser "## Atributos e Perícias".
- Em Atributos, "capacidades fundamentais" passa a ser "aptidões fundamentais".
- **Consequência:** a palavra Capacidade fica reservada ao termo das Competências. Em `en/`, "Capabilities" também precisa sair do índice.

### P-02.4 · Papel de Vigor e Determinação (pergunta ao autor)

Se a falta de Perícias for intencional, recomendo **dizer isso no texto**: Vigor e Determinação são os Atributos de resistência, usados sozinhos ou em par para resistir a efeitos físicos e mentais. Não há mudança mecânica.

Se não for intencional, as alternativas são:

- vincular Perícias existentes a eles;
- aceitar a diferença de valor por XP.

Eu não recomendaria nenhuma das duas sem discutir Perícias (seção 03).
