# AUD-007 — Reconciliação documental dos checklists antigos

**Data:** 2026-11-16  
**Arquivos comparados diretamente:** `StopBall_CHK-DES-001_Checklist_Completo_v1.4.docx` e `StopBall_CHK-DES-GERAL-001_Checklists_Integrados_v0.2.docx`, ambos disponibilizados anteriormente na conversa.

## Resultado objetivo

| Indicador | Resultado |
|---|---:|
| Itens identificados no checklist v1.4 (Saída) | **98** |
| IDs únicos do checklist v1.4 | **98** |
| Itens do checklist integrado v0.2 | **141** |
| IDs únicos do integrado v0.2 | **141** |
| Itens do legado presentes no integrado **com o mesmo código e texto** | **98 de 98** |
| Itens novos no integrado v0.2 | **43** |
| Códigos duplicados no integrado | **0** |
| Códigos antigos omitidos no integrado | **0** |

**Correção da auditoria anterior:** referências a “140 itens” estavam imprecisas. O DOCX integrado v0.2 contém **141 linhas de verificação**, incluindo `EXP-GAB-01`. Esta contagem foi refeita diretamente nas tabelas dos DOCX, não inferida do número de páginas.

## Distribuição dos 141 itens

| Prefixo | Etapa | Itens |
|---|---|---:|
| PED | Conferência inicial | 12 |
| LAY | Layout | 11 |
| GRD | Grid e modelagem | 34 |
| MAR | Marcas/patrocinadores | 9 |
| ESC | Escudos | 14 |
| SIS | Pré-SISBolt | 9 |
| POS | Pós-SISBolt | 16 |
| LIB | Liberação | 9 |
| EXP | Exportação e gabaritos | 16 |
| IMP | Impressão | 11 |
| **Total** | | **141** |

A distribuição por tipo no integrado é: **43 O**, **94 C**, **3 V** e **1 A**.

## Preservação do legado

O documento v1.4 possuía **PED 12 + GRD 31 + MAR 9 + ESC 14 + SIS 9 + POS 14 + LIB 9 = 98**.

O integrado adicionou **LAY 11, GRD 3, POS 2, EXP 16 e IMP 11 = 43**, sem retirar os itens antigos.

**Importante:** esta conclusão se refere exclusivamente aos dois DOCX citados. Não comprova que todos os requisitos de conversas, notas, manuais e PDFs estão incluídos nesses 141 itens. Também não comprova que esses itens estão formalmente aprovados.

## Migração para Markdown no repositório

Os 141 registros estão transcritos de forma individual, por código, nos seguintes arquivos:

1. [Pedido, Layout e Grid — 57 itens](../checklists/INTEGRADO-141-PARTE-1.md).
2. [Marcas, Escudos, SISBolt e Pós-processamento — 48 itens](../checklists/INTEGRADO-141-PARTE-2.md).
3. [Liberação, Exportação e Impressão — 36 itens](../checklists/INTEGRADO-141-PARTE-3.md).

Os arquivos Markdown foram verificados quanto à quantidade de linhas e unicidade dos códigos: **141/141** e **0 códigos duplicados**.

## Cuidados operacionais

- O checklist é **condicional**: não exigir prova de componente que não existe no pedido.
- `O` significa obrigatório quando a etapa aplicável existe; `C` condicional; `V` validação técnica incompleta; `A` campo de registro/automação preferencial.
- Havendo erro, **revisar o pedido inteiro e suas sublistas**, independentemente de qual item apontou a divergência.
- A classificação `V` não autoriza aplicar medidas ou padrões por inferência.
- A origem documental de cada registro é o DOCX v0.2; evidências específicas de pedidos precisam ser associadas separadamente.

## Próximas conferências ainda necessárias

1. Comparar os 141 itens com as informações textuais deste chat e os históricos de ocorrência, procurando lacunas e conflitos, não apenas preservação de IDs.
2. Auditar as páginas manuscritas que restam.
3. Distinguir controles de Layout, Saída, Exportação e Impressão que são regras confirmadas daqueles que são propostas de melhoria.
4. Integrar os PNGs aprovados e anexos binários, preservando contexto técnico.
