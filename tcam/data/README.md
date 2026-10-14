# Dados para o estudo do CNMAC (2000-2025) para a TEMA/TCAM

Registro das decisões de coleta, limpeza e correção deste conjunto.

## Fonte

Anais oficiais do CNMAC, repositório da SBMAC: <https://proceedings.sbmac.org.br/sbmac/issue/archive>.

## Estrutura

- `raw/`: coleta inicial, por ano.
- `clean/`: artigos por ano após a limpeza.

## Composição

- 440 artigos em 22 edições, entre 2000 e 2025.
- Para cada artigo: título, ano, sessão técnica, idioma, autoria e afiliação institucional.

## Linhagem da sessão

A sessão técnica não é uma entidade estável: o CNMAC renumera suas sessões conforme as áreas entram e saem da programação, então o código não serve como identificador longitudinal. A linhagem é definida por período em três fases:

| Fase | Período | Código | Artigos | Edições |
|---|---|---|---|---|
| I | 2000–2005 | ST08 | 71 | 6 |
| II | 2006–2018 | ST09 | 174 | 10 |
| III | 2019–2025 | ST04 | 195 | 6 |

## Lacunas na série

Não houve edição do evento em 2011, 2013 e 2015 (bienalidade do CNMAC no período) nem em 2020 (pandemia de covid-19). Essas lacunas não são valores zero nem falhas de extração.

## Coleta e curadoria

- A coleta e a curadoria foram feitas manualmente a partir dos anais oficiais.
- O modelo *Claude Sonnet 5* foi usado apenas para padronizar nomes de autores e siglas institucionais, com validação manual de todas as sugestões.
- A vinculação de cada artigo à sessão foi feita a partir da descrição oficial do evento e de suas divisões em cada edição, sem inteligência artificial nessa etapa.

## Relação com o conjunto CNMAC 2026

Este estudo e o de [`cnmac/`](../../cnmac/data/README.md) usam critérios diferentes para decidir quais artigos pertencem à sessão técnica. Para os anos em comum, as contagens podem divergir.

> Em breve.
