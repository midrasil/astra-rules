# 41 · Equipamentos (índice, carga e Sobrecarga)

**Arquivo:** `Regras/Equipamentos/Equipamentos.md` (e `en/`)
**Relacionadas:** Armas, Armaduras, Escudos e seus catálogos, Características Derivadas (Carga máxima), Vida (Tratamento, Q-009), Iluminação (fontes de luz, D-063), Movimentação (D-064)
**Status:** em análise

## O que está estabelecido

- Quatro tipos: Armas, Armaduras, Escudos e Itens comuns. Os três primeiros têm catálogo.
- **Valor:** número abstrato, sem moeda. Os valores dos catálogos seguem os preços em peças de ouro do D&D 5e (Adaga 2, Espada Curta 10, Martelo de Guerra 15).
- **Carga:** cada item ocupa N "slots". Carga máxima = 5 + Força.
- **Sobrecarga:** acima da Carga máxima, Movimentação base pela metade e -2 dados em rolagens com Atributo Físico.

## Análise

### Mecânica

1. **Carga em espaços é boa.** É mais rápida que pesar em quilos e combina com a ficha. A Sobrecarga tem duas penalidades claras e termina sozinha. Não proponho mudar a fórmula.
2. **Os Itens comuns não existem (lacuna, fecha a Q-009).** A página diz que são um dos quatro tipos, mas não há catálogo, nem Carga, nem Valor. Isso já causou dois buracos:
   - o Tratamento (Vida) exige "material de cura", que não existe como item (Q-009);
   - Iluminação (D-063) agora tem vela, tocha e lampião, sem Valor nem Carga.
   Proponho um **Catálogo de Itens** curto, com os itens que as regras já usam e alguns básicos de aventura. Como os catálogos já seguem os preços do 5e, uso os mesmos.
3. **Itens muito pequenos (lacuna).** Uma vela ocupar 1 de Carga, como uma adaga, é estranho, mas Carga 0 sem limite permite carregar cem velas. Proponho Carga 0 para itens muito pequenos, contando cada 10 deles como 1.
4. **Sobrecarga sem teto (lacuna pequena).** Hoje um personagem pode carregar dez vezes a Carga máxima com só metade da Movimentação. No 5e, o limite para empurrar ou arrastar é o dobro da capacidade. Proponho: acima do dobro da Carga máxima, o personagem não consegue se mover carregando tudo.

### Texto e estrutura

5. **"Slots" é anglicismo (pendência registrada antes).** A unidade não é necessária: a Carga pode ser só um número, como Dano ou Alcance. "Ocupa 2 slots" vira "Carga 2", e "Carga máxima: 5 + Força slots" vira "5 + Força". Isso toca as tabelas de campos de Armas, Armaduras e Escudos e a tabela de Características Derivadas.
6. **"Uso durante cenas" diz pouco.** Ela só aponta para Trocar Equipamento e para Cenas e Conflitos. Fica, porque o link para Trocar Equipamento é útil; não mudaria.

## Propostas

### P-41.1 · Sem "slots" (texto)

- Em Equipamentos: "No Astra, o espaço que um item ocupa é medido pela sua **Carga**, um número inteiro. A Carga máxima de um personagem é **5 + Força**." Saem as menções a "slots".
- Nas tabelas de campos de Armas, Armaduras e Escudos, "quantos slots ocupa" vira "quanto ocupa da Carga máxima".
- Em Características Derivadas, "**5 + Força** slots" vira "**5 + Força**".

### P-41.2 · Catálogo de Itens (lacuna, fecha a Q-009)

Novo arquivo `Regras/Equipamentos/Catálogo de Itens.md` (e `en/`), listado em Equipamentos junto dos outros catálogos. Valores em peças de ouro do 5e; Carga pensada para a escala do Astra.

| Item | Carga | Valor | Uso |
|---|---:|---:|---|
| Kit de Cura | 1 | 5 | material de cura para o [Tratamento](../Personagens/Vida.md#tratamento); 10 usos, cada Tratamento gasta 1 |
| Vela | 0 | 0,01 | fonte de luz (Claro 1 + Penumbra 1), dura 1 hora |
| Tocha | 1 | 0,01 | fonte de luz (Claro 4 + Penumbra 4), dura 1 hora; pode ser usada como Arma Improvisada |
| Lampião | 1 | 5 | fonte de luz (Claro 6 + Penumbra 6), dura 6 horas por frasco de óleo |
| Frasco de óleo | 0 | 0,1 | combustível do lampião |
| Corda (15 m) | 1 | 1 | — |
| Mochila | 1 | 2 | — |
| Saco de dormir | 1 | 1 | — |
| Ração (1 dia) | 0 | 0,5 | — |
| Cantil | 0 | 0,2 | — |
| Pé de cabra | 1 | 2 | — |
| Ferramentas de ladrão | 1 | 25 | — |

E a regra: "Itens de **Carga 0** são muito pequenos. A cada 10 itens de Carga 0, conte **1** de Carga."

Em Iluminação, a tabela de fontes de luz ganha um link para o Catálogo de Itens. Em Vida, "material de cura" ganha um link para o Kit de Cura.

- **Alternativa:** só o Kit de Cura e as três fontes de luz, os itens que as regras já citam.

### P-41.3 · Teto da Sobrecarga (lacuna)

Em Sobrecarga: "Acima do **dobro** da Carga máxima, o personagem não consegue se mover carregando tudo."

- **Alternativa:** sem teto, como está.
