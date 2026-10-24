Este documento registra as decisões fundamentais para o novo sistema de **Competências**.

As regras fundamentais foram aprovadas e incorporadas ao sistema oficial. Os antigos Trunfos foram removidos do sistema; alguns de seus conceitos podem retornar futuramente como Capacidades, mas não permanecem disponíveis enquanto isso.

## Substituição dos Perfis

O nome **Perfis** não será utilizado. O novo sistema será chamado de **Competências**.

Competências constituem um sistema próprio e não são categorias de Privilégios ou dos antigos Trunfos.

## Conceito

Uma Competência reúne um conjunto temático de **Capacidades** relacionadas. A Competência apresenta a identidade geral do conjunto, enquanto cada Capacidade determina aquilo que o personagem efetivamente consegue fazer.

Competências não são limitadas ao combate. Elas podem reunir Capacidades relacionadas a qualquer aspecto do personagem ou das regras.

As Competências não serão divididas em categorias. Todas farão parte de uma única lista.

## Nível

Toda Competência possui um **Nível entre 0 e 5**, mas esse Nível não funciona como o Nível dos Privilégios.

O personagem aumenta diretamente o Nível de uma Competência. Cada aumento concede imediatamente uma nova Capacidade daquela Competência. Por isso, seu Nível também corresponde à quantidade de Capacidades que o personagem possui nela.

- **Nível 0:** o personagem não possui a Competência nem qualquer Capacidade dela.
- **Nível 1:** o personagem possui uma Capacidade da Competência.
- Cada aumento de Nível concede uma nova Capacidade.
- O Nível nunca pode ultrapassar 5.

Ao adquirir uma Competência, o personagem aumenta seu Nível de 0 para 1 e escolhe imediatamente uma de suas Capacidades. Não existe uma aquisição separada para a Competência e outra para sua primeira Capacidade.

Durante a campanha, o personagem gasta XP para aumentar o Nível da Competência. É esse aumento que concede acesso a uma nova Capacidade; Capacidades não são compradas separadamente.

## Maximização

Uma Competência é considerada **maximizada** quando uma destas condições é atendida:

1. o personagem possui cinco Capacidades da Competência e, portanto, alcançou o Nível 5; ou
2. o personagem adquiriu todas as Capacidades disponíveis naquela Competência, mesmo que ela possua menos de cinco.

Uma Competência com oito Capacidades disponíveis, por exemplo, é maximizada quando o personagem escolhe cinco delas. As três restantes não podem ser adquiridas por esse personagem.

Uma Competência com apenas três Capacidades é maximizada no Nível 3 depois que todas forem adquiridas.

O personagem não pode adquirir novas Capacidades de uma Competência que já esteja maximizada.

## Capacidades

As Capacidades são os elementos mecânicos das Competências. Elas possuem ampla liberdade para modificar o sistema, desde que seus efeitos sejam descritos com clareza.

Uma Capacidade pode, entre outras possibilidades:

- conceder novas ações ou reações;
- permitir ações que normalmente não seriam possíveis;
- modificar o funcionamento de ações, Manobras ou outras regras;
- adicionar ou remover dados de uma Reserva;
- transformar dados em sucessos quando determinadas condições forem atendidas;
- modificar custos, limites, resultados ou consequências;
- aumentar Vida, Vontade, Carga, Movimentação, Absorção ou outras características;
- alterar fórmulas utilizadas pelo sistema;
- conceder Resistências;
- oferecer benefícios passivos ou condicionais;
- representar técnicas, talentos, características físicas ou capacidades sobrenaturais.

Essa lista não limita os efeitos possíveis. A função central das Capacidades é permitir modificações mecânicas específicas e novas formas de interagir com o sistema.

## Relações entre Capacidades

Capacidades não precisam formar sequências ou progressões obrigatórias. Por padrão, podem ser escolhidas livremente dentro da Competência.

Entretanto, uma Capacidade pode exigir outra Capacidade quando existir uma relação clara entre elas. Por exemplo, uma Capacidade de **Contra-Ataque** poderia exigir **Aparar**.

Essas relações são definidas individualmente e não precisam existir em todas as Competências. Ao adquirir uma Competência no Nível 1, o personagem deve escolher uma Capacidade cujas exigências já consiga cumprir.

## Criação de personagem

Durante a criação de personagem, cada personagem recebe **3 Pontos de Competência**.

Cada ponto aumenta uma Competência em **1 Nível**. Todo Nível adquirido concede uma Capacidade apropriada ao novo Nível alcançado.

Não existe um custo separado para adquirir a Capacidade. Ela faz parte do aumento da Competência.

As regras de maximização e quaisquer exigências da Capacidade continuam sendo aplicadas durante a criação.

## Aquisição durante a campanha

Durante a campanha, aumentar uma Competência custa **5 × o novo Nível em XP**.

| Aumento | Custo |
|---|---:|
| Nível 0 para 1 | 5 XP |
| Nível 1 para 2 | 10 XP |
| Nível 2 para 3 | 15 XP |
| Nível 3 para 4 | 20 XP |
| Nível 4 para 5 | 25 XP |

A Capacidade concedida pelo novo Nível faz parte desse custo e não exige um gasto adicional de XP. O personagem precisa escolher uma Capacidade disponível que respeite seu Nível e quaisquer requisitos próprios.

## Níveis de Capacidade

Cada Capacidade possui um Nível que determina quando ela pode ser escolhida.

Quando o personagem aumenta uma Competência, ele pode escolher uma Capacidade de Nível igual ou inferior ao **novo Nível da Competência**.

| Nível anterior | Novo Nível | Capacidades disponíveis |
|---:|---:|---|
| 0 | 1 | Nível 1 |
| 1 | 2 | Níveis 1 ou 2 |
| 2 | 3 | Níveis 1, 2 ou 3 |
| 3 | 4 | Níveis 1 a 4 |
| 4 | 5 | Níveis 1 a 5 |

O personagem não precisa escolher uma Capacidade do maior Nível disponível. Capacidades de Níveis inferiores continuam sendo opções válidas durante toda a progressão.

## Estrutura

Uma Competência seguirá esta estrutura geral:

```md
# Nome

**Descrição:** apresenta a identidade da Competência e o tipo de capacidades que ela reúne.

## Capacidades

### Nome da Capacidade

**Nível:** valor de 1 a 5.

**Requisito:** outra Capacidade, quando houver.

**Descrição:** apresenta o efeito mecânico da Capacidade.
```

O campo **Requisito** somente será utilizado nas Capacidades que dependerem de outra.

## Distinção dos Privilégios

**Privilégios** representam aquilo que o personagem possui ou representa dentro do mundo, como relações, reconhecimento, posição social, propriedades e recursos.

**Competências** reúnem Capacidades que modificam mecanicamente aquilo que o personagem pode fazer e como ele interage com as regras.

## Decisões pendentes

Ainda precisam ser definidos:

- a lista de Competências do sistema;
- quais conceitos do material histórico merecem retornar como Capacidades;
- converter os efeitos das antigas Maestrias em **Propriedades Especiais**, Capacidades ou descartes, conforme [[reestruturação/Equipamentos/Conversão de Maestrias em Propriedades]].

Permanecem como decisões fechadas:

- os pontos iniciais de Perícia não serão alterados;
- a Esquiva permanece em **Agilidade + Acrobacia**, sem uma Capacidade geral de **Evasão Explosiva**;
- a distribuição atual de Perícias e funções entre os seis Atributos será mantida;
- Maestrias de arma não constituem mais um subsistema; efeitos próprios das armas serão Propriedades Especiais;
- testes de jogo e a sincronização com o Foundry serão realizados posteriormente.

## Material para análise

- [Trunfos não convertidos em Privilégios](Trunfos%20n%C3%A3o%20convertidos%20em%20Privil%C3%A9gios.md)
