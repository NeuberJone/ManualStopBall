# Pendências para Homologação

Este arquivo reúne dúvidas que **não devem virar regras automáticas sem confirmação**.

| ID | Prioridade | Tema | O que falta decidir |
|---|---|---|---|
| P-001 | Alta | Diamante Premium × Seleção | Identificar qual composição A/B corresponde a cada variante dos gabaritos e se existem versões adicionais |
| P-002 | Alta | Gabaritos | Conferir todas as pranchas e padronizar nomenclatura/tecido por componente antes de homologar exportação |
| P-003 | Alta | Escudo DTF | Definir se o recorte branco “2 mm menor” significa 2 mm por lado ou total |
| P-004 | Alta | Short feminino de viés com arte central | Definir qual exceção de modelagem prevalece |
| P-005 | Alta | Bermuda de juiz | Confirmar posição dos três bolsos; existe referência a dois laterais + terceiro não especificado |
| P-006 | Alta | Autoridade de aprovação | Definir aprovadores formais de layout, saída, exportação e impressão |
| P-007 | Alta | Exceções de pedidos | Formalizar quando o líder decide e como o pedido deve ser atualizado |
| P-008 | Média | Margem de costura | Confirmar como os 1,5 cm se aplicam a cada componente/borda |
| P-009 | Média | Bainha 4 cm | Validar com PNG técnico a descrição de 2 cm internos e 2 cm externos |
| P-010 | Média | Distância de 8 cm na barra | Confirmar início/fim da medição e exceções por tipo de peça |
| P-011 | Média | Gola e viés | Confirmar sentido de corte, unidade e medição das referências de 5, 6 e 7 cm |
| P-012 | Média | “Molde Total 90” | Esclarecer significado técnico e unidade |
| P-013 | Média | Nome GG+ | Verificar se o limite histórico de 30 cm continua vigente e para quais produtos |
| P-014 | Média | Escudo 4D | Definir destino dos arquivos, marcação e controle de produção |
| P-015 | Média | Escudo removido / Tamanho padrão | Definir qual objeto remanescente deve receber a propriedade |
| P-016 | Média | Etiqueta Linha Bronze | Determinar se a orientação de um pedido sobre retirar etiqueta vale para toda a linha |
| P-017 | Média | Ribanas especiais | Definir exceções de estoque, impressão e envio |
| P-018 | Média | Teste de cor, espelhamento, máquinas | Homologar parâmetros operacionais por tecido/modelo e responsáveis |
| P-019 | Média | Checklists | Confrontar item a item com 140 verificações da versão PDF anterior, preservando códigos |
| P-020 | Alta | Fontes históricas | Ler integralmente páginas manuscritas e históricos de chats, incluindo imagens disponíveis |
| P-021 | Média | Imagens | Receber PNGs finais e aprovar contornos, medidas e posicionamentos |
| P-022 | Média | Repositório público | Autorizar importação de PDFs/imagens de clientes e de documentos internos |
| P-023 | Baixa | Calandra, laser, bordado etc. | Delimitar interfaces versus POPs próprios de outros setores |

## Método de validação

1. Confirmar a resposta com a pessoa/setor competente.
2. Registrar decisão, data, fonte e alcance (todas as linhas ou apenas o pedido).
3. Atualizar o procedimento e o checklist vinculados.
4. Referenciar o registro no changelog e efetuar revisão em pull request.
5. Não registrar como “regra confirmada” interpretações criadas somente durante a redação.

## Observação de abrangência

A auditoria anterior citou 114 requisitos, dos quais 85 presentes, 18 parciais, 6 ausentes e 5 pendentes. Esses números são **resultado de uma auditoria preliminar**; não comprovam 100% de cobertura do material recebido.


## Complemento de pendências — auditoria 0.5

- **P-024:** confirmar convenção de variantes de escudo quando houver múltiplos escudos no layout (cor, contorno, aplicação e peça).
- **P-025:** definir formalmente os detalhes de gola, incluindo componente físico versus detalhe sublimado, por linha/modelo.
- **P-026:** confirmar abrangência do termo TRV e da regra contextual de nome igual em todas as camisas.
- **P-027:** padronizar identificação das listas quando um pedido contém vários layouts.
- **P-028:** transcrever as páginas restantes da reunião de arte-finalistas e os demais PDFs manuscritos, confrontando o contexto com o pedido original.
- **P-029:** identificar diferenças entre os históricos completos de WhatsApp e as exportações compactas atualmente publicadas.
- **P-030:** homologar parâmetros de execução da impressão/calandra; as evidências atuais não os especificam suficientemente.

## Complementos — revisão manuscrita 0.6

- **P-031:** confirmar se a orientação histórica de não aplicar logo StopBall em peças para igreja/evento continua vigente, em que linhas e com quais exceções.
- **P-032:** conferir se a faixa de capitão anotada em reunião como 8 cm é uma medida atual, para qual modelo, e quem aprovou.
- **P-033:** confirmar se a lona sublimada é padrão para patch 3D ou se a decisão é sempre explícita no pedido.
- **P-034:** verificar mudança histórica de 0,5 cm em parte interna da gola Seleção antes de alterar qualquer molde.
- **P-035:** formalizar status de pedido (ativo, cancelado, revisado, em aprovação) e autoridade para reabertura/liberação.
- **P-036:** confrontar divergências entre previsão impressa, campo do sistema e ordem do setor sem presumir qual está atualizado.
- **P-037:** conferir páginas 1–16 e 24–30 de Notes 2 e os outros documentos manuscritos ainda não transcritos.

## Situação da reconciliação de checklists — 0.7

- **P-019 (atualização):** a comparação direta entre o legado v1.4 e o integrado v0.2 está **concluída quanto a IDs e textos**: 98/98 preservados; integrado com 141 verificações, 0 duplicatas. A equivalência operacional com ocorrências e manuais anteriores **ainda não está homologada**.
- **P-038:** conferir se os 141 itens cobrem todos os requisitos textuais desta conversa e dos arquivos de fonte, principalmente detalhes de Impressão e Exportação não explicitados nos checklists antigos.
- **P-039:** validar as três verificações do tipo `V` (`EXP-05`, `EXP-07`, `EXP-09`) antes de automação ou exigência universal.

## Pendências de acervo e grids — revisão 0.8

- **P-040:** validar tabela de nomes antigos e atuais de peças, mangas, golas e recortes antes de automatizar renomeações.
- **P-041:** inspecionar versão vigente dos grids para confirmar ou descartar problemas históricos de camadas erradas, manga curta/longa e objeto duplicado.
- **P-042:** verificar cobertura atual de modelos como cropped, futebol americano, agasalhos, bata, Long Line e Seleção FE, sem assumir disponibilidade pela anotação antiga.
- **P-043:** confirmar interpretação e alcance da anotação de 8 cm em uma referência de telinha (Notes 2, p.27); não usar como medida atual.
- **P-044:** continuar auditoria dos outros PDFs manuscritos e das versões de históricos que não constam integralmente dos arquivos compactos publicados.
- **P-037 (atualização):** inspeção visual de Notes 2 **concluída para as 30 páginas** em AUD-006 e AUD-008; permanecem pontos de escrita ilegível e validação de contexto de pedidos, além de outras fontes.
