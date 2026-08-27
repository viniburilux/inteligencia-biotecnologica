# Mapa público de sinais V2

**Escopo:** corpus cumulativo do caso de uso em biotecnologia agropecuária
**Snapshot:** 21 de agosto de 2026
**Release pública:** `inteligencia-biotecnologica-public-v2`
**Modo:** metadata-only

## O mapa em uma frase

A biotecnologia agropecuária aparece como uma rede de sinais que atravessa organismos, mecanismos, culturas, processos, formulações, instituições e aplicações. O mapa é feito para descobrir relações e perguntas; não para declarar vencedores, produtos validados ou plataformas únicas.

## Composição do corpus

| Fonte | Obras/registros |
|---|---:|
| OpenAlex | 422 |
| Crossref | 146 |
| Google Patents | 195 |
| **Total** | **763** |

| Estrutura observada | Quantidade |
|---|---:|
| Atores normalizados | **2.680** |
| Instituições normalizadas | **767** |
| Relações observadas | **4.045** |
| Sinais de aplicação | **536** |

A soma por fonte representa o snapshot cumulativo utilizado na investigação. Um mesmo item pode atravessar consultas, famílias ou representações antes da deduplicação conservadora; por isso, “obras/registros” não deve ser interpretado como número de tecnologias únicas.

## Trilhas que ganharam forma

### 1. Produção próxima do campo

Biorreatores, fermentação, multiplicação, controle de parâmetros, módulos assépticos, kits e produção on-farm aparecem como uma cadeia funcional de documentos. O sinal é desenvolvido em [Produção local e on-farm](producao-local-e-on-farm.md).

### 2. Biocontrole e bioinsumos

Biocontrole, fungos, bioinsumos, biopesticidas, inoculantes, soja, milho, nematoides e saúde radicular formam o núcleo agrícola do mapa. Os organismos e as aplicações continuam separados quando o registro não sustenta continuidade.

### 3. Nitrogênio, fosfato e rizosfera

Fixação de nitrogênio, solubilização de fosfato, promoção de crescimento, estabilidade e liberação aparecem conectados em famílias e registros diferentes. A trilha Pivot Bio mostra como uma recorrência documental pode ser organizada como portfólio de problemas, sem virar ranking.

### 4. Trichoderma e bioprocessos

*Trichoderma* aparece em biocontrole, soforolipídeos, fermentação, celulase, enzimas, biomassa, resíduos e etanol. [A trilha industrial](trichoderma-industrial.md) mantém agricultura e biorefinaria em ramos conectados, mas não fundidos.

### 5. Resíduos, carbono e biomassa

A trilha Petrobras–microalgas associa cascalho de perfuração, biofixação de CO₂, biomassa algal e fertilizante organomineral em um corredor documental estreito. [O aprofundamento](petrobras-microalgas.md) mantém esse tamanho real.

## Como os sinais devem ser lidos

| Estado | Leitura pública |
|---|---|
| `observed` | Algo diretamente encontrado em uma fonte identificada. |
| `inferred` | Relação derivada de observações por uma regra explícita. |
| `hypothesis` | Interpretação que ainda requer teste ou fonte adicional. |
| `insufficient` | A evidência disponível não permite concluir. |
| `blocked` | A decisão está impedida por acesso ou verificação. |
| `rejected` | A rota ou seleção não atende ao critério definido. |
| `contradicted` | Há evidência incompatível com a afirmação avaliada. |

## O que o mapa não mede

O mapa não mede tamanho de mercado, novidade jurídica, validade de patente, liberdade de operação, eficácia, segurança, adoção agrícola, titularidade econômica, superioridade técnica ou adequação agronômica. A presença de um termo, ator, família ou instituição indica ocorrência no conjunto consultado; ela não resolve sozinha o significado da tecnologia.

## Proveniência

O snapshot foi derivado de OpenAlex, Crossref, páginas renderizadas do Google Patents e repositório institucional UEL, em modo metadata-only. A política pública e o manifesto V2 explicam o escopo, as transformações e as exclusões. [1] [2] [3]

> **Um sinal abre uma pergunta. Uma relação explicada aproxima a evidência. Nenhuma das duas substitui a leitura especializada da fonte.**

## Referências

[1]: ../provenance/manifest-publico-v2.json "Manifesto público V2"
[2]: ../provenance/evidence-register-v2.json "Registro público de evidências V2"
[3]: ../docs/PROVENANCE.md "Proveniência pública"
