# 46 · Trocar Equipamento

**Arquivo:** `Regras/Equipamentos/Trocar Equipamento.md` (e `en/`)
**Relacionadas:** Ação (soltar um objeto não exige Ação), Manobras (Desarmar), Armaduras (Vestir e Tirar, D-072), Armas (Munição, D-069), Escudos
**Pendências que chegam aqui:** nenhuma
**Status:** decidida (D-074) e aplicada; aguardando o merge do PR

## O que está estabelecido

- **Sacar** um equipamento pela primeira vez na Cena Tática não exige Ação; pode fazer parte da própria Ação.
- **Pegar com uma mão livre** também é sacar, mesmo com outro equipamento em uso.
- **Trocar Equipamento** (Ação) substitui o que já está em uso: guardar, reorganizar ou trocar, inclusive "jogar um equipamento no chão para pegar outro".
- **Pegar do chão** exige Trocar Equipamento, mesmo com a mão livre.

## Análise

1. **Uma brecha entre duas regras.** Em Ação: "soltar um objeto não exige Ação". Aqui: "pegar com uma mão livre é sacar". Juntas, elas permitem trocar de arma de graça: o personagem solta a espada (sem Ação), fica com a mão livre e saca o machado (sem Ação). A própria página diz que "jogar um equipamento no chão para pegar outro" é Trocar Equipamento, mas isso contradiz as outras duas frases.
2. **"Pela primeira vez" pede anotação.** Para saber se sacar é de graça, é preciso lembrar o que o personagem já usou na Cena. Na prática, ninguém anota.
3. **Modelo do 5e: uma interação livre por Turno.** No 5e, o personagem pode sacar ou guardar **um** objeto por turno sem gastar ação, e soltar é sempre livre. Trocar mais do que isso exige uma ação. O modelo é simples e não precisa de memória: em cada Turno, uma coisa de graça.
4. **Como fica a brecha com o 5e.** Soltar a espada e sacar o machado continua cabendo num Turno, mas a espada fica no chão, e pegá-la de volta exige Trocar Equipamento. É o mesmo do 5e, e o custo é real: largar a arma.
5. **O que continua igual:**
   - **Pegar do chão:** exige Trocar Equipamento.
   - **Trocar Equipamento:** troca um conjunto inteiro (por exemplo, arma e escudo por uma arma de duas mãos).
   - **Munição:** sacar faz parte do Ataque (D-069).
6. **Armaduras não se trocam numa Cena Tática** (D-072). Proponho uma frase com o link, porque quem lê Trocar Equipamento pode achar que a regra vale para tudo.
7. **Estrutura.** A página tem um título "Trocar Equipamento" dentro da página de mesmo nome, e "Sacar não é Trocar" repete o começo. Proponho três partes curtas: Sacar e Guardar, Trocar Equipamento e Pegar do Chão.

## Propostas

### P-46.1 · Uma interação livre por Turno (modelo do 5e)

> **Sacar e Guardar.** Uma vez por Turno, o personagem pode **sacar ou guardar um equipamento** sem gastar Ação, como parte da Movimentação ou da Ação. Soltar um equipamento no chão nunca exige Ação.
>
> **Trocar Equipamento.** Fazer mais do que isso no mesmo Turno, como guardar uma arma e sacar outra, exige a Ação **Trocar Equipamento**. Ela permite trocar um item ou um conjunto (arma e escudo por uma arma de duas mãos, por exemplo), desde que a mudança caiba no Turno.
>
> **Pegar do Chão.** Pegar um equipamento do chão exige Trocar Equipamento, mesmo com uma mão livre. Isso inclui recuperar uma arma perdida por [Desarmar](../Cenas%20e%20Conflitos/A%C3%A7%C3%B5es/Manobras.md#desarmar).
>
> Armaduras não podem ser vestidas nem tiradas durante uma Cena Tática (ver [Vestir e Tirar](Armaduras.md#vestir-e-tirar)).

- Saem "pela primeira vez", "Sacar não é Trocar" e o caso de jogar no chão para pegar outro (agora coberto pela interação livre).
- **Alternativa:** manter o modelo atual e só fechar a brecha: "soltar um equipamento e sacar outro no mesmo Turno conta como Trocar Equipamento".

### P-46.2 · Equipamentos

- Em Equipamentos, a descrição do link passa a ser "sacar, guardar e trocar equipamentos durante a Cena Tática".

## Decisões do autor (2026-11-05)

- "concordo": P-46.1 e P-46.2 aprovadas como propostas (D-074).
