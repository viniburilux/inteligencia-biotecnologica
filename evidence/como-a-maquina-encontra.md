# Como a máquina encontra uma conexão

> **Quando a primeira pergunta não abre o caminho, a inteligência não insiste no mesmo desenho: ela muda a representação.**

## O movimento

```text
PERGUNTA
   ↓
BUSCA
   ↓
RESULTADO INSUFICIENTE
   ↓
REFORMULAÇÃO
   ↓
NOVA REPRESENTAÇÃO
   ↓
CONEXÃO
   ↓
ACHADO
   ↓
EVIDÊNCIA
```

A demonstração pública não depende de mostrar o mecanismo operacional. O que importa é tornar legível o movimento intelectual: um resultado insuficiente não desaparece; ele informa que a pergunta foi representada de um jeito estreito demais.

## Exemplo 1 — Ag75 e Ag109

A busca pelo nome exato de *Bacillus velezensis* Ag75 e Ag109 não abriu uma família brasileira no filtro utilizado. Isso não foi tratado como prova de ausência. Os registros bibliográficos, porém, trouxeram mecanismos e culturas: biocontrole, solubilização de fosfato, promoção de crescimento, milho, soja, nematoides e *Sclerotinia*.

A pergunta mudou de:

```text
“Existe uma patente com este nome exato?”
```

para:

```text
“Que mecanismo, cultura e instituição aparecem ao redor desta strain?”
```

Essa nova representação abriu outras relações, inclusive a âncora CMRP 4490. [1] [2]

## Exemplo 2 — CMRP 4490

Ao seguir mecanismo, cultura e instituição, apareceu uma família patentária brasileira com *Bacillus velezensis* CMRP 4490, processo em biorreator de tanque agitado e formulações para bionematicida e/ou inoculante. Um artigo de 2021 descrevia o mesmo identificador de strain em atividade antifúngica e promoção de crescimento.

A representação passou a ser:

```text
strain
   → mecanismo
   → bioprocesso
   → formulação
   → documento
```

O resultado não foi uma conclusão automática. Foi uma ponte documental mais específica, com fonte, estado e limite disponíveis para inspeção. [3] [4]

## O que a demonstração revela

A capacidade está em três movimentos: seguir relações em vez de apenas palavras; preservar resultados negativos como informação; e trocar uma representação lexical por uma estrutura de entidades, propriedades, processos, aplicações e documentos.

O público pode ver o efeito desse movimento sem receber as queries completas, os critérios adaptativos, a frontier, os prompts, a memória, o ASIE ou os pipelines internos. A página mostra o fenômeno de investigação; a camada de evidence mostra de onde cada afirmação veio.

## Status

`trajetória documental observada` · `metadata-only` · `mecanismo operacional não publicado`

## Limitação

> **A mudança de pergunta melhora a descoberta de relações documentais; ela não transforma automaticamente uma relação encontrada em validação científica, jurídica ou comercial.**

## Referências

[1]: ../provenance/evidence-register-v2.json "Registro público de evidências V2"
[2]: https://doi.org/10.1038/s41598-022-19515-8 "Artigo de Bacillus velezensis Ag75"
[3]: https://doi.org/10.3389/fmicb.2020.618415 "Artigo de Bacillus velezensis CMRP 4490"
[4]: https://patents.google.com/patent/BR102024016682A2/en "Família BR102024016682A2"
