# Especificação

## Finalidade e público

Demonstrar em atividade individual um fluxo documentado de apoio informacional jurídico para estudante/avaliador: relato fictício, minimização, RAG manual, verificação, auditoria e revisão humana.

## Escopo

Questão didática de consumo: possível vício em notebook e informação de oferta. Fontes limitadas às duas leis públicas indicadas em `apoio/`. Não é parecer, petição, decisão sobre responsabilidade ou cálculo de indenização.

## Fluxo

1. Identificar a ficção e inventariar identificadores no relato bruto.
2. Minimizar para a versão sanitizada, preservando fatos pertinentes e lacunas.
3. Consultar somente trechos localizados nas fontes selecionadas.
4. Registrar afirmações/conferência em `evidencias/verificacao.md`.
5. Auditar pelo prompt e registrar achados.
6. Revisão humana decide manter/corrigir/excluir e explica o motivo.
7. Emitir orientação revisada com limites e fontes.

## Critérios de aceitação

- Ficção explícita e coerente, sem dados reais.
- Sanitização remove identificadores e preserva lacunas relevantes.
- Afirmações jurídicas apontam fonte, artigo e trecho.
- Prompt restringe fontes, exige insuficiência explícita e proíbe invenções.
- Verificação, auditoria, decisão humana e entrega são rastreáveis.
- README registra finalidade, público, limites, fluxo, critérios e URL real após publicar.

## Orientação a outra pessoa

Comece pelo README; não use relato bruto como entrada de consulta. Leia limites, utilize apenas fontes listadas e registre mudanças de entendimento nas evidências.

## Versionamento

Faça commit descritivo durante a avaliação e publique no GitHub pessoal. Registre a URL pública somente após publicação efetiva.
