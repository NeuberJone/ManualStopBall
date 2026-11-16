# POP-DES-013 — Qualidade visual antes e após impressão

**Versão:** 0.9-draft  
**Abrangência:** verificações na interface entre Layout, Saída, Exportação e Impressão.  
**Base de evidências:** ocorrências textuais de `Saídas de Emergência (3).zip`, comparadas na [AUD-009](../governanca/AUDITORIA-FONTES-V0.9.md). **Não é ficha de parâmetros de máquina**.

## 1. Objetivo

Impedir que defeitos previsíveis na arte ou montagem só sejam descobertos depois de imprimir tecido. As ocorrências históricas incluem **emenda visível na manga**, **contorno fino desaparecendo**, **texto secundário de patrocinador que não apareceu** e **diferença importante entre fundo previsto e cor impressa**.

Um defeito observado depois de imprimir não prova automaticamente erro de impressão. Pode resultar da arte, montagem, exportação, cor, material, equipamento ou combinação desses fatores.

## 2. Layout — legibilidade e integridade

- Inspecionar patrocinadores e logos, inclusive textos pequenos, contornos e versões coloridas.
- Avaliar linhas muito finas e detalhes pequenos **no tamanho efetivo de produção**.
- Revisar resolução de bitmap/raster, qualidade de vetores e compatibilidade da arte com alterações de cor.
- Conferir fundos e variações aprovadas; não prometer correspondência de cor sem o procedimento de prova aplicável.
- Se o detalhe for essencial e não existir solução aprovada para reproduzi-lo, **devolver para decisão**.

## 3. Saída — continuidade entre componentes

- Verificar arte na posição e tamanho reais do molde; conferir manga esquerda/direita, incluindo a orientação.
- Quando o padrão percorre mais de uma região de peça, verificar **continuidade e emendas** antes de gerar tamanhos.
- Confirmar que a margem e o excedente permitem montagem sem lacuna visível.
- Validar contorno/texto de patrocinador nos elementos pós-SISBolt, especialmente em peças reduzidas.
- Conferir o **arquivo efetivo** após salvar, não apenas a prévia.

## 4. Exportação — correspondência com a arte liberada

- Receber somente arquivo de Saída liberado com revisão identificada.
- Conferir que no mapa não ocorreram recortes, escala incorreta, perda de linhas/textos ou orientação inadequada.
- Separar arquivos e mapas pelo material/tecido correto, sem presumir que uma configuração de cor sirva a todos.
- Quando houver alteração tardia na arte ou configuração, reavaliar os mapas já exportados.

## 5. Impressão — inspeção e diagnóstico

- Confirmar versão, arquivo, tecido, rolo e parâmetros **do procedimento vigente**.
- Realizar prova/teste quando exigidos, comparando com a **referência aprovada**.
- Durante a produção, observar legibilidade, continuidade, contornos e diferenças marcantes de tom.
- Se detalhe desaparecer ou houver diferença de cor: **registrar evidência e interromper o uso do arquivo potencialmente afetado**, devolvendo para investigação.
- **Não alterar perfil ICC, temperatura, velocidade ou configuração da máquina por inferência a partir destas notas.**

## 6. Registro de ocorrência

| Campo mínimo | Utilidade |
|---|---|
| Pedido/sublista e variante | Identificar todas as peças possivelmente afetadas |
| Arquivo/revisão e mapa | Rastrear a arte executada |
| Tecido, rolo e máquina | Rastrear a execução |
| Foto do defeito e referência aprovada | Comparação técnica |
| Detalhes afetados | Ex.: palavra pequena, contorno, transição de manga, fundo |
| Decisão/responsável | Corretivo e destino |
| Nova revisão/reimpressão | Identificar resultados e reposições |

## 7. Devolução e revisão integral

Ao sinalizar erro, corrigir na origem e **revisar todo o pedido**, incluindo demais sublistas, peças, tamanhos e versões, antes de liberar novas impressões. Também conferir que o mapa e o arquivo anterior não continuem na fila.

## 8. Pendências para procedimento de máquina

Permanecem por homologar: referências de aprovação de cor, critérios de aceitação/rejeição, padrões de prova por tecido, perfis, velocidade, passadas, calandra e registro de amostras.
