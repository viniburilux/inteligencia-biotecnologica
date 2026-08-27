# Relações públicas identificadas

Este documento descreve classes de relações selecionadas no snapshot público V2. Ele não publica a lista completa de registros nem representa um grafo operacional completo. Para uma leitura narrativa das conexões, consulte o [mapa de relações V2](relacoes-v2.md).

## Classes de relação

| Relação | O que significa no corpus | O que não significa automaticamente |
|---|---|---|
| `authorship` | Um autor aparece associado a uma obra bibliográfica. | Liderança, contribuição específica ou influência. |
| `inventorship` | Um inventor aparece associado a um registro patentário. | Titularidade atual, exploração ou validade da patente. |
| `affiliation` | Uma obra associa um autor a uma instituição. | Parceria comercial ou endosso institucional. |
| `assignment` | Um registro patentário apresenta um titular ou cessionário. | Liberdade de operação, exclusividade ou valor econômico. |
| `application_signal` | Termos de aplicação aparecem em metadados ou snippets. | Eficácia, segurança ou disponibilidade do produto. |
| `observed_relation` | Uma relação é explicitamente sustentada pelo registro de uma fonte. | Causalidade ou continuidade completa. |
| `inferred` | Uma conexão agregada resulta de uma regra explícita de normalização ou agrupamento. | Fato observado em uma única fonte. |
| `hypothesis` | Uma interpretação aberta requer evidência adicional. | Conclusão ou recomendação. |

## Relações que ganharam resolução na V2

A V2 organiza relações públicas em torno de CMRP 4490, LABIM22, Trichoderma, produção local/on-farm, Simple Agro, Solubio, Pivot Bio, Novozymes e Petrobras. O objetivo é mostrar como entidades, propriedades, processos, aplicações e documentos se aproximam sem colapsar famílias patentárias ou strains distintas.

| Núcleo | Relação pública selecionada | Estado |
|---|---|---|
| CMRP 4490 | Strain associada a artigo, processo em biorreator e formulação patentária. | `observed_relation` |
| LABIM22 | Strain associada a aplicação em soja e composição biofungicida patentária. | `observed_relation` |
| Trichoderma | Organismo recorrente em biocontrole, fermentação, enzimas, biomassa e etanol. | `application_signal` |
| Simple Agro / Solubio | Atores associados a famílias de multiplicação, equipamento e produção on-farm. | `inventorship` / `assignment` metadata |
| Pivot Bio | Recorrência documental em nitrogênio, fosfato, estabilidade e liberação. | `observed_relation` / `application_signal` |
| Petrobras | Famílias relacionadas a microalgas, cascalho de perfuração, CO₂ e fertilizante. | `observed_relation` |
| UEL / IAP | Recorrência institucional em múltiplas strains e tecnologias. | `inferred` |
| Ag75 / Ag109 | Strains e mecanismos observados, sem continuidade patentária demonstrada no filtro usado. | `insufficient` / `hypothesis` |

## Recorrência e escala

O snapshot cumulativo V2 registra 4.045 relações observadas. Entre as instituições com maior conectividade documental aparecem Embrapa, Universidade de São Paulo, Universidade Estadual de Londrina, Universidade Federal de Santa Maria, Unesp e Universidade de Brasília. Entre os atores mais conectados aparecem Pivot Bio, Mariangela Hungría e inventores e autores associados às fontes consultadas.

A conectividade é uma propriedade do corpus e da cobertura das fontes. Ela pode refletir repetição documental, amplitude de publicação, indexação ou vocabulário da consulta. Não deve ser apresentada como ranking de importância científica, comercial ou institucional.

## Famílias e entidades continuam separadas

A mesma organização pode aparecer em várias famílias sem que elas formem uma plataforma única. Uma strain pode aparecer em literatura e patente sem que isso prove continuidade jurídica, eficácia ou adoção. Um filtro BR pode conter famílias internacionais ou registros apresentados no Brasil. O mapa preserva essas diferenças.

## Relações e estados epistemológicos

Uma relação é `observed` quando está diretamente sustentada pelo registro da fonte. Uma conexão agregada pode ser `inferred` quando resulta de uma regra explícita. Uma interpretação sobre corredor tecnológico, transição industrial ou potencial de aplicação permanece como `hypothesis` até receber evidência adicional.

A [política pública de dados](../docs/DATA_POLICY.md), a [proveniência](../provenance/README.md) e o [registro público de evidências V2](../provenance/evidence-register-v2.json) definem os limites de leitura.
