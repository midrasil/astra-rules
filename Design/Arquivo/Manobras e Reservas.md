# Manobras e Reservas

Este documento separa as **Manobras** para revisão dentro da proposta de Atributos vinculados. Cada Manobra possui uma finalidade própria e uma Reserva fixa. Capacidades e outras regras podem substituir essas Reservas expressamente.

> [!note] Estado do documento
> As Reservas desta nota foram incorporadas a `Regras/Cenas e Conflitos/Ações/Manobras.md` durante a Etapa 3 da reestruturação.

## Regra geral

Realizar uma Manobra exige uma **Ação**, salvo quando uma regra determinar outra coisa.

Quando houver um alvo, a Manobra normalmente é resolvida por uma rolagem oposta. O personagem que iniciou a Manobra precisa obter mais Sucessos. Em caso de empate, nada acontece.

As Reservas apresentadas abaixo são fixas. A descrição narrativa da ação não permite trocar livremente Atributos ou Perícias. Uma Capacidade, propriedade ou regra específica pode determinar outra Reserva.

Uma Manobra não é um Ataque e não causa dano, salvo quando uma regra disser expressamente o contrário. Por isso, propriedades que modificam o Atributo de **Ataques**, como Pesado, não modificam automaticamente uma Manobra.

## Lista resumida

| Manobra | Reserva de quem inicia | Reserva de resistência |
| --- | --- | --- |
| Reposicionar | Força + Atletismo | Força + Atletismo |
| Derrubar | Força + Atletismo | Força + Atletismo |
| Agarrar | Força + Atletismo | Força + Atletismo |
| Desarmar | Agilidade + Lutar | Agilidade + Lutar |
| Mirar | não exige teste | — |

## Reposicionar

Reposicionar representa empurrar, puxar, conduzir corporalmente ou retirar um alvo de sua posição.

> **Atacante: Força + Atletismo**
> **Alvo: Força + Atletismo**

Se vencer, o personagem desloca o alvo em **1 quadrado** numa direção válida.

O personagem só pode Reposicionar um alvo do mesmo Tamanho ou menor. A Manobra não causa dano ao colidir com obstáculos, embora quedas e perigos ambientais sejam resolvidos normalmente.

A propriedade **Manobra (Reposicionar)** permite realizar essa Manobra até o Alcance da arma, mas não transforma a rolagem em Ataque nem aplica Pesado por si mesma.

## Derrubar

Derrubar representa retirar a sustentação, desequilibrar ou lançar o alvo ao chão por potência física.

> **Atacante: Força + Atletismo**
> **Alvo: Força + Atletismo**

Se vencer, o alvo recebe a condição **Caído**.

Derrubar não causa dano. A propriedade **Manobra (Derrubar)** permite realizar a Manobra até o Alcance da arma, mantendo a Reserva acima.

## Agarrar

Agarrar representa prender fisicamente o alvo e impedir sua movimentação.

> **Atacante: Força + Atletismo**
> **Alvo: Força + Atletismo**

Se vencer, o alvo recebe a condição **Agarrado**.

O personagem só pode Agarrar um alvo do mesmo Tamanho ou menor. Enquanto mantiver o agarrão, pode arrastar ou carregar o alvo conforme as regras de Movimentação Especial.

### Escapar

Escapar de Agarrado exige uma Ação e repete a oposição:

> **Personagem Agarrado: Força + Atletismo**
> **Personagem que o segura: Força + Atletismo**

Se o personagem Agarrado vencer, a condição termina. Capacidades podem permitir Acrobacia, Lutar ou outro Atributo como substituição, mas essa possibilidade não faz parte da regra básica.

## Desarmar

Desarmar representa retirar um equipamento das mãos do alvo por técnica, precisão e controle da luta.

> **Atacante: Agilidade + Lutar**
> **Alvo: Agilidade + Lutar**

Se vencer, o alvo deixa cair o equipamento escolhido em seu próprio quadrado.

Desarmar pode afetar armas, escudos e outros objetos empunhados. Pegar o objeto caído continua seguindo a ação de Trocar Equipamento.

A propriedade **Manobra (Desarmar)** permite utilizar o Alcance da arma. Uma arma Pesada não transforma automaticamente essa Manobra em Força + Lutar, pois Pesado modifica Ataques. Uma Capacidade específica pode estabelecer essa substituição.

## Mirar

Mirar representa preparar e estabilizar um ataque à distância.

Mirar não exige teste. Cada Ação utilizada concede um acúmulo de **Mirando**, respeitando o limite determinado por Astúcia.

Cada acúmulo beneficia o próximo **Ataque à distância**, independentemente de ele utilizar:

- Atirar;
- Arremessar;
- Agilidade;
- Força por Pesado;
- outro Atributo estabelecido por uma Capacidade.

A Reserva utilizada pelo Ataque não altera o funcionamento de Mirar.

## Manobras realizadas com armas

Uma arma só altera uma Manobra quando possuir uma regra expressa para isso.

- **Pesado:** modifica apenas Ataques.
- **Manobra (X):** permite realizar a Manobra indicada até o Alcance da arma.
- **Tiro de Controle:** exemplo de Capacidade que permite realizar determinadas Manobras utilizando a Reserva de Ataque do arco.
- **Golpe Tático:** aplica o efeito de uma Manobra depois de vencer um Ataque, sem realizar uma segunda rolagem.

Essa separação impede que todas as propriedades ofensivas da arma sejam carregadas automaticamente para ações de controle.

## Manobras narrativas

Outras interferências físicas continuam possíveis como Manobras Narrativas. Quando uma tentativa se tornar recorrente, ela deve receber uma entrada própria com:

- finalidade;
- alcance;
- Reserva de quem inicia;
- Reserva de resistência;
- consequência da vitória;
- consequência do empate;
- limites de Tamanho ou equipamento;
- interação com dano, condições e movimentação.

O Narrador pode resolver uma situação inédita utilizando a Manobra mais próxima como referência, mas não deve permitir a troca livre de Atributos apenas pela forma como a ação foi descrita.

## Pontos ainda abertos

- verificar se Desarmar deve possuir alguma interação básica com Força ou se isso ficará inteiramente para Capacidades;
- decidir se Reposicionar, Derrubar e Agarrar terão o mesmo limite de Tamanho;
- decidir se alguma arma permite Agarrar a distância;
- revisar Tiro de Controle depois da atualização oficial das Reservas;
- testar se Força + Atletismo nas três Manobras físicas concentra funções demais numa única Reserva.
