# POP-DES-APL — Escudos, personalizações e SISBolt

**Versão:** 0.4-draft. Documento técnico de apoio à [Saída de Artes](02-SAIDA-DE-ARTES.md).

## 1. Escudos e aplicações

A escolha do processo depende da especificação **do pedido atual**. Escudo, marca StopBall, etiqueta e patrocinador não são sinônimos.

### Escudo sublimado

Escudo permanece na peça e é impresso junto à arte. Quando houver **X de posicionamento/substituição**, retirar essa marcação da arte sublimada conforme o procedimento vigente.

### Escudo DTF

Retirar o escudo da sublimação da peça e preparar o arquivo separado. Foi informado um **vazado branco 2 mm menor**, sem contorno. **A convenção de “2 mm menor” (total ou por lado) não foi homologada**; até esclarecer, não definir automaticamente o recorte por interpretação própria.

### Patch 3D emborrachado

Retirar o escudo principal da peça e conservar **ponto de referência contrastante de 2 × 2 mm**. Preparar os arquivos auxiliares para DTF e corte da lona/laser de acordo com a operação aplicável.

### Patch 3D sublimado

Retirar o escudo principal, manter marca de posicionamento **2 × 2 mm**, preparar impressão separada e arquivo para o setor posterior conforme o pedido, incluindo operações de bordado/laser quando aplicáveis.

### Escudo bordado

Retirar escudo da peça **sem ponto de posicionamento**; fornecer PNG no **tamanho efetivo** para bordado.

### Escudo 4D

Preparar o escudo separado, **vetorizado ou na melhor qualidade possível**, e manter marcação **2 × 2 mm** como no 3D. O destino e os arquivos obrigatórios do processo 4D ainda estão em homologação. Não inventar procedimento de laser ou bordado para essa variante sem confirmação.

### Conferência obrigatória por aplicação

- Tipo correto de escudo e sua versão/colorização.
- Presença ou ausência de marca de posicionamento de acordo com o tipo.
- Tamanho, local e quantidade de escudos em **todas as peças aplicáveis**.
- Arquivos auxiliares gerados e nomeados corretamente.
- Nenhum escudo antigo sobrou como objeto oculto ou duplicado.
- Arquivo final de produção foi conferido, não só imagem de exemplo.

## 2. Variáveis de personalização

| Variável | Significado | Verificação |
|---|---|---|
| `NO` | Nome | Grafia, acentuação, posição, largura |
| `NU` | Número | Dígitos e zeros à esquerda, fonte, eixo |
| `AP` | Apelido | Existência/posição prevista no pedido |
| `TS` | Tipo sanguíneo | Existência/posição e informação da lista |

Nomes/números nas listas **não obrigam** aplicação quando o layout não os apresenta; a divergência exige esclarecimento.

## 3. Tamanho padrão

A propriedade **Tamanho padrão** preserva a dimensão definida para o elemento entre tamanhos gerados pelo SISBolt. Deve ser aplicada **antes** do processamento. O valor de 9 cm mencionado em exemplos de escudo é **ilustrativo/histórico**, não regra universal para todos os escudos.

Quando o escudo vai ser retirado do grid, ainda é preciso definir qual referência remanescente recebe a propriedade.

## 4. Mão livre

Ao configurar **Mão livre**, o SISBolt deixa de realizar o alinhamento/centralização automática daquele texto. O operador deve **ajustar manualmente** orientação e posição de acordo com o molde real e o layout aprovado. É incorreto assumir que ativar Mão livre centralize o objeto.

## 5. Antes do SISBolt

1. Selecionar o grid-base da modelagem: MA em G, FE em BLG ou infantil em 12A quando esses padrões forem aplicáveis.
2. Confirmar pedido, sublista, arte atual e todas as variantes.
3. Conferir fontes, estilos, acentos e nomes, mantendo os dados exatamente como aprovados.
4. Verificar propriedades de Mão livre e Tamanho padrão, além de ordem e visibilidade de objetos.
5. Confirmar que peças especiais, golas, capuzes, punhos, shorts/bermudas e recortes estão preparados.

## 6. Depois do SISBolt

1. Conferir **todas as peças geradas**, tamanhos e sublistas.
2. Comparar os nomes, números, apelidos e tipos sanguíneos com as respectivas listas.
3. Conferir zeros à esquerda, diacríticos, fontes, centralização e legibilidade.
4. Verificar escudos, logos, patrocínios, etiquetas e posições em cada variante.
5. Conferir cores e alterações de escala entre tamanhos.
6. Garantir que o arquivo real salvo contém todas as correções.
7. Se houver erro apontado, reabrir a revisão **integral do pedido**, não somente a sublista ou o objeto sinalizado.

## 7. Referência histórica — largura de nome

Os manuais anteriores registram **30 cm de largura máxima para nomes em GG e tamanhos superiores**. A liderança ainda não confirmou o alcance dessa regra; por enquanto, **não aplicá-la como parâmetro universal** sem validação formal.

## 8. Imagens técnicas

As ilustrações finais devem usar contornos de peças reais fornecidos e aprovados, com medidas verificadas. Os esquemas genéricos produzidos em revisões anteriores foram rejeitados. Ver [catálogo de imagens](../referencias/IMAGENS-E-GABARITOS.md).
