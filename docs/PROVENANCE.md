# Proveniência pública

A provenance é parte da comunicação. Cada achado público deve permitir responder quatro perguntas: **qual é a fonte, quando ela foi consultada, que transformação foi aplicada e o que ainda permanece incerto?**

## Release V2

A release pública atual é [`inteligencia-biotecnologica-public-v2`](../provenance/manifest-publico-v2.json). Ela foi montada a partir do snapshot cumulativo metadata-only da investigação Agro, com data de referência em 21 de agosto de 2026. A projection foi organizada em 27 de agosto de 2026 sem nova coleta.

O [registro público de evidências V2](../provenance/evidence-register-v2.json) mantém as fontes e identificadores de cada trilha nova. O manifesto V2 lista os artefatos publicados e, após a validação final, registra o hash de cada arquivo público relevante.

## Registro mínimo

| Campo | Função |
|---|---|
| `source_type` | Tipo de fonte: artigo, repositório institucional ou patente metadata. |
| `source_id` | DOI, identificador de patente ou identificador institucional. |
| `source_url` | URL pública de consulta ou referência. |
| `observed_at` | Data da observação/captura que sustenta a narrativa. |
| `transformation` | Seleção, normalização ou reescrita aplicada para a projection. |
| `sha256` | Hash do artefato público quando útil para auditoria. |
| `epistemic_status` | Estado do achado ou relação publicada. |
| `limitations` | Restrições conhecidas de cobertura, acesso ou interpretação. |

## O que foi transformado

A V2 transforma registros metadata-only e sínteses já auditadas em textos editoriais originais, tabelas de identificadores, mapas de relações e diagramas textuais. A seleção preserva o tipo de relação e o estado epistemológico, mas não pretende reproduzir o corpus interno completo.

A transformação não inclui PDFs, textos integrais, claims completas, imagens, anexos, respostas extensas de APIs ou dados experimentais. Um link para uma fonte não é uma cópia do seu conteúdo.

## Estados de leitura

`observed` é reservado ao que foi diretamente encontrado na fonte indicada. `inferred` exige uma regra de derivação identificável. `hypothesis` mantém aberta uma interpretação ainda não testada. `insufficient`, `blocked`, `rejected` e `contradicted` são resultados válidos e permanecem legíveis quando impedem uma leitura equivocada.

## Política de atualização

Cada release pública deve informar versão, escopo, data, fontes, transformação e limitações. Alterações que mudem a interpretação de um achado geram novo registro de mudança. Se uma fonte externa deixar de permitir determinada forma de referência ou redistribuição, o artefato deve ser reduzido ou removido sem apagar a explicação da decisão.

## Limites de provenance

Provenance pública permite auditar a origem e a transformação do achado; ela não entrega acesso ao laboratório. O público pode seguir um identificador até uma fonte externa, mas não recebe automaticamente o documento bruto, o corpus, o mecanismo de seleção ou a memória operacional que produziu a investigação.
