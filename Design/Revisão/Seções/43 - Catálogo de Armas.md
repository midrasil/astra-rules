# 43 · Catálogo de Armas

**Arquivo:** `Regras/Equipamentos/Catálogo de Armas.md` (e `en/`)
**Relacionadas:** Armas (D-068, Maestria e Domínio de arma), Catálogo de Itens (D-067), Ambidestro, Ação
**Pendências que chegam aqui:** nenhuma
**Status:** concluída (PR #65, mergeado em 2026-11-05)

## O que está estabelecido

- Três tabelas: 20 armas corpo a corpo, 5 à distância e a Arma Improvisada.
- Colunas iguais à tabela de campos de Armas (D-068); a coluna Maestria indica o efeito que só quem domina a arma usa.
- Os Valores seguem os preços do D&D 5e (Adaga 2, Espada Longa 15, Montante 50, Arco Longo 50 etc.), como no Catálogo de Itens.
- Não existe regra de munição em nenhum lugar das regras.

## Organização da seção (decidida em 2026-11-04)

O autor pediu para tratar dois problemas maiores dentro desta seção: as armas ainda são desiguais por causa do formato plano, e falta um sistema de munição. A seção foi dividida em três partes, todas no mesmo PR:

- **43.A · Munição e Recarga** (esta parte, em análise);
- **43.B · Critério de equilíbrio:** o que diferencia uma arma de outra e quanto cada coisa vale;
- **43.C · Maestrias novas e catálogo:** um catálogo de Maestrias para os papéis que faltam, aplicado arma por arma.

As propostas da primeira análise (no fim deste arquivo) ficam suspensas e serão retomadas na 43.C.

## 43.A · Munição e Recarga

### Análise

1. **Hoje nada diz o que um arco dispara.** Arco Curto, Arco Longo, Besta e Funda não gastam nada, e a Besta é melhor que o Arco Curto em tudo. O autor decidiu criar um sistema de munição.
2. **Modelo de partida: o 5e.** Lá, a propriedade *Ammunition* gasta uma peça por ataque, sacar a munição faz parte do ataque e metade da munição gasta é recuperada depois da luta, se houver tempo para procurar. *Loading* limita a um disparo por ação. Proponho seguir esse modelo, que é curto e conhecido, com dois ajustes ao Astra.
3. **Ajuste 1: Aceitar o Confronto também dispara.** No Astra, quem é atacado à distância pode Aceitar o Confronto com uma arma à distância e atirar de volta. Esse disparo gasta munição como qualquer outro. Defender e Esquivar não disparam e não gastam.
4. **Ajuste 2: a Recarga não pode custar uma Ação.** No 5e, *Loading* só pesa para quem tem mais de um ataque. No Astra, cada personagem tem **uma** Ação por Turno; se recarregar custasse uma Ação, a Besta atiraria a cada dois Turnos. Proponho que recarregar custe **2 pontos de Movimentação**. Como a Movimentação pode ser dividida antes e depois da Ação (D-064), o besteiro atira e depois recarrega, e anda 2 quadrados a menos por Turno. O custo também aparece na resposta: uma Besta descarregada não pode Aceitar o Confronto até ser recarregada no Turno do personagem, então quem Aceita com ela fica sem resposta até lá.
5. **O Material deve vir da munição.** Hoje o Arco é de Madeira, mas quem fere é a flecha. Com Resistências e Vulnerabilidades por Material, isso importa: uma flecha de ponta de prata contra um lobisomem, por exemplo. Proponho: num Ataque com uma arma que usa Munição, vale o **Material da munição**, não o da arma. A munição comum é de Metal comum, e as balas de funda são de Pedra.
6. **Armas de arremesso não usam munição.** A própria arma é lançada e fica no chão (pegá-la de volta já exige Trocar Equipamento). Não precisam de regra nova.
7. **Pacotes, para não pesar a Carga.** Uma flecha de Carga 0 faria 20 flechas pesarem 2. Proponho vender a munição em **pacotes de 20**, com Carga 1 por pacote, como o 5e faz com o peso de 20 flechas.
8. **A Recarga sozinha não equilibra tudo.** Com ela, a Besta passa a ter um custo real, mas o Arco Curto continua sem Maestria. O que o Arco Curto ganha em troca fica para a 43.B e a 43.C.

### Propostas

#### P-43.A1 · Propriedade Munição (Uso)

Texto novo em Armas, em Uso:

> - **Munição (tipo)** — arma de disparo que lança a munição indicada, como **Munição (flechas)**. Cada disparo gasta **1 munição**, seja ao iniciar um Confronto, seja ao Aceitar o Confronto; sem munição, a arma não dispara. Sacar a munição faz parte do Ataque. No Ataque, vale o **Material da munição**, não o da arma. Ao fim da Cena, se houver tempo para procurar, o personagem recupera **metade da munição gasta**, arredondada para baixo.

#### P-43.A2 · Propriedade Recarga (Uso)

> - **Recarga** — depois de disparar, a arma fica **descarregada**. Recarregá-la custa **2 pontos de Movimentação** no Turno do personagem e exige as duas mãos livres de outros equipamentos. Descarregada, a arma não pode iniciar nem Aceitar um Confronto. A arma começa a Cena carregada.

#### P-43.A3 · Munição no Catálogo de Itens

| Item | Carga | Valor | Uso |
|---|---:|---:|---|
| Flechas (20) | 1 | 1 | munição de arcos; Metal comum |
| Virotes (20) | 1 | 1 | munição de bestas; Metal comum |
| Balas de funda (20) | 1 | 0,04 | munição de fundas; Pedra |

Os Valores são os do 5e. Módulos e cenários podem acrescentar munição de outros Materiais, como flechas de prata.

#### P-43.A4 · Catálogo de Armas

- Arco Curto e Arco Longo: **Munição (flechas)**.
- Besta: **Munição (virotes), Recarga**.
- Funda: **Munição (balas de funda)**.

### Decisões do autor (2026-11-04)

- P-43.A1, P-43.A3 e P-43.A4: aprovadas como propostas.
- P-43.A2: o autor preferiu o modelo do 5e. Depois da discussão, ficou só "a arma dispara no máximo uma vez por Rodada", sem estado de descarregada e sem custo de Movimentação. Com esse texto, a Besta pode Aceitar o Confronto se ainda não disparou na Rodada, mas perde o disparo do próprio Turno.
- Registrada como D-069 e aplicada.

## 43.B · Critério de equilíbrio

### Análise

1. **O que o catálogo usa hoje para diferenciar armas:**
   - **Dano:** de 0 a 4;
   - **Empunhadura:** Leve, uma mão, Flexível ou Duas mãos;
   - **Alcance:** 1 ou 2 no corpo a corpo, de 10 a 20 à distância;
   - **Atributo:** Agilidade ou Força (Pesado);
   - **Propriedades de Uso:** Arremesso, Versátil, Manobra, Não letal, Munição, Recarga;
   - **Maestria** e **Material**;
   - **Carga** e **Valor**.
2. **O que já segue um padrão, mesmo sem estar escrito.** O Dano acompanha a Empunhadura: Leve 1, uma mão 2, Duas mãos 4. Quando a arma tem Alcance 2, ela perde 1 de Dano (Alabarda e Lança 3, Chicote 0). Proponho usar esse padrão como base.
3. **O que não segue padrão nenhum.** A quantidade de Propriedades vantajosas: a Espada Longa tem Flexível e Versátil; a Maça, nenhuma. É isso que gera armas melhores que outras.
4. **O que não deve entrar na conta:**
   - **Pesado:** só troca Agilidade por Força. Não é vantagem nem custo; serve para que cada tipo de personagem tenha opções.
   - **Valor:** só pesa na criação; depois, todo personagem pode comprar qualquer arma do núcleo.
   - **Carga:** a diferença é de 1 ponto.
   - **Material:** muda o alvo contra o qual a arma é boa, mas não deixa a arma melhor no geral.
5. **Versátil é fraco demais para contar como vantagem.** Ele só importa contra Resistências e Vulnerabilidades de Tipo. Se contar, a maioria das armas perde o sabor (a espada que corta e perfura). Proponho que Versátil seja **livre**.

### Propostas

#### P-43.B1 · Orçamento de uma arma

| Base | Dano |
|---|---:|
| Corpo a corpo, Leve | 1 |
| Corpo a corpo, uma mão | 2 |
| Corpo a corpo, Duas mãos | 4 |
| À distância, Leve | 1 |
| À distância, Duas mãos | 2 |

- **Alcance 2** no corpo a corpo: **-1 de Dano**.
- Toda arma tem **uma Maestria** e **uma vantagem**, escolhida entre:
  - Flexível;
  - Arremesso;
  - Manobra;
  - Alcance à distância maior (cerca de +50%).
- **Uma desvantagem** (Não letal, Recarga) compra **+1 de Dano** ou **mais uma vantagem**.
- **Livres:** Versátil e Pesado.
- **Fora da conta:** Valor, Carga e Material.
- A Arma Improvisada fica fora do orçamento, porque é de propósito pior.

#### P-43.B2 · Onde o critério fica

O critério serve a quem cria armas (você, módulos e cenários), não a quem joga. Proponho guardá-lo em `Design/Equipamentos/Critério de Equilíbrio de Armas.md`. Alternativa: uma seção curta "Criando armas" em Armas, perto da frase "Módulos e cenários podem adicionar…".

### Como o catálogo atual fica com esse critério

Só a título de diagnóstico; os ajustes ficam para a 43.C.

| Situação | Armas |
|---|---|
| **Dentro do orçamento** | Adaga, Machadinha (falta a Maestria), Lança Curta, Chicote, Espada Longa, Mangual, Machado de Batalha, Porrete com Espinhos, Malho, Clava Massiva, Alabarda, Bordão |
| **Acima** | Martelo de Guerra (Flexível e Manobra); Arco Longo (Dano 3 e Alcance 20, sem desvantagem) |
| **Abaixo** (sem vantagem) | Espada Curta, Cimitarra, Maça, Montante, Machado Grande, Lança, Porrete (Não letal sem compensação), Funda, Arco Curto (também sem Maestria) |
| **Besta** | Dano 3 = 2 + Recarga, como manda o critério; o Alcance 15 conta como uma vantagem pequena |

Conclusões:
- Só **dois** casos estão acima do orçamento.
- O problema maior são as **nove** armas abaixo dele, quase todas sem vantagem nenhuma.
- A 43.C pode resolver a maior parte disso com Maestrias novas e dando uma vantagem a cada arma, sem mexer no Dano.

### Decisões do autor (2026-11-04)

- "concordo": P-43.B1 e P-43.B2 aprovadas como propostas (D-070). O critério foi gravado em `Design/Equipamentos/Critério de Equilíbrio de Armas.md`.

## 43.C · Maestrias novas e catálogo

### Análise

1. **Ponto de partida:** as nove armas abaixo do orçamento (43.B), as duas acima dele e as propostas suspensas da primeira análise.
2. **A lista de vantagens da 43.B é curta demais.** Flexível, Arremesso e Manobra servem bem às armas leves e de uma mão. Mas o Montante, o Machado Grande e a Lança já são de Duas mãos e não fazem sentido arremessados, Por isso proponho **duas vantagens novas** (Propriedades de Uso). Isso **amplia a lista aprovada na D-070**, então precisa da sua aprovação explícita.
3. **Quatro Maestrias novas.** Partem das maestrias do 5e que ainda não têm equivalente no Astra: *Vex*, *Graze*, *Push* e uma nova contra armaduras. A antiga maestria Embalo volta, mais simples: sem acúmulos e sem Condição, para não criar anotação. Cada uma segue o padrão das atuais ("ao vencer um Ataque…"), menos o Raspão, que funciona justamente quando o Ataque perde.
4. **O Chicote deixa de ter Debilitante.** Com Dano 0, abrir mão do Dano não custava nada. Pelo critério, o Dano 0 está certo (Leve, Alcance 2), então o que muda é a Maestria.
5. **Porrete com Espinhos:** pelo critério, está dentro do orçamento, e o Valor fica fora da conta. Retiro a proposta de Valor 10 da primeira análise.
6. **Arco Longo:** está acima do orçamento (Dano 3 e Alcance 20, sem desvantagem). Passa para Dano 2, e a vantagem dele é o Alcance (24, o maior do catálogo).
7. **Besta:** Dano 3 vem da Recarga; a vantagem passa a ser o Alcance maior (18). Ganha Perfurar, que combina com o virote que atravessa armadura.

### Propostas

#### P-43.C1 · Quatro Maestrias novas (em Armas, junto das atuais)

> - **Embalo** — ao vencer um Ataque, o próximo Ataque do atacante contra o mesmo alvo, até o fim do seu próximo Turno, recebe **+1 dado**. Os bônus de Embalo não se acumulam.
> - **Raspão** — quando o alvo vence o Ataque, ele ainda sofre **metade do Dano da arma**, arredondada para cima, como dano superficial. Não vale se o atacante não obteve nenhum Sucesso.
> - **Deslocar** — ao vencer um Ataque, o atacante pode mover o alvo **1 quadrado** em qualquer direção, sem outra rolagem, seguindo os limites de [Reposicionar](../Cenas%20e%20Conflitos/A%C3%A7%C3%B5es/Manobras.md#reposicionar).
> - **Perfurar** — ao vencer um Ataque, a [Absorção](Armaduras.md#absor%C3%A7%C3%A3o) do alvo converte **1 ponto a menos** de dano agravado.

#### P-43.C2 · Duas vantagens novas (Propriedades de Uso)

> - **Investida** — se o personagem se moveu pelo menos **3 quadrados em linha reta** até o alvo neste Turno, logo antes do Ataque, o Ataque recebe **+1 de Dano**.
> - **Guarda** — enquanto empunha a arma, o personagem recebe **+1 dado ao Esquivar**. Duas armas com Guarda não somam.

O critério em `Design/` passa a listar as seis vantagens. (Disparo Rápido chegou a ser proposta e foi retirada pelo autor em 2026-11-05.)

Sem Disparo Rápido, o Arco Curto e a Funda usam o **Alcance maior** como vantagem. Para o Arco Longo continuar sendo o arco de maior Alcance, ele sobe para 24.

#### P-43.C3 · Catálogo

Só as armas que mudam:

| Arma | Muda |
|---|---|
| Espada Curta | + Guarda; Maestria Varredura → **Embalo** |
| Machadinha | Maestria — → **Debilitante (Lento)** |
| Porrete | Dano 1 → **2** (Não letal compra o Dano); + Manobra (Derrubar) |
| Lança Curta | Arremesso (4) → **(6)**; Maestria Letal → **Perfurar** |
| Chicote | Maestria Debilitante (Lento) → **Deslocar** |
| Cimitarra | + Guarda |
| Maça | + Investida; Maestria Debilitante (Abalado) → **Perfurar** |
| Martelo de Guerra | − Manobra (Derrubar); Maestria Debilitante (Abalado) → **Deslocar** |
| Montante | + Guarda; Maestria Varredura → **Raspão** |
| Machado Grande | + Investida; Maestria Letal → **Varredura** |
| Clava Massiva | Maestria Debilitante (Abalado) → **Deslocar** |
| Lança | + Investida |
| Arco Curto | Alcance 12 → **18**; Maestria — → **Embalo** |
| Arco Longo | Dano 3 → **2**; Alcance 20 → **24** |
| Besta | Alcance 15 → **18**; Maestria Letal → **Perfurar** |
| Funda | Alcance 10 → **15** |

Ficam como estão: Adaga, Espada Longa, Mangual, Machado de Batalha, Malho, Porrete com Espinhos, Alabarda, Bordão e Dardo.

Distribuição das Maestrias depois da mudança:

| Maestria | Armas |
|---|---|
| Letal | Adaga, Espada Longa, Porrete com Espinhos, Lança, Arco Longo, Dardo |
| Varredura | Cimitarra, Machado de Batalha, Machado Grande, Bordão |
| Debilitante (Abalado) | Porrete, Malho, Funda |
| Debilitante (Lento) | Machadinha, Mangual, Alabarda |
| Embalo | Espada Curta, Arco Curto |
| Raspão | Montante |
| Deslocar | Chicote, Martelo de Guerra, Clava Massiva |
| Perfurar | Lança Curta, Maça, Besta |

### Decisões do autor (2026-11-05)

- "tire disparo rapido": Disparo Rápido foi retirada; o Arco Curto e a Funda usam o Alcance maior, e o Arco Longo sobe para Alcance 24.
- "concordo.": P-43.C1, P-43.C2 (sem Disparo Rápido) e P-43.C3 aprovadas (D-071). O termo "vantagem" continua só no critério em `Design/`.
- As propostas da primeira análise foram absorvidas pela 43.A e pela 43.C.

## Primeira análise (suspensa; retomada na 43.C)

Comparei cada arma com as vizinhas de mesmo Dano e Empunhadura, procurando armas que sejam piores em tudo do que outra (uma arma que ninguém teria motivo para escolher).

1. **A Machadinha é pior em tudo que a Adaga.** As duas são Leves, têm Dano 1, Arremesso (4) e Carga 1. A Adaga ainda tem Versátil (Corte), que cobre o Tipo da Machadinha, e Letal; a Machadinha não tem Maestria e custa mais (5 contra 2). Proponho dar uma Maestria à Machadinha: **Debilitante (Lento)**, o golpe que corta a perna. Assim ela fica sendo a arma leve de arremesso que atrasa o alvo.
2. **A Lança Curta também perde para a Adaga.** Mesmo Dano, Tipo, Arremesso (4), Maestria (Letal) e Carga; a Adaga ainda tem Versátil. A diferença de Valor (1 contra 2) não pesa. Proponho **Arremesso (6)**: a lança de arremesso vai mais longe, como o dardo de arremesso (javelin) do 5e.
3. **O Chicote aplica Lento de graça.** Debilitante pede para abrir mão do Dano da arma; com Dano 0, isso não custa nada, e todo Ataque vencido deixa o alvo Lento. Proponho **Dano 1**, como o chicote do 5e (que tem o mesmo dado da adaga). Alternativa: manter Dano 0 e trocar a Maestria por outra.
4. **A Besta é melhor em tudo que o Arco Curto.** Mesmo Valor (25), Carga e Empunhadura; a Besta tem mais Dano (3 contra 2), mais Alcance (15 contra 12) e Letal, enquanto o Arco Curto não tem Maestria. No 5e, a besta paga isso com a recarga. Proponho uma nova Propriedade de Uso, **Recarga**: depois de atacar, a arma precisa ser recarregada antes do próximo Ataque, o que custa **2 pontos de Movimentação**. A Besta recebe Recarga. Não proponho que a recarga custe uma Ação, porque no Astra o personagem tem uma Ação por Turno, e a Besta só atacaria a cada dois Turnos.
   - **Alternativa sem regra nova:** baixar a Besta para Dano 2 e manter o resto. Ela continuaria melhor que o Arco Curto em Alcance e Maestria, só que por menos.
5. **O Porrete com Espinhos custa 1, mas faz o mesmo que a Espada Longa (15).** Os dois têm Dano 2, Flexível, Versátil e Letal; o Porrete ainda tem Pesado (usa Força, o que não é custo nem vantagem) e é de Madeira. Não tem equivalente direto no 5e com esse preço (a maça-estrela custa 15). Proponho **Valor 10**: continua mais barato que a Espada Longa por ser de madeira, mas deixa de custar o mesmo que um porrete comum. É uma questão de gosto; se preferir uma arma barata e forte de propósito, fica como está.
6. **Munição não existe.** Arco, Besta e Funda não dizem o que disparam. Proponho deixar a munição **abstrata**, numa frase: quem tem uma arma de disparo tem munição para ela, e o Narrador pode pedir que ela seja reposta entre aventuras ou quando fizer sentido na história. Contar flechas acrescenta anotação sem decisão interessante na maior parte das mesas.
   - **Alternativa (modelo do 5e):** Flechas, Virotes e Balas de funda no Catálogo de Itens (Carga 0, em pacotes de 20), cada Ataque gasta uma, e metade pode ser recuperada depois da Cena.

#### Conferido, sem mudança

- **Clava Massiva × Malho:** só diferem em Material (Madeira ou Metal comum) e Valor. O Material importa contra Resistências e Vulnerabilidades, então a escolha tem sentido.
- **Dardo:** está na tabela à distância, mas tem Alcance 1 e Arremesso (6), como a Adaga. Funciona e fica como está. Com a P-43.1, a Lança Curta empata com ele em Arremesso (6), mas o Dardo continua sendo a opção mais barata.
- **Lança × Alabarda, Montante × Machado Grande, Maça × Mangual:** cada par tem uma diferença real de Maestria, Manobra, Alcance ou Valor.

### Propostas da primeira análise

#### P-43.1 · Equilíbrio do catálogo

- Machadinha: Maestria **Debilitante (Lento)**.
- Lança Curta: **Arremesso (6)**.
- Chicote: **Dano 1**.
- Nova Propriedade de Uso em Armas: **Recarga** — "depois de atacar, a arma precisa ser recarregada antes do próximo Ataque; recarregar custa 2 pontos de Movimentação." A Besta recebe Recarga.
- Porrete com Espinhos: **Valor 10**.

#### P-43.2 · Munição abstrata (descartada: o autor decidiu criar munição contada, ver 43.A)

- Frase nova no catálogo, junto das armas à distância: "A munição é abstrata: quem possui uma arma de disparo tem munição para ela. O Narrador pode exigir que ela seja reposta entre aventuras ou quando fizer sentido na história."
- **Alternativa:** munição contada, no modelo do 5e, com itens no Catálogo de Itens.
