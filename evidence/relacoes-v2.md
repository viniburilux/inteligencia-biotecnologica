# Relações públicas V2

> **Uma rede só fica inteligente quando suas conexões têm tipo, fonte e força diferentes.**

## Como ler o mapa

O mapa público não trata toda proximidade como a mesma coisa. Uma autoria é uma relação diferente de uma invenção; uma afiliação é diferente de uma atribuição; um sinal de aplicação é diferente de uma hipótese de continuidade tecnológica.

| Tipo | O que significa | O que não significa sozinho |
|---|---|---|
| `authorship` | Autor associado a uma obra bibliográfica. | Liderança, contribuição específica ou influência. |
| `inventorship` | Inventor associado a um registro patentário. | Titularidade atual, exploração ou validade. |
| `affiliation` | Obra ou inventor associado a uma instituição. | Parceria comercial ou endosso. |
| `assignment` | Registro apresenta titular ou cessionário. | Exclusividade, liberdade de operação ou valor. |
| `application_signal` | Termo de aplicação aparece em metadata ou snippet. | Eficácia, segurança ou produto disponível. |
| `observed_relation` | Relação explicitamente sustentada pelos registros consultados. | Causalidade ou continuidade completa. |
| `inferred` | Relação agregada derivada por regra de leitura explícita. | Fato observado em uma única fonte. |
| `hypothesis` | Interpretação aberta que requer evidência adicional. | Conclusão. |

## Relações em destaque

```text
CMRP 4490 ──[observed_relation: strain/document]──> artigo + patente
CMRP 4490 ──[application_signal]──────────────────> biocontrole / biorreator / formulação
LABIM22 ────[observed_relation]───────────────────> soja / mofo branco / patente
Trichoderma ─[application_signal]─────────────────> biocontrole / enzimas / fermentação
Simple Agro ─[inventorship/assignment metadata]────> multiplicação / formulado
Solubio ────[inventorship/assignment metadata]────> produção na propriedade
Pivot Bio ──[observed_relation: portfolio signal]─> nitrogênio / fosfato / estabilidade
Petrobras ──[observed_relation]───────────────────> microalgas / CO₂ / fertilizante
UEL/IAP ────[inferred corridor]───────────────────> múltiplas strains e tecnologias
```

O desenho acima é um mapa de leitura, não um grafo operacional. Famílias patentárias, strains e organizações continuam separadas quando a evidência não autoriza uma fusão.

## O que ganhou força

A ponte CMRP 4490 entre artigo, identificador de strain, processo em biorreator e formulação é a relação mais específica do conjunto. LABIM22 apresenta outro caminho, entre strain, aplicação em soja e composição biofungicida. A trilha Petrobras–microalgas é estreita, mas possui duas famílias patentárias relacionadas por ator, biomassa, cascalho de perfuração e fertilizante.

A produção local aparece como uma rede funcional de famílias diferentes: biorreator, fermentação, monitoramento, multiplicação, módulos on-farm e kits. A recorrência de Pivot Bio é um sinal de portfólio documental. Trichoderma é uma ponte de navegação entre agricultura e bioprocessos, não uma entidade tecnológica única.

## O que permanece aberto

A relação UEL/IAP multi-strain permanece `inferred` e não deve ser narrada como uma única plataforma. A ordenação temporal de LABIM22, CMRP 4490, Ag75, Ag109 e patentes posteriores é uma ordenação de registros, não uma progressão causal demonstrada. Ag75 e Ag109 continuam como entidades distintas, sem conexão patentária brasileira demonstrada no filtro utilizado.

## Status

`relações selecionadas` · `metadata-only` · `tipos preservados`

## Limitação

> **Conectividade documental organiza o mapa; não prova causalidade, parceria, eficácia, adoção, titularidade ou valor comercial.**

## Proveniência

As relações V2 foram sintetizadas a partir da reconstrução estrutural, dos achados patentários e do Knowledge Layer Agro auditado. A camada pública apresenta somente relações selecionadas e reescritas para comunicação; o grafo interno completo permanece no laboratório privado. [1] [2] [3]

## Referências

[1]: ../provenance/evidence-register-v2.json "Registro público de evidências V2"
[2]: ../provenance/manifest-publico-v2.json "Manifesto público V2"
[3]: ../provenance/fontes-e-limites.md "Fontes e limites de leitura"
