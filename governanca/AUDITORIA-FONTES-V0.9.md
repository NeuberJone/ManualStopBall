# AUD-009 — Anotações históricas restantes e cobertura das exportações de conversa

**Data:** 2026-11-16  
**Status:** levantamento visual/estrutural, **não homologação**.  
**Escopo:** PDFs curtos de anotações ainda não tratados individualmente, confronto entre versões das exportações de conversa e identificação de ocorrências ligadas à qualidade de impressão.

## 1. PDFs analisados nesta rodada

Foram renderizadas e inspecionadas **8 páginas** dos cinco PDFs listados:

| Fonte | Páginas | Conteúdo observável | Tratamento |
|---|---:|---|---|
| [Notes_240320_101523.pdf](../fontes/extraidos/anotacoes/Notes/Notes_240320_101523.pdf) | 2 | Nomes de modelos/pessoas e lembretes de pedido, quantidade, observações e alterações | **Histórico de organização**, sem procedimento técnico completo |
| [Notes_240819_173330.pdf](../fontes/extraidos/anotacoes/Notes/Notes_240819_173330.pdf) | 2 | Esboços de formas elípticas com medidas/posições numéricas | **Referência pontual** sem identificação suficiente para determinar molde vigente |
| [Notes_231223_171609.pdf](../fontes/extraidos/anotacoes/Notes/Notes_231223_171609.pdf) | 1 | Anotação isolada de dimensão “794 × 360” (sem unidade/contexto certo) | **Não utilizar como padrão** |
| [Coyote_240704_091144.pdf](../fontes/extraidos/anotacoes/Notes/Coyote_240704_091144.pdf) | 1 | Exemplo de arte de equipe com referências a fundo, contorno, olho, sombra e regata | **Estudo de arte de pedido**, não guia geral de cores/medidas |
| [Notes_240319_155022.pdf](../fontes/extraidos/anotacoes/Notes/Notes_240319_155022.pdf) | 2 | Desenho de posições relativas e números de coordenadas, sem método de medição documentado | **Referência de composição**, não parâmetro universal |

Estas oito páginas foram revistas em conjunto para **catalogar** sua utilidade. Termos manuscritos pouco legíveis e dimensões sem unidade não foram reinterpretados como instruções.

As páginas restantes de outros PDFs seguem no inventário da auditoria geral, com estado próprio; não afirmar que este lote equivale à auditoria completa de todas as fontes.

## 2. Versões dos históricos de WhatsApp: cobertura real

A auditoria anterior usou os **ZIPs compactos presentes no GitHub**, mas estes não equivalem aos históricos mais extensos enviados na conversa original. Os seguintes arquivos foram diretamente inspecionados por tamanho e conteúdo de `chat.txt`:

| Exportação disponível na conversa | Linhas em `chat.txt` | Situação frente ao GitHub |
|---|---:|---|
| `Ajustar pedidos.zip` (versão mais antiga, 147 KB) | 865 | **Não é** a mesma exportação compacta atualmente publicada |
| `Ajustar pedidos(1).zip` (160 KB) | 939 | Versão com maior extensão; **não incorporada** integralmente ao repositório |
| `Ajustar pedidos(2).zip` (3,5 KB) | 16 | Exportação curta de complemento |
| `Saídas de Emergência.zip` (2,8 KB) | 26 | Exportação curta que está no repositório |
| `Saídas de Emergência (1).zip` (81 KB) | 654 | Histórico mais extenso, fora do repositório |
| `Saídas de Emergência (2).zip` (87 KB) | 695 | Histórico mais extenso, fora do repositório |
| `Saídas de Emergência (3).zip` (99 KB) | 781 | Histórico mais extenso, fora do repositório |

**Observação sobre a nomenclatura:** o arquivo `Ajustar pedidos.zip` publicado no GitHub corresponde à exportação compacta identificada anteriormente como `Ajustar pedidos(2).zip` (aproximadamente 3,5 KB). O nome no GitHub não identifica a data/versão interna do chat. Este registro distingue os arquivos por **tamanho e número de linhas** para impedir falsas conclusões de cobertura.

**Não somar as contagens como se fossem mensagens independentes.** As versões podem compartilhar registros e apresentam intervalos diferentes; é necessário deduplicar por conteúdo/horário após conferir a estrutura das exportações.

## 3. Ocorrências de qualidade em impressão encontradas no histórico maior

No arquivo `Saídas de Emergência (3).zip` foi observada a presença textual de:

- Registro de **emenda de manga que apareceria na impressão**, indicando risco de arte/encaixe e continuidade visual.
- Registro de **contorno muito fino que desapareceu na impressão**, indicando necessidade de prova no tamanho e processo de produção.
- Registro de **texto pequeno abaixo de patrocinador não reproduzido** e **cor de fundo impressa mais escura** do que a esperada, exigindo apuração de arte, arquivo, perfil e execução.

Esses casos sustentam **controles preventivos** entre Layout, Saída, Exportação e Impressão. **Não sustentam isoladamente** determinar causa raiz, alterar perfil ICC, temperatura, velocidade ou atribuir culpa a um setor.

## 4. Lacunas que permanecem

1. Não há evidência suficiente nas notas curtas para estabelecer novas dimensões padrão de modelagem.
2. Os históricos grandes ainda não foram deduplicados nem codificados caso a caso em uma matriz de incidentes com contexto e resultado.
3. Imagens mencionadas em mensagens de chat estão ausentes do ZIP ou apenas representadas como “imagem ocultada”, portanto a cor/posição não pode ser inferida visualmente.
4. Os parâmetros de impressão específicos de tecido e calandra ainda dependem de documentação operacional atual.
5. Publicar conversas brutas adicionais num repositório público expõe dados de terceiros; a auditoria derivada não reproduz nomes, contatos nem identificadores de pedidos.

## 5. Encaminhamento documental

- Criado [POP-DES-013](../docs/13-QUALIDADE-VISUAL-PRE-IMPRESSAO.md): pontos de controle da arte, montagem, mapa e saída impressa.
- Estendido o checklist funcional com itens de legibilidade, contorno, continuidade de manga, tom e investigação de falha.
- Registrada a diferença de cobertura entre os históricos compactos públicos e versões maiores ainda disponíveis, **sem declarar que a extração está 100% concluída**.
