# Dados para o estudo do CNMAC (2021-2025)

Registro das decisões de coleta, limpeza e correção deste conjunto.

## Fonte

Anais oficiais do CNMAC, repositório da SBMAC: <https://proceedings.sbmac.org.br/sbmac/issue/archive>.

## Estrutura

- `clean/`: artigos por ano após a limpeza.

## Coleta e filtragem

1. Foram recuperados inicialmente 2.468 registros do repositório da SBMAC.
2. Usamos o modelo *Google Gemini 3 Pro* para processar os metadados brutos e a filtragem foi feita na plataforma *Gemini Notebook*.
3. A amostra inicial qualificada tinha **280 registros**.

## Correção de duplicatas

Durante a preparação do pôster foram identificados **20 registros duplicados**, o que reduziu a amostra para **260 artigos**:

- **19** duplicatas decorrentes de arquivos baixados em duplicidade durante a coleta;
- **1** duplicata presente nos próprios anais do evento.

Exemplo da verificação: o arquivo de 2022 tinha 46 entradas brutas e 27 títulos únicos.

## Conjunto corrigido

| Ano | Artigos da sessão | Total do CNMAC | % da sessão |
|---|---|---|---|
| 2021 | 69 | 570 | 12,11 |
| 2022 | 27 | 315 | 8,57 |
| 2023 | 52 | 279 | 18,64 |
| 2024 | 66 | 678 | 9,73 |
| 2025 | 46 | 346 | 13,29 |

Rede de coautoria institucional: 98 instituições e 92 conexões.

## Relação com o conjunto TEMA/TCAM

Este estudo e o de [`tcam/`](../../tcam/data/README.md) usam critérios diferentes para decidir quais artigos pertencem à sessão técnica. Para os anos em comum, as contagens podem divergir.

> Em breve.
