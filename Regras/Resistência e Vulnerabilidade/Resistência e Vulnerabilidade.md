Esta seção reúne as regras que definem como personagens e criaturas reagem a dano de [Tipos de Dano](../Equipamentos/Armas.md#tipos-de-dano) e [Materiais](../Equipamentos/Armas.md#material-obrigat%C3%B3rio-um-por-arma) específicos, através de **Resistências**, **Vulnerabilidades** e **Imunidades**.

Elas podem ser concedidas por equipamentos, condições, origens, criaturas, magias ou efeitos.

## Conceitos

- [Resistência](Resist%C3%AAncia.md) — valor que contribui para converter dano agravado em dano superficial.
- [Vulnerabilidade](Vulnerabilidade.md) — valor que reduz a absorção e aumenta o dano recebido.
- [Imunidade](Imunidade.md) — sem valor; o dano do Tipo ou Material simplesmente não se aplica.

As Resistências, Vulnerabilidades e Imunidades a Materiais são, por enquanto, definidas diretamente nos personagens e criaturas. Armaduras continuam concedendo Resistências apenas a Tipos de Dano.

## Absorção Efetiva

Ao sofrer dano, calcula-se a **absorção efetiva** considerando o [Tipo de Dano](../Equipamentos/Armas.md#tipos-de-dano) recebido e o Material da arma que o causou, quando houver:

> **Absorção Efetiva** = [Absorção da armadura](../Equipamentos/Armaduras.md#absor%C3%A7%C3%A3o) + Σ [Resistências](Resist%C3%AAncia.md) ao Tipo e ao Material − Σ [Vulnerabilidades](Vulnerabilidade.md) ao Tipo e ao Material

Os valores do Tipo e do Material são somados. Quando a fonte de dano não tem Material, apenas o Tipo de Dano é considerado.

- **Absorção efetiva maior ou igual ao dano agravado:** todo o dano é convertido em dano superficial.
- **Absorção efetiva entre 0 e o dano:** apenas a parte coberta pela absorção é convertida; o excedente permanece agravado (ver [Armaduras](../Equipamentos/Armaduras.md)).
- **Absorção efetiva negativa:** o valor negativo é somado ao dano recebido (em módulo) e todo o dano é agravado — nenhuma conversão é possível (ver [Vulnerabilidade](Vulnerabilidade.md)).
- Dano que já é **superficial** não é afetado pela absorção positiva.
- A [Imunidade](Imunidade.md) ao Tipo ou ao Material prevalece sobre tudo: o dano é ignorado antes mesmo de calcular a absorção efetiva, mesmo que haja Vulnerabilidade ao outro.

## Exemplos

- Personagem com **Absorção 1** e **Resistência a Fogo 3** sofre **4 de dano de Fogo**: a absorção efetiva é 4, e os 4 pontos são convertidos em dano superficial.
- Personagem com **Vulnerabilidade a Fogo 3** e **Absorção 0** sofre **1 de dano de Fogo**: a absorção efetiva é −3, e ele recebe **4 de dano agravado de Fogo**.
- Personagem com **Imunidade a Fogo** sofre **4 de dano de Fogo**: o dano não se aplica, e nenhum dano é recebido.
- Personagem com **Absorção 2** e **Vulnerabilidade a Fogo 3** sofre **1 de dano de Fogo**: a absorção efetiva é −1, e ele recebe **2 de dano agravado de Fogo**.
- Criatura com **Absorção 0**, **Resistência a Corte 3** e **Vulnerabilidade a Prata 3** sofre dano de Corte de uma arma de Prata: a absorção efetiva é 0, pois os valores se anulam.
- Criatura com **Imunidade a Metal comum** sofre dano de uma arma de ferro ou aço: nenhum dano é recebido, independentemente do Tipo de Dano da arma. Essa Imunidade não se aplica a armas de Prata ou Meteorito.

## Relações

Os Tipos de Dano e Materiais são definidos em [Armas](../Equipamentos/Armas.md). A gravidade do dano e sua recuperação estão descritas em [Vida](../Personagens/Vida.md).

O dano causado por [Zonas](../Cenas%20e%20Conflitos/Zonas.md) não utiliza a Absorção Efetiva. Nesse caso, Resistências contam como Sucessos automáticos no teste para resistir, Vulnerabilidades aumentam diretamente o Dano da Zona e Imunidades impedem completamente o dano.

---

← [Voltar ao Astra](../../Readme.md)
