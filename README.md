# Austroblechnum

<!-- badges: start -->
[![License: GPL (>= 2)](https://img.shields.io/badge/License-GPL%20%28%3E%3D%202%29-blue.svg)](https://choosealicense.com/licenses/gpl-2.0/)
<!-- badges: end -->

Compêndio de pesquisa do artigo científico sobre as espécies do gênero
*Austroblechnum* (Blechnaceae), Herbário FURB.

### Conteúdo

```
Austroblechnum/
├── R/                   # funções do projeto
├── analyses/            # scripts das análises, em ordem
├── data/
│   ├── raw-data/        # dados brutos (fora do git)
│   └── derived-data/    # dados processados (fora do git)
├── outputs/             # resultados (fora do git)
├── figures/             # figuras do artigo
├── make.R               # roda o projeto inteiro
├── DESCRIPTION          # metadados e dependências
└── LICENSE.md
```

### Como usar

Clone o repositório, abra `Austroblechnum.Rproj` no RStudio e rode:

```r
source("make.R")
```

Chaves de API (GBIF, speciesLink) vão no `.Renviron`, que não entra no git.

### Autores

- Guilherme Grittz ([ORCID 0000-0001-6500-4422](https://orcid.org/0000-0001-6500-4422))
- André Luís de Gasper
