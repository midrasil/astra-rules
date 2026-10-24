A **Vida** representa a condição física de um personagem e sua capacidade de continuar agindo após sofrer ferimentos.

Sempre que um personagem sofre dano, esse dano é registrado em sua trilha de Vida. Conforme os ferimentos se acumulam, sua condição piora até que ele não seja mais capaz de continuar normalmente.

A Vida não representa apenas ferimentos visíveis. Ela também pode representar exaustão física, trauma, queimaduras, contusões e outras consequências capazes de comprometer o corpo do personagem.

## Trilha de Vida

Cada personagem possui uma quantidade limitada de espaços em sua **trilha de Vida**.

Quando sofre dano, o jogador marca uma quantidade de espaços correspondente ao dano recebido.

Os espaços são preenchidos da esquerda para a direita.

A trilha de Vida de um personagem é composta por:

> **3 + Vigor** espaços

Vigor é o **Atributo da Vida** por padrão. Cenários, Capacidades e outras regras podem ajustar esse valor ou substituir o Atributo utilizado na fórmula.

Quando uma Capacidade substituir Vigor, a quantidade de espaços é recalculada imediatamente a partir do novo Atributo. A substituição afeta somente o tamanho da trilha: recuperação, testes de Vigor e outras regras não são alterados, salvo quando a própria Capacidade disser o contrário.

## Gravidade do Dano

O Astra utiliza duas **gravidades** principais de dano:

- **Dano Superficial**
- **Dano Agravado**

A diferença entre eles representa a gravidade do ferimento e a dificuldade necessária para sua recuperação.

O **Tipo de Dano** — a natureza do ferimento (corte, contusão, perfurante, fogo, gelo, elétrica etc.) — é uma informação separada da gravidade: ele é definido pela fonte do dano, como as armas (ver [Armas](../Equipamentos/Armas.md)).

## Dano Superficial

O **Dano Superficial** representa ferimentos menos graves, desgaste físico e traumas dos quais um personagem consegue se recuperar com relativa facilidade.

Golpes desarmados, impactos leves e outros ferimentos que não colocam a integridade física do personagem em risco imediato são exemplos de dano superficial, quando a fonte do dano ou o Narrador assim determinar. Ferimentos agravados também podem se tornar superficiais por meio de armaduras, Resistências e outros efeitos.

O dano superficial é registrado na trilha de Vida como um traço /.

## Dano Agravado

O **Dano Agravado** representa ferimentos graves e potencialmente incapacitantes.

Perfurações profundas, queimaduras severas, eletricidade letal e outras formas particularmente perigosas de dano podem causar dano agravado.

Essa gravidade de dano representa consequências mais sérias e normalmente é mais difícil de recuperar do que dano superficial.

Determinados equipamentos, habilidades ou efeitos podem transformar **dano agravado em dano superficial**.

**Por padrão, todo dano é agravado** — a menos que a própria fonte do dano (arma, ataque, efeito) especifique o contrário. É o caso da maioria dos ataques, especialmente os desferidos com armas. [Armaduras](../Equipamentos/Armaduras.md) e [Resistências](../Resist%C3%AAncia%20e%20Vulnerabilidade/Resist%C3%AAncia.md) podem converter dano agravado em superficial (ver [Resistência e Vulnerabilidade](../Resist%C3%AAncia%20e%20Vulnerabilidade/Resist%C3%AAncia%20e%20Vulnerabilidade.md)).

A principal exceção é o **combate desarmado**, que causa **dano superficial** por padrão — socos, chutes e agarrões raramente são fatais. O Narrador também pode determinar que outras fontes de dano causam superficial quando a situação assim pedir.

O dano agravado é registrado na trilha de Vida como um traço X.

## Trilha de Vida Preenchida

- Quando a **trilha de Vida fica cheia**, com qualquer combinação de dano superficial e agravado, o personagem fica **Debilitado** (ver [Debilitado](../Condi%C3%A7%C3%B5es/Debilitado.md)).
- Se continuar recebendo dano, superficial ou agravado, e não houver mais espaços livres, o dano adicional começa a **converter espaços já preenchidos por dano superficial em dano agravado**.
- Quando **toda a trilha de Vida estiver preenchida por dano agravado**, o personagem está **incapacitado** e em uma situação potencialmente fatal. Em termos práticos, ele deixa de conseguir continuar normalmente na cena, e a sobrevivência passa a depender da situação e da decisão narrativa do Narrador.

## Recuperação

Ferimentos não desaparecem imediatamente após o término de um conflito.  
A recuperação depende da **gravidade** do dano sofrido.

**Dano Superficial** — cura com o tempo, sem necessidade de tratamento. Ao completar um [Descanso Prolongado](Descanso%20Prolongado.md), o personagem recupera uma quantidade de dano superficial igual ao seu **Vigor**.

**Dano Agravado** — não se recupera com o tempo. Ele permanece na trilha até receber **tratamento**, que o converte em dano superficial; o dano convertido volta a se curar normalmente depois disso.

O tratamento é uma **cena de cuidados** que exige condições mínimas: material de Curar, higiene e algum conforto. Quem trata rola **Astúcia + Curar** (o próprio personagem ou outro). **Cada sucesso converte 1 ponto** de dano agravado em superficial. Sem nenhum sucesso, o tratamento não converte nada. Um personagem pode receber um tratamento **por dia em jogo**.

Se o personagem estiver **hospitalizado**, em instalações adequadas, nenhuma rolagem é necessária: ele converte 1 ponto de dano agravado em superficial por dia de jogo, até a recuperação total.
