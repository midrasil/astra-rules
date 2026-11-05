Uma **Vulnerabilidade** é um valor associado a um [Tipo de Dano](../Equipamentos/Armas.md#tipos-de-dano) ou [Material](../Equipamentos/Armas.md#material-obrigat%C3%B3rio-um-por-arma) específico, que deixa o personagem mais suscetível ao dano correspondente. Ela sempre acompanha um valor — por exemplo, **Vulnerabilidade a Gelo 2** ou **Vulnerabilidade a Prata 3**.

No cálculo da [Absorção Efetiva](Resist%C3%AAncia%20e%20Vulnerabilidade.md#absor%C3%A7%C3%A3o-efetiva), as Vulnerabilidades ao Tipo de Dano e ao Material da arma são somadas e **subtraem** da absorção. Por isso, uma Vulnerabilidade consome a [Absorção da armadura](../Equipamentos/Armaduras.md#absor%C3%A7%C3%A3o) antes de se tornar dano extra.

Por enquanto, Vulnerabilidades a Materiais são definidas diretamente nos personagens e criaturas.

Quando a Absorção Efetiva é **negativa** e o personagem sofre pelo menos 1 ponto de dano daquela fonte:

- o valor negativo é somado ao dano recebido (em módulo);
- todo o dano é então **agravado** — nenhuma conversão é possível, mesmo que o dano recebido seria superficial originalmente.

Por exemplo, um personagem com **Absorção 2** e **Vulnerabilidade a Fogo 3** tem Absorção Efetiva -1 contra Fogo; um dano de **1 de Fogo** torna-se **2 de dano agravado**.

---

← [Voltar para Resistência e Vulnerabilidade](Resist%C3%AAncia%20e%20Vulnerabilidade.md)
