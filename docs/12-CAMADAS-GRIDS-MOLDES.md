# POP-DES-012 — Conferência de camadas, grids e identificação dos moldes

**Versão:** 0.8-draft · **Setor responsável:** Saída de Artes.  
**Origem:** [Notes 2.pdf, páginas 7–13](../fontes/extraidos/anotacoes/Notes/Notes%202.pdf) e [AUD-008](../governanca/AUDITORIA-NOTES2-V0.8.md). Este procedimento é um **controle preventivo fundamentado em ocorrências**, não uma substituição dos moldes aprovados.

## 1. Antes de preparar o grid

1. Confirmar pedido ativo, sublista, produto, linha, variante, revisão e layout aprovado.
2. Escolher o molde **existente e vigente** para modelagem, gênero e tamanho.
3. Identificar as camadas correspondentes às **peças reais**: frente, costas, mangas, gola, punhos, recortes e demais componentes.
4. Verificar se cada objeto está **na camada correta**, com nome, lado, comprimento e tipo de peça compatíveis.
5. Confirmar a distinção entre manga curta/longa e manga convencional/raglan; não usar a versão parecida por reflexo.
6. Para gola V, redonda, polo ou detalhe de gola, confirmar o **componente físico da variante**, não apenas a forma visual no layout.
7. Se o arquivo usa nomenclatura antiga e nova, suspender renomeação automática até validar a tabela de equivalências.

## 2. Erros encontrados nas notas históricas

As páginas 12–13 mostram exemplos concretos de:

- Mangas de uma variante presentes na camada de outra.
- Confusão entre mangas raglan **curtas** e **longas**.
- Golas de modelo feminino ou V colocadas na camada incorreta.
- Dianteiro de gola V duplicado.
- Peças infantis inseridas em camada incompatível.

Essas anotações justificam uma inspeção detalhada, mas **não provam que o erro ainda existe nos grids atuais**.

## 3. Conferência antes e depois do SISBolt

| Momento | O que conferir |
|---|---|
| Antes de processar | Modelo vigente, camadas, objetos, nomes, comprimento da peça, visibilidade e versões |
| Após gerar tamanhos | Quantidade real de componentes, nomes, números, posição, lado, proporção, ausência de duplicatas e objeto na camada correta |
| Antes de salvar | Arquivo efetivo atualizado e identificável |
| Antes de transferir | Checklist aplicável concluído e sublistas verificadas |

Em caso de erro, não corrigir somente uma manga ou gola: **revisar novamente o pedido inteiro**, incluindo peças, tamanhos e sublistas.

## 4. Catálogo de nomenclaturas

A página 7 registra exemplos históricos de transição de nomes de objetos e variantes de gola. **Não automatizar correspondências sem validação da equipe**.

Para cadastrar um par de nomes, exigir:

- Nome antigo exato e nome atual exato.
- Tipo de peça, gênero, linha e tamanho a que se aplica.
- Arquivo de molde de origem e revisão.
- Aprovação de alguém responsável pela modelagem.
- Teste de criação/visibilidade sem sobreposição nem perda de peças.

## 5. Família de produtos

Há menções históricas a cropped, futebol americano, shorts Seleção FE, agasalhos, bata e Long Line. Elas devem orientar **auditoria de cobertura** do catálogo de moldes e não demonstram quais tamanhos ou componentes estão disponíveis hoje.

## 6. Checklist setorial específico

- [ ] Grid corresponde à modelagem atual do pedido.
- [ ] Frente/costas, manga esquerda/direita e comprimentos estão identificados.
- [ ] Manga raglan/convencional separada corretamente, quando aplicável.
- [ ] Gola e punhos usam o componente certo.
- [ ] Camadas de MA/FE/C ou outras variantes estão corretas.
- [ ] Nenhum objeto duplicado, ausente ou oculto foi herdado do modelo ou dos Atalhos.
- [ ] Objetos foram conferidos no **arquivo efetivo pós-SISBolt**.
- [ ] Se houve falha, toda a ordem foi revisada antes de liberar.

## 7. Imagens a incluir

Os exemplos visuais definitivos devem ser preparados com capturas dos **grids reais**, sem clientes ou dados pessoais, com:
- `IMG-GRD-01`: exemplo correto de nomes e camadas de frente/costas/mangas.
- `IMG-GRD-02`: contraste de camadas erradas versus corrigidas, em manga curta/longa.
- `IMG-GRD-03`: caso de dianteiro de gola V duplicado e correto.

Até receber exemplos aprovados, manter somente as descrições técnicas.
