# Proveniência pública

A proveniência permite acompanhar a origem dos achados sem transformar este repositório em um espelho das fontes externas ou do laboratório privado.

## Fontes principais do inventário inicial

| Fonte | Papel público | Limite de interpretação |
|---|---|---|
| [OpenAlex](https://openalex.org/) | Literatura, autores, instituições e relações bibliográficas | Cobertura e normalização dependem do índice e da data de consulta |
| [Crossref](https://www.crossref.org/) | Registros bibliográficos e identificadores persistentes | Registro bibliográfico não é validação do conteúdo científico |
| [Google Patents](https://patents.google.com/) | Descoberta de registros patentários e identificadores de publicação | Resultado de busca não comprova validade, vigência, titularidade ou liberdade de operação |
| [INPI](https://www.gov.br/inpi/pt-br) | Contexto e referências oficiais para propriedade industrial no Brasil | Campos e condições de acesso devem ser verificados na fonte oficial |
| [MAPA](https://www.gov.br/agricultura/pt-br) | Contexto regulatório relacionado ao domínio Agro | Menção documental não equivale a registro ou autorização regulatória |
| [Embrapa AgroAPI](https://www.embrapa.br/agroapi) | Referência para fontes públicas de agricultura digital e bioinsumos | Acesso, tokens, quotas e redistribuição dependem dos termos da API |

## Manifesto público

O arquivo [`manifest-publico.json`](manifest-publico.json) resume o escopo, as fontes e os artefatos deliberadamente publicados. Ele não substitui os termos de uso das fontes nem contém as queries completas ou os hashes de cada resposta bruta do laboratório.

## Cadeia de leitura

Para cada resultado público, a cadeia esperada é:

```text
fonte → identificador → captura datada → normalização → relação/sinal
      → estado epistemológico → síntese pública → limitação
```

Quando um campo não puder ser verificado, ele deve permanecer ausente, marcado como `insufficient` ou marcado como `blocked`. A ausência de evidência é um resultado válido.

## O que fica fora deste diretório

Não são publicados aqui arquivos brutos completos, respostas extensas de APIs, consultas completas, logs operacionais, memória de investigação, ranking de perguntas, heurísticas privadas ou estados adaptativos. O repositório público mostra a sustentação dos achados, não a máquina privada que decidiu cada passo.
