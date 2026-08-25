# Relações públicas identificadas

Este documento descreve classes de relações observadas no inventário público inicial. Ele não publica a lista completa de registros nem representa um grafo operacional completo.

## Classes de relação

| Relação | O que significa no corpus | O que não significa automaticamente |
|---|---|---|
| `authorship` | Um autor aparece associado a uma obra bibliográfica | Liderança, contribuição específica ou influência |
| `inventorship` | Um inventor aparece associado a um registro patentário | Titularidade atual, exploração ou validade da patente |
| `affiliation` | Uma obra associa um autor a uma instituição | Parceria comercial ou endosso institucional |
| `assignment` | Um registro patentário apresenta um titular/cessionário | Liberdade de operação, exclusividade ou valor econômico |
| `application_signal` | Termos de aplicação aparecem em metadados ou snippets | Eficácia, segurança ou disponibilidade do produto |

## Relações de maior recorrência

O primeiro inventário registra 2.093 relações. Entre as instituições com maior conectividade documental aparecem a Embrapa, a Universidade de São Paulo, a Universidade Estadual de Londrina, a Universidade Federal de Santa Maria, a Unesp e a Universidade de Brasília. Entre os atores mais conectados aparecem Pivot Bio, Mariangela Hungría e inventores e autores associados às fontes consultadas.

A conectividade é uma propriedade do corpus e da cobertura das fontes. Ela pode refletir repetição documental, amplitude de publicação, indexação ou vocabulário da consulta. Não deve ser apresentada como ranking de importância científica, comercial ou institucional.

## Relações e estados epistemológicos

Uma relação é `observed` quando está diretamente sustentada pelo registro da fonte. Uma conexão agregada entre entidades pode ser `inferred` quando resulta de uma regra explícita de normalização ou agrupamento. Uma interpretação sobre corredor tecnológico, transição industrial ou potencial de aplicação deve permanecer como `hypothesis` até receber evidência adicional.

A [política pública de dados](../docs/DATA_POLICY.md) define os estados e os limites de uso. A [proveniência pública](../provenance/README.md) mostra como acompanhar cada classe de relação até sua fonte.
