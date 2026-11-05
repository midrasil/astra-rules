# Instruções para agentes

- Estrutura: `Readme.md` (início), `Regras/` (uma pasta por área, com a nota de mesmo nome como página da área), `Criação de Personagem/`, `Design/` (análises e rascunhos, fora da wiki) e `en/` (tradução, com os mesmos caminhos e nomes em português; pastas sem nota própria têm o título em `en/folders.json`). A wiki do Foundry (astra-engine) e o site leem só `Readme.md`, `Regras/` e `Criação de Personagem/`.
- Antes de criar ou alterar uma Competência, leia [Fundamento das Competências](Design/Competências/Fundamento.md), em especial **Progressão fixa** (de 1 a 5 Níveis) e **Escrita das Competências**.
- Use as Competências existentes em `Regras/Competências/` como referência de formato.
- Toda alteração em `Regras/` ou `Criação de Personagem/` leva a versão em inglês em `en/`, com o hash `<!-- source -->` (sha256, 12 primeiros caracteres) do arquivo em português.
- Núcleo e módulos: tudo em `Regras/` é núcleo. Cada módulo, quando existir, ganha uma pasta própria fora de `Regras/` (por exemplo, `Módulos/Magia/`), com a mesma organização por áreas e a versão em `en/`. Uma regra de módulo diz qual regra do núcleo acrescenta ou substitui.
- Ordem das áreas: a lista "Regras do sistema" do `Readme.md` é a ordem oficial, por dependência (Mecânica Básica, Personagens, Cenas e Conflitos, Movimento, Equipamentos, Resistência e Vulnerabilidade, Condições, Competências, Capacidades, Criaturas). A wiki do astra-engine deve segui-la.
