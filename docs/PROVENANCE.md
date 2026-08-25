# Proveniência pública

A proveniência é parte do conteúdo, não um detalhe técnico. Cada artefato público deve permitir responder quatro perguntas: **qual é a fonte, quando ela foi consultada, qual transformação foi aplicada e o que ainda permanece incerto?**

## Registro mínimo

| Campo | Função |
|---|---|
| `source` | Fonte ou provedor de origem |
| `source_url` | URL pública de consulta ou referência |
| `retrieved_at` | Data e hora da captura |
| `source_id` | Identificador na fonte, quando houver |
| `transformation` | Normalização, deduplicação ou agregação aplicada |
| `sha256` | Hash do artefato de entrada quando útil para auditoria |
| `epistemic_status` | Estado da afirmação ou relação publicada |
| `limitations` | Restrições conhecidas de cobertura, acesso ou interpretação |

## Princípios

A transformação deve ser reversível ou explicável sempre que possível. Deduplicar não pode apagar a origem. Agregar não pode ser apresentado como observação direta. Um link para uma fonte não deve ser confundido com a cópia do conteúdo daquela fonte.

Este repositório publica uma seleção deliberada de evidências. A cadeia operacional completa, incluindo queries, memória, priorização e execução adaptativa, permanece no laboratório privado. A proveniência pública demonstra a sustentação do resultado sem revelar a implementação que conduziu cada rodada.

## Estados de leitura

`observed` é reservado ao que foi diretamente encontrado na fonte indicada. `inferred` exige uma regra de derivação identificável. `hypothesis` mantém aberta uma interpretação ainda não testada. `insufficient` e `blocked` são resultados válidos, e não falhas a serem escondidas. `rejected` e `contradicted` devem permanecer legíveis quando forem importantes para impedir uma interpretação equivocada.

## Política de atualização

Cada novo conjunto público deve informar sua versão, escopo, data, fontes e limitações. Alterações que mudem a interpretação de um achado devem gerar um registro de mudança. Se uma fonte externa deixar de permitir determinada forma de redistribuição, o artefato derivado deve ser reduzido ou removido sem apagar a explicação de que a decisão ocorreu.
