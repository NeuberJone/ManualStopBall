# AUD-005 — Revisão das fontes de Layout, Saída e comunicação com Vendas

**Edição:** 2026-11-16 · **Situação:** levantamento de evidências, não homologação.  
**Objetivo:** registrar orientações que estavam ausentes ou apenas implícitas no manual v0.4 e vincular cada conclusão à fonte original armazenada no repositório.  
**Privacidade:** descrições de ocorrências foram anonimizadas; consulte as fontes com acesso autorizado. As conversas brutas estão atualmente em um repositório público.

## Fontes efetivamente consultadas nesta rodada

- [Reunião de vendedores, 05/03/2026](../fontes/extraidos/anotacoes/Notes/Reuni%C3%A3o%20vendedores%200403_260305_110637.pdf): páginas **1–4** (leitura visual).
- [Reunião de arte-finalistas, 24/03/2026](../fontes/extraidos/anotacoes/Notes/Reuni%C3%A3o%20arte%20finalistas_260324_085423.pdf): páginas **1–4** (leitura visual).
- [Ajustar pedidos — histórico antigo](../fontes/extraidos/conversas/Ajustar_pedidos/chat.md): registros textuais e casos identificados por assunto; imagens anexas não estão disponíveis na exportação.
- [Ajustar pedidos — complemento de novembro](../fontes/extraidos/conversas/Ajustar_pedidos/chat.md): registra divergência de aplicação de nomes, ressalvando que existe mais de uma versão dos históricos na conversa original.
- [Saídas de Emergência](../fontes/extraidos/conversas/Saidas_de_Emergencia/chat.md): ocorrências textuais; imagens referenciadas não foram reconstituídas.
- [Layautistas](../fontes/extraidos/conversas/Layautistas/chat.md): solicitações e referências de fontes; **não constitui manual de arte-finalização**.

> **Limitação relevante:** os dois conjuntos longos de históricos mais antigos também foram consultados por seus arquivos fornecidos na conversa, mas **não constam integralmente do repositório como arquivos independentes**. Para não criar links que levem à versão errada, os registros abaixo distinguem o histórico antigo do complemento de novembro. A consolidação por mensagem e mídia segue pendente.

## Achados e encaminhamento

| ID | Setor | Achado sustentado por fonte | Origem | Tratamento |
|---|---|---|---|---|
| AUD-LAY-01 | Layout | Fontes diferentes entre frente, costas e short precisam ser identificadas; confirmar com a criação antes de tratar como erro | Reunião vendedores, p.2, item 4 | **Controle de conferência** |
| AUD-LAY-02 | Layout | Patrocinadores e logos originais devem ficar na última página do arquivo | Reunião arte-finalistas, p.2 | **Regra reiterada** |
| AUD-LAY-03 | Layout | Bandeira deve ser construída no tamanho real e depois reduzida proporcionalmente | Reunião arte-finalistas, p.3 | **Regra reiterada** |
| AUD-LAY-04 | Layout | Arte vetorizada convertida em bitmap, transparências desnecessárias e qualidade dos escudos são riscos registrados | Reunião arte-finalistas, p.1 e p.3 | **Verificação de qualidade**; não proibição universal de bitmap |
| AUD-LAY-05 | Layout | Havia casos com bitmap/RGB sem excedente para completar o grid e arte serrilhada que pioraria ao ampliar | Saídas de Emergência, histórico antigo | **Ocorrência convertida em barreira de qualidade** |
| AUD-LAY-06 | Layout | QR Code/arte pequena em aplicação precisa de dimensão legível e confirmação em caso de dúvida | Reunião arte-finalistas, p.4 | **Controle condicionado** |
| AUD-VEN-01 | Interface vendas/layout | Identificar claramente a qual layout pertence cada lista quando houver vários layouts ou listas | Reunião vendedores, p.2, item 1 | **Regra de entrada** |
| AUD-VEN-02 | Interface vendas/layout | Se houver vários escudos e aplicação DTF, especificar exatamente qual será aplicado e se ambos serão DTF | Reunião vendedores, p.2, item 2 | **Regra de especificação** |
| AUD-VEN-03 | Interface vendas/layout | Diferenciar escudo entre layout e saída; informar revisão/correção da arte para não reutilizar a anterior | Reunião vendedores, p.2, item 3; Ajustar pedidos, histórico antigo | **Controle de versões** |
| AUD-VEN-04 | Interface vendas/layout | Gola com detalhe só deve ser interpretada após confirmação da aplicação (detalhe sublimado ou componente físico) | Reunião vendedores, p.2, item 5; Ajustar pedidos, histórico antigo | **Dúvida técnica obrigatória** |
| AUD-VEN-05 | Interface vendas/layout | Pedido que inclui nome de time no punho precisa representar essa aplicação na saída, ainda que não estivesse no layout | Reunião vendedores, p.3, item 6 | **Inconsistência que exige esclarecimento**, não autorização automática |
| AUD-VEN-06 | Interface vendas/layout | Especificar se a lona deve ser sublimada quando o escudo é patch 3D | Reunião vendedores, p.3, item 7 | **Regra de especificação** |
| AUD-VEN-07 | Interface vendas/layout | Pedido com prazo curto exige identificação e interpretação corretas antes da saída | Reunião vendedores, p.3, item 8 | **Controle de comunicação** |
| AUD-VEN-08 | Layout | Cor de teste deve estar definida no layout, em vez de só constar em pedido retirado | Reunião vendedores, p.3, item 9 | **Regra de entrada/representação visual** |
| AUD-VEN-09 | Layout | Aplicações de jogador, diretoria e comissão devem identificar quando cada camisa terá ou não a aplicação | Reunião vendedores, p.3, item 10 | **Regra de especificação por variante** |
| AUD-VEN-10 | Layout/saída | Em pedido TRV, indicar quando todas as camisas devem receber o mesmo nome | Reunião vendedores, p.3, item 11 | **Regra contextual**, significado/abrangência de TRV pendente |
| AUD-ART-01 | Saída | Atenção às artes próximas do encaixe; consultar a liderança se a posição/recorte não for viável | Reunião arte-finalistas, p.3 | **Barreira de revisão** |
| AUD-ART-02 | Saída | Verificar qualidade/contorno de escudos e detalhes que podem mudar após conversão/ajuste | Reunião arte-finalistas, p.1 e p.3 | **Conferência em arquivo efetivo** |
| AUD-ART-03 | Saída/Layout | Em arte próxima ao embarque e não concluível corretamente, comunicar o bloqueio antes de liberar | Reunião arte-finalistas, p.2 | **Controle de comunicação** |
| AUD-ERR-01 | Qualidade | Há histórico de pedido vinculado ao layout de outro projeto; o pedido atual deve prevalecer | Ajustar pedidos, histórico antigo | **Ocorrência preventiva** |
| AUD-ERR-02 | Qualidade | Houve diferença entre patrocínio de short de jogador e goleiro, não necessariamente erro quando autorizada | Ajustar pedidos, histórico antigo | **Conferir variante, não padronizar cegamente** |
| AUD-ERR-03 | Qualidade | Foram sinalizados nomes errados, número frontal incorreto e camisa impressa sem nome do time | Saídas de Emergência, complemento de novembro | **Ocorrências de controle**, não taxas individuais |
| AUD-EXC-01 | Saída | Em uma camisa Diamante foi autorizada costa inteira para evitar que o patrocínio coincidisse com o recorte | Ajustar pedidos, 13/11/2026 | **Exceção específica**, não muda padrão de toda a linha |
| AUD-EXC-02 | Saída | Nomes presentes na lista, ausentes do layout, foram expressamente autorizados para aplicação na barra | Ajustar pedidos, 13/11/2026 | **Exceção específica**; confirmar por pedido |
| AUD-EXC-03 | Layout | Um detalhe de gola SASP sem viabilidade e pedido de tag foram objeto de consulta e negativa | Ajustar pedidos, 13/11/2026 | **Caso específico**, não regra universal de gola/tag |

## Lacunas e verificação pendente

1. As **páginas 5–8** do PDF da reunião de arte-finalistas e outros PDFs manuscritos ainda exigem transcrição de cada ponto com revisão visual.
2. As fotos referidas nos históricos não estão recuperadas nas exportações; evitar conclusões sobre cor, lado e aplicação baseadas apenas em “[Imagem]”.
3. O histórico mais antigo de Ajustar pedidos/Saídas de Emergência é maior que as exportações compactas recém-publicadas. Necessário preservar identidade de versão, data de exportação e cobertura antes de deduplicar.
4. A fonte **Layautistas** comprova circulação de referências de fontes tipográficas, mas não permite definir um catálogo obrigatório de fontes sem aprovação.
5. Registros de Exportação e Impressão disponíveis até aqui são majoritariamente ocorrências e interfaces, **não especificações completas** para velocidades, perfil ICC, temperatura de calandra ou parâmetros de máquina.

## Regras para atualizar o manual

- **Regra explícita da liderança:** pode entrar como orientação registrada, com ressalva de homologação formal.
- **Reunião anotada:** registrar redação exata e dependências; usar como controle enquanto a regra estiver em revisão.
- **Ocorrência de pedido:** vira um **teste/checagem** se for um risco repetível, mas não vira automaticamente norma de modelagem ou impressão.
- **Exceção expressa para um pedido:** manter no histórico, não substituir a regra normal.
- **Informação incerta ou dependente de foto ausente:** manter em pendências.

## Próxima etapa

Transcrição visual das demais páginas manuscritas e confronto do checklist histórico item a item com a versão Markdown. Só então indicar percentuais de cobertura por setor.
