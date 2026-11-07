Um **Consumível** é um equipamento que se gasta ao ser usado, como remédios, Drogas, venenos, bombas e suprimentos. Os Consumíveis do núcleo estão no [Catálogo de Consumíveis](Cat%C3%A1logo%20de%20Consum%C3%ADveis.md).

Cada Consumível tem **Usos** (quantas vezes pode ser usado antes de acabar; 1 quando o catálogo não indica outro número), **Uso** (o que custa usá-lo), **Efeito**, [Carga e Valor](Equipamentos.md).

## Usar um Consumível

- **Sacar** um Consumível segue as regras de [Trocar Equipamento](Trocar%20Equipamento.md).
- **Usar** um Consumível em si mesmo ou em uma criatura adjacente custa uma [Ação](../Cenas%20e%20Conflitos/A%C3%A7%C3%A3o.md), salvo quando o catálogo indica outro custo. Uma criatura que não quer o efeito precisa ser alvo de [Confrontar](../Cenas%20e%20Conflitos/A%C3%A7%C3%B5es/Confrontar.md).
- Um Consumível **arremessável** é usado com Confrontar, como uma arma com **Arremesso** (ver [Armas](Armas.md)) e o alcance indicado. O item se gasta mesmo que o Ataque falhe.
- **Aplicar em uma arma** custa uma Ação. O efeito vale para o próximo Ataque que causar dano com ela, até o fim da Cena.

O mesmo Consumível não acumula na mesma criatura: usá-lo de novo só renova a duração.

**Nenhum Consumível recupera dano** de [Vida](../Personagens/Vida.md) ou de [Vontade](../Personagens/Vontade.md). O [Kit de Cura](Cat%C3%A1logo%20de%20Consum%C3%ADveis.md#outros-consum%C3%ADveis) fornece o material do Tratamento, mas quem recupera o dano é o Tratamento.

## Drogas

**Drogas** são Consumíveis que fortalecem o corpo ou a mente por um preço. Uma Droga dura até o fim da Cena ou, fora de uma [Cena Tática](../Cenas%20e%20Conflitos/Cenas%20T%C3%A1ticas.md), por 1 hora. Ela tem três partes:

- **Efeito:** o que a Droga concede enquanto dura.
- **Custo:** a penalidade que o personagem sofre enquanto a Droga dura.
- **Rebote:** quando a Droga termina, o personagem paga o resto da conta, com valor igual ao Grau:
  - Drogas do **corpo** dão acúmulos de [Prejudicado](../Condi%C3%A7%C3%B5es/Prejudicado.md);
  - Drogas da **mente** causam dano superficial de [Vontade](../Personagens/Vontade.md).

Uma criatura só fica sob efeito de **uma Droga por vez**. Usar outra encerra a primeira, e o Rebote dela acontece na hora.

### Graus

Toda Droga existe em cinco **Graus**. O Grau decide a força do Efeito, os Custos, o Rebote e o Valor.

| Grau | Nome | Custos | Valor |
|---:|---|---|---:|
| 1 | Diluída | o Custo | 25 |
| 2 | Comum | o Custo | 50 |
| 3 | Concentrada | o Custo e o Custo extra | 150 |
| 4 | Forte | o Custo e o Custo extra | 400 |
| 5 | Pura | o Custo dobrado e o Custo extra | 1000 |

### Efeitos

Cada efeito tem uma **Intensidade**. A soma das Intensidades de uma Droga é igual ao Grau.

| Efeito | Intensidade |
|---|---:|
| **+1 num Atributo.** O Atributo pode passar de 5, sem limite. O bônus vale em rolagens e requisitos, mas não muda Vida, Vontade, Carga nem Iniciativa | 1 por ponto |
| **[Resistência](../Resist%C3%AAncia%20e%20Vulnerabilidade/Resist%C3%AAncia.md) 1** a um Tipo de Dano | 1 por ponto |
| **+2 de [Movimentação](../Movimento/Movimenta%C3%A7%C3%A3o.md) base** | 1 a cada +2 |
| **Ignorar uma Condição:** [Medo](../Condi%C3%A7%C3%B5es/Medo.md), [Atordoado](../Condi%C3%A7%C3%B5es/Atordoado.md), [Envenenado](../Condi%C3%A7%C3%B5es/Envenenado.md), [Lento](../Condi%C3%A7%C3%B5es/Lento.md), [Abalado](../Condi%C3%A7%C3%B5es/Abalado.md) ou [Desafiado](../Condi%C3%A7%C3%B5es/Desafiado.md) não têm efeito enquanto a Droga dura | 1 cada |
| **[Visão no Escuro](../Cenas%20e%20Conflitos/Ilumina%C3%A7%C3%A3o.md#vis%C3%A3o-no-escuro)** até 6 quadrados | 1 |
| **Sem Dor:** ignora as penalidades em dados do [Debilitado](../Condi%C3%A7%C3%B5es/Debilitado.md), do Prejudicado e do Envenenado | 2 |
| **Clareza:** o primeiro uso de Vontade na Cena não custa dano de Vontade | 2 |
| **De Pé:** a trilha de Vida cheia não deixa o personagem [Incapacitado](../Condi%C3%A7%C3%B5es/Incapacitado.md) enquanto a Droga dura. Se a trilha estiver cheia quando ela terminar, ele fica Incapacitado | 3 |

### Custos

| Custo | Efeito | Dobrado |
|---|---|---|
| **Atributo** | -1 num Atributo que a Droga não fortalece | -2 |
| **Vulnerabilidade** | [Vulnerabilidade](../Resist%C3%AAncia%20e%20Vulnerabilidade/Vulnerabilidade.md) 1 a um Tipo de Dano | Vulnerabilidade 2 |
| **Pesado** | -2 de Movimentação base | -4 |
| **Ofuscado** | o Claro conta como Penumbra para o personagem | — |
| **Instável** | no fim de cada Turno, role 1 dado; sem Sucesso, o personagem perde a Movimentação do próximo Turno | — |

Ofuscado e Instável não podem ser dobrados, por isso só aparecem como Custo extra.

---

← [Voltar para Equipamentos](Equipamentos.md)
