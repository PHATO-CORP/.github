<!-- PR em pt-br. Descreva o "porquê", não só o "o quê". -->

## O quê
<!-- Resumo curto da mudança. -->

## Por quê
<!-- Problema/necessidade que motivou. Se for decisão, aponte a ADR. -->

## Como validei
- [ ] `python3 .devkit/tools/doc_lint.py` verde
- [ ] todo doc novo tem frontmatter + linha `- **Status**:`

## Checklist de governança
- [ ] Branch a partir da `main`, sem commit direto na `main`
- [ ] Sem segredos nem dados pessoais no diff
- [ ] Nome de arquivo sem acento; conteúdo pt-br
- [ ] Se substitui decisão: ADR nova, a antiga marcada `SUBSTITUÍDA`
