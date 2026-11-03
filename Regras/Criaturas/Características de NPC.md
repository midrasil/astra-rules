**Características de NPC** são capacidades próprias de NPCs, criaturas e inimigos. Elas são definidas diretamente na ficha da criatura e não pertencem ao sistema de Competências dos personagens.

Um **Ataque natural** é um Ataque feito com o corpo da criatura, como garras, mordidas, chifres ou ferrões. A ficha da criatura define seu Dano, Tipo de Dano e Alcance, como os de uma [arma](../Equipamentos/Armas.md), e ele usa **Agilidade + Lutar**, salvo quando a ficha indicar outra Reserva.

## Valores configuráveis

Cada característica traz **valores padrão** entre parênteses, como a **Potência**, a Reserva usada para resistir, a duração ou a quantidade de acúmulos. Esses valores são **configuráveis em cada criatura**: duas criaturas com a mesma característica podem ter valores diferentes.

A **Potência** é a [Dificuldade](../Mec%C3%A2nica%20B%C3%A1sica/Reserva%20de%20Dados.md#escala-de-dificuldade) do teste que o alvo faz para resistir, quando a característica pede um.

Quando uma Característica menciona uma Perícia sem escrever a Reserva completa, ela utiliza o Atributo vinculado da Perícia. Reservas formadas expressamente por dois Atributos, como Vigor + Determinação, permanecem inalteradas.

Quando uma característica não indicar a Reserva para resistir, use **Vigor + Determinação** contra efeitos no corpo e **Determinação + Astúcia** contra efeitos na mente.

## Movimentos especiais

Nadar e escalar são [Movimentação Especial](../Movimento/Movimenta%C3%A7%C3%A3o.md#movimenta%C3%A7%C3%A3o-especial) e custam 2 pontos de Movimentação por quadrado. Com uma destas características, a criatura usa aquele movimento pelo **custo normal**, 1 ponto por quadrado, e escolhe no seu Turno se usa a Movimentação com o movimento normal ou com o especial.

**Aquática** e **Voadora** podem trazer um valor entre parênteses, como **Aquática (5)**: é a Movimentação da criatura naquele meio, também pelo custo normal. Sem valor, ela usa sua Movimentação padrão. Uma criatura que só se move na água, como um tubarão, tem Movimentação 0 em terra.

### Aquática

- **Descrição:** nada pelo custo normal e respira debaixo d'água. Com valor, nada com essa Movimentação.

### Voadora

- **Descrição:** voa pelo custo normal (ver [Voo](../Movimento/Movimenta%C3%A7%C3%A3o.md#voo)), com a Movimentação do valor quando houver, e ignora Terreno Difícil no chão. Se ficar [Caída](../Condi%C3%A7%C3%B5es/Ca%C3%ADdo.md) ou [Agarrada](../Condi%C3%A7%C3%B5es/Agarrado.md) no ar, cai.

### Escavadora

- **Descrição:** cava e se move por dentro da terra pelo custo normal. Enquanto está enterrada, não pode ser alvo de Ataques.

### Escaladora

- **Descrição:** escala paredes e tetos pelo custo normal, sem precisar de teste.

## Efeitos ao acertar

Quando a criatura **vence um Ataque com um Ataque natural corpo a corpo**, o alvo faz um teste para resistir, com Dificuldade igual à Potência. Se falhar, sofre o efeito.

### Venenosa (Potência 2; Vigor + Determinação)

- **Descrição:** o alvo que falhar fica [Envenenado](../Condi%C3%A7%C3%B5es/Envenenado.md) por um número de Turnos igual à Potência.

### Paralisante (Potência 2; Vigor + Força)

- **Descrição:** o alvo que falhar fica [Paralisado](../Condi%C3%A7%C3%B5es/Paralisado.md) por 1 Turno.

### Atordoante (Potência 2; Determinação + Astúcia)

- **Descrição:** o alvo que falhar fica [Atordoado](../Condi%C3%A7%C3%B5es/Atordoado.md) por 1 Turno.

### Infecciosa

- **Descrição:** a doença ou maldição transmitida, a Reserva para resistir, a Potência e a duração são definidas em cada criatura (por exemplo, licantropia).

## Ataques especiais

### Frenesi

- **Descrição:** uma vez por Turno, ao vencer um Ataque, a criatura faz outro Ataque contra outro alvo ao seu Alcance, com **-2 dados**.

### Frenesi Aprimorado

- **Requisito:** Frenesi
- **Descrição:** o Ataque extra do Frenesi não sofre a penalidade.

### Sopro (Dano; Tipo de Dano)

- **Descrição:** com sua Ação, a criatura cria uma [Zona](../Cenas%20e%20Conflitos/Zonas.md) instantânea em uma [Rajada 3](../Cenas%20e%20Conflitos/Zonas.md#rajada-n). A Zona possui o Dano e o Tipo de Dano definidos na criatura. O Sopro não pode ser usado em Turnos seguidos.

### Investida (+2 de Dano; 4 quadrados)

- **Descrição:** se a criatura se mover pelo menos 4 quadrados em linha reta antes de atacar, soma **+2 ao Dano** do Ataque.

### Ir para a Garganta (Margem 3)

- **Descrição:** ao vencer um Ataque com Margem 3 ou mais, o dano ignora a Absorção da **armadura** do alvo. A Absorção base continua valendo.

### Constritora (Margem 2)

- **Descrição:** ao vencer um Ataque com Margem 2 ou mais, o alvo também fica [Agarrado](../Condi%C3%A7%C3%B5es/Agarrado.md). No começo de cada Turno da criatura, quem ela estiver agarrando sofre o Dano do seu Ataque natural.

### Aterrorizante (Potência 2; Determinação + Astúcia; acúmulos iguais à Potência)

- **Descrição:** quem vê a criatura pela primeira vez na cena faz o teste para resistir. Quem falhar recebe acúmulos de [Medo](../Condi%C3%A7%C3%B5es/Medo.md).

### Teia (Potência 2; Alcance 6; Ataque: Agilidade + Atirar; escapar: Força + Atletismo)

- **Descrição:** a criatura realiza um Ataque à distância, até o Alcance, com **Agilidade + Atirar**. Uma ficha pode estabelecer expressamente outro Atributo de Ataque para sua Teia. Ao vencer, deixa o alvo [Agarrado](../Condi%C3%A7%C3%B5es/Agarrado.md) pela teia. Para se soltar, o alvo usa sua Ação e testa **Força + Atletismo** contra a Potência.

### Emboscada Subterrânea

- **Requisito:** Escavadora
- **Descrição:** ao sair da terra para atacar, a criatura testa **Agilidade + Furtividade** contra **Astúcia + Perceber** do alvo. Se vencer, recebe **+2 dados** no Ataque.

### Enxame (dano pelo Tamanho)

- **Descrição:** a criatura é um enxame de bichos pequenos, tratado como uma só. No **começo de cada Turno** dela, todas as criaturas **no espaço que ela ocupa ou adjacentes** sofrem **dano superficial**, sem rolagem de Ataque. O dano base vem do Tamanho (**Médio 2, Grande 4, Enorme 6**) e cai **1 para cada criatura atingida além da primeira**, até o mínimo de 1. Efeitos ao acertar da criatura, como [Venenosa](#venenosa-pot%C3%AAncia-2-vigor--determina%C3%A7%C3%A3o), valem para cada atingido. O dano base pode mudar em cada criatura. Costuma ser **Imune a Corte e Perfurante**.

## Recuperação

### Regeneração (2; interrompida pelo Tipo de Dano ou Material definido na criatura)

- **Descrição:** ao **final de cada Turno** da criatura, ela converte um número de pontos de dano agravado em superficial igual ao valor da Regeneração, sem precisar de tratamento. O valor é configurável em cada criatura.
- **Interrupção:** cada criatura lista os Tipos de Dano ou Materiais que interrompem a sua Regeneração. Se ela sofrer dano de um deles desde o fim do seu último Turno, **não regenera nesse Turno**. A interrupção vale só por esse Turno: no Turno seguinte, sem novo dano daquele tipo, a Regeneração volta.

## Sentidos

### Visão no Escuro (12 quadrados)

- **Descrição:** até o alcance, a criatura trata a **Penumbra** como **Claro** e o **Escuro** como **Penumbra**, mas enxerga sem distinguir cores. Além do alcance, a [Iluminação](../Cenas%20e%20Conflitos/Ilumina%C3%A7%C3%A3o.md) vale normalmente. A [escuridão sobrenatural](../Cenas%20e%20Conflitos/Ilumina%C3%A7%C3%A3o.md#escurid%C3%A3o-sobrenatural) bloqueia a Visão no Escuro.

---

← [Voltar para Criaturas](Criaturas.md)
