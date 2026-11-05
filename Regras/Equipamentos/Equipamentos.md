Equipamentos são os objetos que os personagens carregam e utilizam, seja para atacar, se proteger ou realizar outras tarefas.

Atualmente o núcleo do Astra organiza os equipamentos em **quatro tipos**:

- [Armas](Armas.md) — equipamentos utilizados para atacar.
- [Armaduras](Armaduras.md) — equipamentos utilizados para proteção.
- [Escudos](Escudos.md) — equipamentos utilizados para defesa.
- **Itens comuns** — objetos de uso cotidiano, como mochilas, cordas e ferramentas.

Os equipamentos disponíveis no núcleo estão reunidos em:

- [Catálogo de Armas](Cat%C3%A1logo%20de%20Armas.md);
- [Catálogo de Armaduras](Cat%C3%A1logo%20de%20Armaduras.md);
- [Catálogo de Escudos](Cat%C3%A1logo%20de%20Escudos.md);
- [Catálogo de Itens](Cat%C3%A1logo%20de%20Itens.md).

Novos tipos de equipamento podem ser adicionados futuramente, através de módulos ou cenários específicos.

## Valor

Todo equipamento possui um **Valor**, usado para comparar preços e montar orçamentos. O Valor é um número abstrato e pode conter casas decimais; o cenário determina o nome da moeda, sua disponibilidade e as regras de compra.

## Uso durante cenas

- [Trocar Equipamento](Trocar%20Equipamento.md) — sacar, guardar e trocar equipamentos durante a Cena Tática.
- [Cenas e Conflitos](../Cenas%20e%20Conflitos/Cenas%20e%20Conflitos.md) — regras para confrontos e outras decisões táticas.

## Carga

O peso dos equipamentos **não é medido em quilogramas**. No Astra, o espaço que um item ocupa é medido pela sua **Carga**, um número inteiro. Isso se aplica igualmente a armas, armaduras, escudos e itens comuns. Itens muito pequenos têm Carga 0 (ver [Catálogo de Itens](Cat%C3%A1logo%20de%20Itens.md)).

### Carga máxima

A **Carga máxima** de um personagem é o total de Carga que ele consegue carregar sem penalidades. Sua fórmula padrão é:

> **5 + Força**

Força é o **Atributo da Carga** por padrão. Capacidades e outras regras podem substituí-la nessa fórmula. Quando isso acontecer, a Carga máxima é recalculada imediatamente a partir do novo Atributo, sem alterar testes de Força ou outras regras.

### Sobrecarga

Carregar além da **Carga máxima** deixa o personagem em **Sobrecarga**. Enquanto estiver em Sobrecarga, ele:

- tem sua **Movimentação base** reduzida à **metade** (ver [Movimentação](../Movimento/Movimenta%C3%A7%C3%A3o.md));
- sofre **-2 dados** em rolagens que utilizem um [Atributo Físico](../Personagens/Atributos.md#categorias).

Acima do **dobro** da Carga máxima, o personagem não consegue se mover carregando tudo.

A Sobrecarga termina assim que a Carga volta a ficar dentro do limite.

---

← [Voltar ao Astra](../../Readme.md)
