# POP-DES-009 — Pré-conferência de Layout para transferência à Saída

**Edição:** 0.5-draft · **Fontes:** [reunião de arte-finalistas de 24/03/2026](../fontes/extraidos/anotacoes/Notes/Reuni%C3%A3o%20arte%20finalistas_260324_085423.pdf), páginas 1–4; ocorrências textuais de `Saídas de Emergência`.

Este documento registra riscos observados e controles de qualidade para a interface entre Layout e Saída. **Não** proíbe de forma universal o uso de raster, transparência ou RGB; a restrição depende da necessidade de edição, reprodução, escala e processo.

## 1. Identificação da arte

- Pedido, sublista, variante e versão vigente identificáveis.
- Diferenciar arte de jogador de linha/goleiro quando houver mudanças de patrocínio, cor, escudo, número e posições.
- Marcar a versão efetivamente corrigida no arquivo de layout; avisar quando a correção invalidar a versão já enviada.
- Preservar na **última página do layout** as marcas e os patrocinadores originais, conforme orientação da reunião.

## 2. Vetores, bitmaps e transparência

Há registro de orientações para **vetorizar escudos da Linha Especial**, verificar qualidade dos escudos, evitar transparências desnecessárias e conferir objetos vetorizados que foram convertidos em bitmap.

### Verificação prática

1. Verificar se a arte tem resolução, definição, bordas e contraste suficientes **no tamanho real da produção**.
2. Se a cor de um elemento rasterizado precisar ser alterada, verificar se o arquivo permite a alteração sem degradação.
3. Evitar expandir bitmap serrilhado para cobrir molde maior sem nova aprovação da qualidade.
4. Examinar transparências e efeitos que possam aparecer diferentes na saída ou na exportação.
5. Para escudo que exija vetor, confirmar o **arquivo vetorial efetivo** e não apenas uma imagem visualmente semelhante.

> **Ocorrência documentada:** um layout estava em bitmap/RGB, com arte encostada à margem e sem excedente para preencher o grid; esticar e repetir a imagem apresentaria serrilhado. Isso demonstra um risco técnico, não uma regra de que todo bitmap/RGB seja inválido.

## 3. Composição para o molde

- Conferir **excedente de arte** necessário para completar a peça sem emenda ou faixa aparente.
- Identificar áreas próximas de gola, ombro, recortes, punho e barra.
- Conferir se o patrocinador atravessa o recorte de modelagem; se a redução prejudicar a leitura, **consultar o líder** e formalizar exceção.
- O gabarito é referência geométrica; arte e patrocinador não podem ser substituídos por um desenho improvisado do molde.
- **Bandeiras:** preparar no tamanho real e depois reduzir proporcionalmente quando aplicável.
- Cuidado com imagens de QR Codes em tamanho final, para não perder capacidade de leitura; medidas concretas ainda dependem do pedido.

## 4. Prevenir defeitos encontrados nos históricos

| Risco | Conferência recomendada |
|---|---|
| Aplicação omitida em uma variante | Comparar frente/costas/mangas/short entre variantes |
| Escudo sem contorno autorizado ou contorno de cor incorreta | Confirmar escudo e contorno da versão aprovada |
| Logo muito perto da gola | Verificar posicionamento e interação com costura/recorte |
| Emenda aparente de arte na manga | Validar continuidade visual no molde real |
| Pedido com layout de outro projeto | Conferir identificadores e a última versão |
| Correção comunicada apenas no chat | Exigir alteração no **arquivo efetivo** e identificador de revisão |

## 5. Condições de liberação

- [ ] Arte corresponde à versão aprovada e ao pedido atual.
- [ ] Escudos, patrocinadores e fontes conferidos por peça e variante.
- [ ] Vetor/bitmap/efeitos compatíveis com a aplicação e escala real.
- [ ] Excedente, emendas, margem e recortes verificados.
- [ ] Golas e detalhes especiais suficientemente especificados.
- [ ] Arquivos de referência originais preservados na última página.
- [ ] Correções foram refletidas no arquivo e não apenas nas mensagens.
- [ ] Pendências e exceções foram resolvidas e registradas.

## 6. Se houver divergência

Não improvisar, não alterar por suposição e não considerar concluído somente porque a imagem de prova parece correta. Devolver a origem, corrigir e **revisar todas as peças, versões e sublistas do pedido**.

A [auditoria de fontes](../governanca/AUDITORIA-FONTES-V0.5.md) indica de onde vem cada controle e o que ainda depende de validação.
