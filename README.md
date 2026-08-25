# Inteligência Biotecnológica

> **Uma camada pública para acompanhar o que está sendo investigado, o que foi encontrado e quais perguntas continuam abertas na biotecnologia.**

[![Status](https://img.shields.io/badge/status-public%20research-blue)](docs/STATUS.md)
[![Evidence](https://img.shields.io/badge/evidence-metadata--only-green)](docs/DATA_POLICY.md)
[![Pages](https://img.shields.io/badge/site-GitHub%20Pages-orange)](https://viniburilux.github.io/inteligencia-biotecnologica/)

## O que é este repositório

A inteligência biotecnológica está espalhada por literatura científica, patentes, organizações, inventores, organismos, processos, aplicações e sinais regulatórios. Este repositório organiza uma parte desse conhecimento em uma camada pública de **investigação, evidência e síntese**.

O objetivo não é publicar uma resposta definitiva nem expor a máquina operacional que produz cada rodada de pesquisa. O objetivo é tornar legível uma trajetória: **qual problema foi observado, que pergunta orientou a investigação, quais fontes sustentam os achados, que relações apareceram e o que ainda não pode ser afirmado**.

O primeiro caso de uso é a biotecnologia agropecuária. Ele funciona como um campo de investigação concreto para testar perguntas sobre bioinsumos, biocontrole, inoculantes, biofertilizantes, microrganismos, fermentação, aplicações agrícolas e transições industriais.

## Comece pela história

A melhor porta de entrada é o [site público](https://viniburilux.github.io/inteligencia-biotecnologica/), que apresenta a investigação na ordem **problema → pergunta → investigação → evidências → achados → implicações → limitações → método**.

Para consultar os artefatos, siga para o [inventário público](evidence/inventario-publico.md), o [mapa de sinais](evidence/mapa-de-sinais.md) e a [proveniência das fontes](provenance/README.md). A documentação metodológica explica como ler os registros sem confundir presença em uma fonte com validade, novidade, viabilidade comercial ou adequação agronômica.

## O que este repositório publica

| Camada | O que você encontra |
|---|---|
| **Conhecimento** | Contexto do problema, perguntas de investigação, sínteses e relações identificadas |
| **Evidência** | Inventários, sinais, mapas, identificadores, URLs e estados epistemológicos |
| **Proveniência** | Fonte, data de captura, transformação aplicada, hashes e limitações |
| **Demonstrações** | Visualizações e exemplos metadata-only ou sintéticos |
| **Governança** | Política de dados, critérios de interpretação e limites de uso |

Os artefatos publicados foram escolhidos para demonstrar conhecimento e credibilidade sem entregar estratégias de busca, memória, priorização, heurísticas adaptativas, ciclos autônomos ou pipelines operacionais privados.

## O que não é publicado aqui

Este repositório não é uma cópia reduzida do laboratório Agro e não pretende expor sua implementação. Queries completas, corpus bruto, respostas extensas de APIs, estados adaptativos, memória de investigação, políticas internas de priorização, scripts específicos de execução e dados intermediários permanecem fora desta camada pública.

O laboratório completo de Inteligência Biotecnológica Agropecuária está no repositório privado [`inteligencia-biotecnologica-agropecuaria`](https://github.com/viniburilux/inteligencia-biotecnologica-agropecuaria). A existência desse repositório privado não altera o compromisso de tornar pública a evidência que for deliberadamente selecionada, revisada e contextualizada.

## Relação com o TraceFoundry

O [TraceFoundry](https://github.com/viniburilux/TraceFoundry) é a infraestrutura pública geral de **discovery, evidence, provenance e investigation**. Este repositório não duplica esse núcleo.

A separação é intencional:

> **TraceFoundry** fornece a infraestrutura geral.  
> **Inteligência Biotecnológica** organiza conhecimento, investigação e evidência pública sobre biotecnologia.  
> **Inteligência Biotecnológica Agropecuária** é o laboratório privado onde a investigação específica é executada.

## Como ler os resultados

Cada achado deve ser interpretado com seu estado epistemológico. `observed` indica algo diretamente sustentado por uma fonte capturada; `inferred` indica uma relação derivada por regra explícita; `hypothesis` indica uma possibilidade ainda não testada; `insufficient` indica que a evidência não basta; `blocked` registra uma limitação de acesso ou verificação; `rejected` e `contradicted` preservam resultados que não devem ser tratados como confirmação.

A presença de uma patente, artigo, empresa, universidade ou organismo em um registro não prova, isoladamente, validade jurídica, novidade, titularidade atual, disponibilidade para licenciamento, eficácia, viabilidade comercial, segurança ou adequação agronômica.

## Estrutura

```text
.
├── README.md
├── docs/
│   ├── DATA_POLICY.md
│   ├── PROVENANCE.md
│   ├── STATUS.md
│   └── metodo-e-leitura.md
├── evidence/
│   ├── inventario-publico.md
│   ├── mapa-de-sinais.md
│   └── relacoes-publicas.md
├── provenance/
│   ├── README.md
│   └── manifest-publico.json
├── examples/
│   └── metadata-only-record.json
├── site/
│   └── index.html
├── .github/workflows/
│   └── pages.yml
└── LICENSE
```

## Participação

Contribuições são bem-vindas quando melhoram a clareza da investigação, a rastreabilidade das fontes ou a distinção entre observação e interpretação. Antes de propor alterações em dados derivados, consulte a [política de dados](docs/DATA_POLICY.md) e a [política de proveniência](docs/PROVENANCE.md).

## Licença

O código e os textos originais deste repositório são disponibilizados conforme a licença indicada em [`LICENSE`](LICENSE). Metadados, abstracts, imagens, identificadores e demais conteúdos provenientes de fontes externas não são automaticamente relicenciados por este repositório e continuam sujeitos aos termos das respectivas fontes.

## Referências

[1]: https://github.com/viniburilux/TraceFoundry "TraceFoundry — infraestrutura pública geral"
[2]: https://github.com/viniburilux/inteligencia-biotecnologica-agropecuaria "Laboratório privado Agro"
[3]: https://viniburilux.github.io/inteligencia-biotecnologica/ "Site público de Inteligência Biotecnológica"
