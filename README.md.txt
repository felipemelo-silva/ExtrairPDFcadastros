# Pokémon Graphic

Para executar o código, é necessário instalar a seguinte biblioteca: pip install pandas plotnine  

Este projeto foi desenvolvido em Python com o objetivo de realizar uma análise exploratória dos atributos dos Pokémon presentes no arquivo `Pokemon_full.csv`.

A análise considera os principais atributos de cada Pokémon:

- HP;
- Ataque;
- Defesa;
- Ataque Especial;
- Defesa Especial;
- Velocidade.

Para cada Pokémon, foi calculada a soma desses seis atributos. Em seguida, os dados foram agrupados de acordo com o tipo principal do Pokémon, permitindo calcular a pontuação média total de cada categoria.

## Visualização

O gráfico apresenta a pontuação média dos Pokémon para cada tipo principal.

Cada categoria é representada por uma cor característica do respectivo tipo, e a quantidade de Pokémon pertencentes a cada grupo é indicada por `n` ao lado do nome da categoria.

Por exemplo:

- Dragão (`n = ...`);
- Água (`n = ...`);
- Fogo (`n = ...`).

O eixo horizontal representa a **pontuação média total dos atributos**, calculada a partir da soma de:

`HP + Ataque + Defesa + Ataque Especial + Defesa Especial + Velocidade`.

## Tecnologias utilizadas

- Python
- Pandas
- Plotnine
- Google Colab

## Estrutura do projeto

```text
PokemonGraphic/
│
├── Pokemon_full.csv
├── PokemonGraphic.py
├── README.md
└── gráfico gerado