Esta seção reúne as regras que definem como personagens e criaturas reagem a dano de [[Armas#Tipos de Dano|Tipos de Dano]] e [[Armas#Material (obrigatório, um por arma)|Materiais]] específicos, através de **Resistências**, **Vulnerabilidades** e **Imunidades**.

Elas podem ser concedidas por equipamentos, condições, origens, criaturas, magias ou efeitos.

## Conceitos

- [[Resistência|Resistência]] — valor que contribui para converter dano agravado em dano superficial.
- [[Vulnerabilidade|Vulnerabilidade]] — valor que reduz a absorção e aumenta o dano recebido.
- [[Imunidade|Imunidade]] — sem valor; o dano do Tipo ou Material simplesmente não se aplica.

As Resistências, Vulnerabilidades e Imunidades a Materiais são, por enquanto, definidas diretamente nos personagens e criaturas. Armaduras continuam concedendo Resistências apenas a Tipos de Dano.

## Absorção Efetiva

Ao sofrer dano, calcula-se a **absorção efetiva** considerando o [[Armas#Tipos de Dano|Tipo de Dano]] recebido e o Material da arma que o causou, quando houver:

> **Absorção Efetiva** = [[Armaduras#Absorção|Absorção da armadura]] + Σ [[Resistência|Resistências]] ao Tipo e ao Material − Σ [[Vulnerabilidade|Vulnerabilidades]] ao Tipo e ao Material

Os valores do Tipo e do Material são somados. Quando a fonte de dano não tem Material, apenas o Tipo de Dano é considerado.

- **Absorção efetiva maior ou igual ao dano agravado:** todo o dano é convertido em dano superficial.
- **Absorção efetiva entre 0 e o dano:** apenas a parte coberta pela absorção é convertida; o excedente permanece agravado (ver [[Armaduras]]).
- **Absorção efetiva negativa:** o valor negativo é somado ao dano recebido (em módulo) e todo o dano é agravado — nenhuma conversão é possível (ver [[Vulnerabilidade]]).
- Dano que já é **superficial** não é afetado pela absorção positiva.
- A [[Imunidade]] ao Tipo ou ao Material prevalece sobre tudo: o dano é ignorado antes mesmo de calcular a absorção efetiva, mesmo que haja Vulnerabilidade ao outro.

## Exemplos

- Personagem com **Absorção 1** e **Resistência a Fogo 3** sofre **4 de dano de Fogo**: a absorção efetiva é 4, e os 4 pontos são convertidos em dano superficial.
- Personagem com **Vulnerabilidade a Fogo 3** e **Absorção 0** sofre **1 de dano de Fogo**: a absorção efetiva é −3, e ele recebe **4 de dano agravado de Fogo**.
- Personagem com **Imunidade a Fogo** sofre **4 de dano de Fogo**: o dano não se aplica, e nenhum dano é recebido.
- Personagem com **Absorção 2** e **Vulnerabilidade a Fogo 3** sofre **1 de dano de Fogo**: a absorção efetiva é −1, e ele recebe **2 de dano agravado de Fogo**.
- Criatura com **Absorção 0**, **Resistência a Corte 3** e **Vulnerabilidade a Prata 3** sofre dano de Corte de uma arma de Prata: a absorção efetiva é 0, pois os valores se anulam.
- Criatura com **Imunidade a Metal comum** sofre dano de uma arma de ferro ou aço: nenhum dano é recebido, independentemente do Tipo de Dano da arma. Essa Imunidade não se aplica a armas de Prata ou Meteorito.

## Relações

Os Tipos de Dano e Materiais são definidos em [[Armas|Armas]]. A gravidade do dano e sua recuperação estão descritas em [[Vida|Vida]].

---

← [[Astra Engine|Voltar ao Astra Engine]]
