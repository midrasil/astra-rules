# Q-010 · Socorrista (versão 5)

**Status:** concluída (2026-11-06)
**Arquivos que mudariam:** `Regras/Competências/Socorrista.md` (novo), `Regras/Competências/Competências.md`, `Regras/Condições/Remendado.md` e `Regras/Condições/Prejudicado.md` (novos), `Regras/Condições/Condições.md`, `Regras/Personagens/Vida.md` (link no Tratamento) e as versões em `en/`

## Decisões do autor até aqui (2026-11-06)

- **A ideia:** a Competência não cura em combate. Ela mantém os feridos lutando e trata melhor depois (versão 1 descartada).
- **Nível 1:** Ação, Astúcia + Curar, alvo adjacente. Até o fim da Cena, converte uma quantidade de agravados em superficiais igual aos Sucessos (talvez também superficiais em espaços livres). O efeito é temporário, e ao fim da luta o personagem afetado recebe uma Condição de penalidade.
- **Nível 2:** sob o efeito do Curativo, o personagem ignora o Debilitado.
- **Níveis 3 e 5:** aprovados.
- **Nível 4:** precisa melhorar.
- **Nome:** Socorrista.
- **Revisão (2026-11-06, segunda rodada):** a Capacidade se chama Remendo, uma vez por Cena; Remendado é o estado durante a Cena; no fim da Cena o dano volta, podendo derrubar, mas sem matar; depois vem a Condição Prejudicado, com penalidade igual aos Sucessos do Remendo em todas as rolagens Físicas, somada ao Debilitado.
- **Terceira rodada:** uma vez por Cena para cada aliado; Prejudicado é acumulável, e cada Tratamento e cada Descanso Prolongado remove 1 acúmulo; o Socorrista escolhe quantos Sucessos usar; o Nível 4 deve aprimorar o Remendo ou acelerar a recuperação do Prejudicado; nome Socorrista.

## Proposta de progressão

| Nível | Capacidade | Lado |
|---:|---|---|
| **1** | Remendo | combate |
| **2** | Aguentar Firme | combate |
| **3** | Mãos Treinadas | fora do combate |
| **4** | Remendo Experiente | combate e depois |
| **5** | Hospital de Campanha | fora do combate |

### Nível 1 · Remendo

Em uma Cena Tática, com a sua Ação, você aplica um Remendo em uma criatura **adjacente** ou em si mesmo, com material de cura (1 uso), e testa **Astúcia + Curar**. Ela fica [Remendada](#condição-remendado) até o fim da Cena, com uma quantidade de pontos aliviados igual aos Sucessos. Você escolhe quantos Sucessos usar, de 0 até o total obtido.

Cada criatura pode ser Remendada **uma vez por Cena**.

### Condição Remendado (nova)

Cada ponto aliviado de uma criatura **Remendada** muda o dano de Vida dela até o fim da Cena:

- um ponto de dano agravado se torna superficial;
- se ela não tiver dano agravado, um ponto de dano superficial é apagado.

No **fim da Cena**, o dano aliviado volta. Cada ponto convertido volta a ser agravado, e cada ponto apagado volta como superficial, com as regras normais da trilha cheia. Isso pode deixá-la [Incapacitada](../../Regras/Condi%C3%A7%C3%B5es/Incapacitado.md), mas **esse dano nunca a mata**. Depois disso, ela fica [Prejudicada](#condição-prejudicado), com acúmulos iguais à quantidade de pontos aliviados.

- Um aliado Incapacitado pode ser Remendado e se levantar, porque passa a ter dano superficial na trilha.
- Apagar superficial só acontece quando não há agravado. Assim nenhum Sucesso se perde.

### Condição Prejudicado (nova)

**Prejudicado** é uma Condição acumulável. Cada acúmulo dá **-1 dado** em todas as rolagens que utilizem um [Atributo Físico](../../Regras/Personagens/Atributos.md#categorias). A penalidade se soma à do [Debilitado](../../Regras/Condi%C3%A7%C3%B5es/Debilitado.md), se a trilha estiver cheia.

A Condição não termina no fim da Cena. Cada [Tratamento](../../Regras/Personagens/Vida.md#tratamento) recebido remove **1 acúmulo**, além do seu efeito normal, e cada [Descanso Prolongado](../../Regras/Personagens/Descanso%20Prolongado.md) completo remove **1 acúmulo**.

- Um Remendo com 5 Sucessos deixa 5 acúmulos. Com um Tratamento e um Descanso por dia, a Condição some em cerca de 3 dias.
- Um novo Prejudicado soma acúmulos ao que já existe.

### Nível 2 · Aguentar Firme

Enquanto estiver Remendada, a criatura ignora a penalidade de [Debilitado](../../Regras/Condi%C3%A7%C3%B5es/Debilitado.md).

### Nível 3 · Mãos Treinadas (aprovado)

Fora de uma Cena Tática, quando um Tratamento seu tiver ao menos 1 Sucesso, ele converte **1 ponto a mais**. Você trata e aplica Remendos sem material de cura, improvisando com o que tiver à mão.

### Nível 4 · Remendo Experiente (recomendado)

Quando a criatura que você Remendou ficar [Prejudicada](#condição-prejudicado) no fim da Cena, ela recebe **metade dos acúmulos**, arredondando para baixo.

- Aprimora o Remendo e acelera a recuperação ao mesmo tempo: o mesmo alívio custa metade depois. Um Remendo de 5 deixa 2 acúmulos, e um Remendo de 1 não deixa nenhum.
- Muda a conta principal da Competência, como pede o Domínio, sem dar ação extra nem cura na Cena.

**Alternativas:**

- **Recuperação Assistida:** quando você Trata uma criatura Prejudicada, cada Sucesso do Tratamento remove 1 acúmulo, em vez de só 1 no total. Fica todo no lado de depois da luta, como os Níveis 3 e 5.
- **Remendo Imediato:** uma vez por Rodada, quando uma criatura adjacente sofrer dano de Vida, você aplica o Remendo nela sem gastar a sua Ação, sofrendo 1 ponto de dano superficial de Vontade. Aprimora só o lado do combate.

### Nível 5 · Hospital de Campanha (aprovado)

Fora de uma Cena Tática, os seus Tratamentos contam como feitos em [Instalações Adequadas](../../Regras/Personagens/Vida.md#instala%C3%A7%C3%B5es-adequadas): +2 dados e no mínimo 3 pontos.

## Decisões do autor (2026-11-06)

- Nível 4: Remendo Experiente (escolha no cartão de decisão). A Competência foi aprovada para aplicar.
- Na escrita final, a volta do dano no fim da Cena passou a ser contada, sem marcar cada espaço: a criatura sofre dano superficial igual aos pontos apagados, e depois uma quantidade de superficiais igual aos pontos convertidos se torna agravada. O resultado é o mesmo e não exige acompanhar espaços individuais.
- Remendado e Prejudicado entram como Condições do núcleo; o Kit de Cura passa a servir também ao Remendo.
