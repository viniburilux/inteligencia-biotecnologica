# Provenance pública

A provenance desta camada responde a quatro perguntas: **qual é a fonte, quando ela foi observada, que transformação foi feita e o que continua incerto?**

## Release atual

A release pública atual é [`inteligencia-biotecnologica-public-v2`](manifest-publico-v2.json). Ela reúne uma seleção metadata-only do snapshot cumulativo Agro, com textos originais de comunicação, identificadores públicos, relações selecionadas, estados epistemológicos e limitações.

O [registro de evidências V2](evidence-register-v2.json) organiza as fontes das trilhas de produção local/on-farm, Trichoderma industrial, Petrobras–microalgas e Pivot Bio, além das âncoras já públicas CMRP 4490, LABIM22 e Ag75/Ag109.

## Fontes principais

| Fonte | Papel público | Limite de interpretação |
|---|---|---|
| [OpenAlex](https://openalex.org/) | Literatura, autores, instituições e relações bibliográficas. | Cobertura e normalização dependem do índice e da data de consulta. |
| [Crossref](https://www.crossref.org/) | Registros bibliográficos e identificadores persistentes. | Registro bibliográfico não é validação do conteúdo científico. |
| [Google Patents](https://patents.google.com/) | Descoberta de registros patentários e identificadores de publicação. | Resultado de busca não comprova validade, vigência, titularidade ou liberdade de operação. |
| [INPI](https://www.gov.br/inpi/pt-br) | Contexto e referências oficiais para propriedade industrial no Brasil. | Campos e condições de acesso devem ser verificados na fonte oficial. |
| [MAPA](https://www.gov.br/agricultura/pt-br) | Contexto regulatório relacionado ao domínio Agro. | Menção documental não equivale a registro ou autorização regulatória. |
| [Embrapa AgroAPI](https://www.embrapa.br/agroapi) | Referência para fontes públicas de agricultura digital e bioinsumos. | Acesso, quotas e redistribuição dependem dos termos da API. |

## Como acompanhar um achado

1. Comece pela narrativa em `evidence/`.
2. Abra o identificador ou URL da fonte externa.
3. Consulte o estado epistemológico e a limitação junto do achado.
4. Verifique no registro V2 a data de observação, o tipo de fonte e a transformação aplicada.
5. Use o manifesto para conhecer escopo, snapshot, deduplicação e exclusões da release.

## O manifesto público

O arquivo [`manifest-publico-v2.json`](manifest-publico-v2.json) resume o escopo, as fontes, a política de seleção, o snapshot, os artefatos publicados e as exclusões deliberadas. O [registro de evidências](evidence-register-v2.json) detalha cada identificador usado nas trilhas.

A extensão editorial [`manifest-publico-product-001.json`](manifest-publico-product-001.json) registra a nova porta de produto: a homepage passou a oferecer exploração e investigação, e a rota [`/copiloto/`](../site/copiloto/index.html) apresenta o Copiloto como demonstração guiada. Essa extensão não altera o conhecimento-base nem expõe a infraestrutura privada.

Os hashes dos artefatos públicos devem ser calculados na validação final da release. O manifesto não substitui os termos de uso das fontes nem concede licença sobre textos, imagens, abstracts, claims ou documentos de terceiros.

## Cadeia de leitura

Para cada resultado público, a cadeia esperada é:

```text
fonte → identificador → captura datada → normalização → relação/sinal
      → estado epistemológico → síntese pública → limitação
```

A comunicação privilegia a sequência **achado → evidência → interpretação → limite**. Quando um campo não puder ser verificado, ele deve permanecer ausente, marcado como `insufficient` ou marcado como `blocked`. A ausência de evidência é um resultado válido.

## O que fica fora deste diretório

Não são publicados aqui arquivos brutos completos, respostas extensas de APIs, consultas completas, logs operacionais, memória de investigação, ranking de perguntas, heurísticas privadas, estados adaptativos, prompts, ASIE, pipelines internos, PDFs, textos integrais ou anexos. O repositório público mostra a sustentação dos achados, não a máquina privada que decidiu cada passo.
