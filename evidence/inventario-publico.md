# Inventário público V2

**Release:** `inteligencia-biotecnologica-public-v2`
**Snapshot cumulativo de investigação:** 21 de agosto de 2026
**Publicação da projection:** 27 de agosto de 2026
**Modo:** metadata-only

## A escala que sustenta o mapa

A fotografia cumulativa desta release contém **763 obras e registros**, ligados a **2.680 atores**, **767 instituições**, **4.045 relações observadas** e **536 sinais de aplicação**. Foram executadas 17 consultas derivadas e três reformulações abriram resultados que não apareciam na representação inicial. [1]

Esses números descrevem a escala do corpus e das relações observadas. Eles não são um ranking, uma medida de relevância econômica ou uma conclusão sobre as tecnologias encontradas.

| Medida | V2 |
|---|---:|
| Obras e registros cumulativos | **763** |
| Atores normalizados | **2.680** |
| Instituições normalizadas | **767** |
| Relações observadas | **4.045** |
| Sinais de aplicação | **536** |
| Queries derivadas executadas | **17** |
| Reformulações que abriram resultados | **3** |

## Composição por fonte

| Fonte | Obras/registros observados |
|---|---:|
| OpenAlex | 422 |
| Crossref | 146 |
| Google Patents | 195 |
| **Total cumulativo** | **763** |

As fontes foram lidas em modo metadata-only. O filtro `BR` utilizado em consultas patentárias indica o recorte da busca, não prova sozinho origem brasileira, titularidade, validade ou capacidade local. [1] [2]

## Eixos tecnológicos observados

Os sinais mais recorrentes atravessam biocontrole, fungos, bioinsumos, biopesticidas, inoculantes, promoção de crescimento, fermentação, bioprocesso, nematoides, biofertilizantes, fixação de nitrogênio, solubilização de fosfato, saúde radicular, soja, milho, monitoramento de qualidade e sequestro/biofixação de carbono.

A leitura pública organiza esses sinais em quatro trilhas:

1. **Produção próxima do campo:** biorreator, fermentação, controle, multiplicação, módulos e produção on-farm.
2. **Biocontrole e biopesticidas:** organismos, mecanismos, culturas e aplicações de proteção.
3. **Nitrogênio, fosfato e rizosfera:** funções microbianas, formulações, estabilidade e entrega.
4. **Bioprocessos e transições industriais:** enzimas, biomassa, resíduos, fermentação e etanol.

Essas trilhas são formas de leitura do corpus, não categorias definitivas de mercado ou de tecnologia.

## Relações que aparecem no mapa

As relações preservadas nesta camada incluem autoria, invenção, afiliação, atribuição, associação com sinais de aplicação e conexões documentais selecionadas. Uma relação observada pode ligar um autor a uma obra ou uma strain a um registro; uma relação agregada pode ser inferida por uma regra explícita. Nenhuma dessas classes deve ser automaticamente lida como parceria, causalidade, eficácia ou adoção.

## O que a V2 torna visível

A release amplia a vitrine pública com quatro trilhas novas: produção local/on-farm, Trichoderma industrial, Petrobras–microalgas e Pivot Bio. Ela também preserva os achados anteriores sobre CMRP 4490, LABIM22 e o resultado negativo de Ag75/Ag109.

A fotografia pública continua sendo uma seleção. Ela não distribui o corpus raw, o dataset normalizado completo, documentos integrais, PDFs, anexos, sequências, dados científicos, memória adaptativa ou mecanismos operacionais.

## Proveniência e limites

Cada artefato publicado declara a fonte, o tipo de transformação, o estado epistemológico e as limitações relevantes. A seleção V2 foi derivada dos artefatos metadata-only já existentes no laboratório Agro; nenhum documento novo foi coletado para esta release. O [manifesto V2](../provenance/manifest-publico-v2.json) lista os artefatos públicos e seus hashes.

> **O inventário mostra onde o campo ficou conectado. Não afirma que toda conexão representa uma tecnologia validada, um produto comercial ou uma relação causal.**

## Referências

[1]: https://github.com/viniburilux/inteligencia-biotecnologica/blob/main/provenance/manifest-publico-v2.json "Manifesto público V2"
[2]: https://github.com/viniburilux/inteligencia-biotecnologica/blob/main/provenance/evidence-register-v2.json "Registro público de evidências V2"
