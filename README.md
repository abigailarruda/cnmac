# Mapeamento bibliométrico do CNMAC

Dados, prompts e scripts de duas pesquisas bibliométricas sobre a sessão técnica de Computação Gráfica e Matemática Discreta do Congresso Nacional de Matemática Aplicada e Computacional (CNMAC):

| Estudo | Recorte | Pasta |
|---|---|---|
| Resumo e pôster do XLV CNMAC (2026): *Tendências Recentes em Computação Gráfica e Matemática Discreta: Mapeamento Bibliométrico do CNMAC (2021–2025)* | 2021 a 2025 | [`cnmac/`](cnmac/) |
| Artigo submetido à TEMA/TCAM: *Vinte e Cinco Anos de Computação Gráfica e Matemática Discreta: Mapeamento Bibliométrico do CNMAC (2000–2025)* | 2000 a 2025 | [`tcam/`](tcam/) |

Os dois trabalhos fazem parte da pesquisa de mestrado de Abigail de J. Arruda no PPGCC/UFG, sob orientação de Hebert C. da Silva (INF/UFG).

## Estrutura

```
cnmac/
  data/
    clean/
    README.md
  prompts/
  analysis/
  README.md
tcam/
  data/
    clean/
    README.md
  prompts/
  analysis/
  README.md
```

## Diferenças metodológicas entre os estudos

Os dois estudos usam os mesmos anais oficiais, mas não o mesmo critério para decidir quais artigos pertencem à sessão técnica:

- **CNMAC 2026 (2021-2025):** inteligência artificial (*Google Gemini 3 Pro*) classificou os artigos a partir da descrição da sessão técnica, com filtragem na plataforma *Gemini Notebook*.
- **TEMA/TCAM (2000-2025):** a vinculação de cada artigo à sessão foi feita diretamente a partir da descrição oficial do evento e de suas divisões em cada edição, sem inteligência artificial nessa etapa. O modelo *Claude Sonnet 5* foi usado apenas para padronizar metadados de autores e instituições, com validação manual de todas as sugestões.

Por este motivo, os totais dos dois estudos não são diretamente comparáveis para anos em comum. Detalhes em [cnmac/data/README.md](cnmac/data/README.md) e [tcam/data/README.md](tcam/data/README.md).

## Dados

Os dados brutos e limpos seguem a estrutura descrita em [cnmac/data/](cnmac/data/) e [tcam/data/](tcam/data/). Os artigos originais pertencem aos autores e à SBMAC e estão disponíveis nos anais oficiais: <https://proceedings.sbmac.org.br/sbmac/issue/archive>.

## Como citar

Veja [`CITATION.cff`](CITATION.cff).

## Licenças

MIT ([`LICENSE`](LICENSE)) e CC BY 4.0 ([`LICENSE-DATA`](LICENSE-DATA)).
