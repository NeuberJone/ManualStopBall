# POP-DES-010 — Devoluções entre Exportação e Impressão

**Edição:** 0.5-draft · **Natureza:** protocolo de rastreabilidade e prevenção de erros; **não** é ficha de parâmetros de máquina.

## 1. Finalidade

A exportação prepara o mapa de impressão a partir da saída liberada, levando em conta tecido, viés, partes e arquivos auxiliares. A impressão executa o mapa e comunica falhas de correspondência. Este procedimento consolida o que já foi informado sobre essas interfaces e sobre a regra de revisão integral.

## 2. Antes de exportar

- [ ] Pedido/sublista e **versão da saída efetiva** identificados.
- [ ] Linha e gabarito correspondem à versão aprovada.
- [ ] Material por componente foi conferido; o controle de **tecidos e rendimento do viés pertence à exportação**.
- [ ] Todas as peças previstas e quantidades foram consideradas.
- [ ] Não ficou componente de DTF, patch, bordado, lona/laser ou outra produção auxiliar sem destinação.
- [ ] A separação respeita o tecido/rolo correspondente; não misturar materiais com perfis operacionais distintos por suposição.
- [ ] Arquivo exportado aberto para verificar **o resultado**, não apenas a operação de exportação.

## 3. Antes de imprimir

- [ ] Arquivo corresponde ao mapa, revisão, pedido e tecido.
- [ ] Rolo e impressora selecionados conforme programação vigente.
- [ ] Espelhamento/orientação, margens, largura e sequência foram conferidos conforme procedimento técnico vigente.
- [ ] Qualidade de imagem, continuidade dos desenhos e quantidade de componentes foram examinadas.
- [ ] Quando houver divergência de escudo, patrocinador, aplicação ou dado personalizado, a produção é bloqueada antes de prosseguir.

**Não há, nas fontes consolidadas até aqui, especificações suficientes para criar uma tabela universal de velocidade, temperatura de calandra, perfil ICC, passes ou calibração.** Esses parâmetros dependem de procedimento de impressão ainda não homologado.

## 4. Quando surgir erro na impressão

1. Registrar pedido, sublista, tecido, mapa, versão, rolo, máquina e arquivo executado.
2. Descrever falha e anexar evidência do material ou do arquivo, quando disponível.
3. Identificar se é falha de **arquivo de origem, saída, exportação, execução ou insumo**. Não atribuir automaticamente ao último operador.
4. Devolver à etapa de origem para correção.
5. Após correção, realizar **revisão integral do pedido e arquivos derivados** antes de reimprimir.
6. Registrar reposição separada e ligar à ordem e ao rolo de origem.

## 5. Registros e logs de máquina

As operações mencionam **duas Mimaki TS55-1800 4C**, calandra, logs do **Neo Estampa** e registros diários **JetPrime/PrintXP**. Para medição dos logs:

- **HeightMM/1000** representa altura útil do arquivo impresso.
- **VPosMM** representa `Espaço`.
- **Não subtrair automaticamente 1 m por troca de tecido**.
- Reposições devem ter vínculo com pedido, arquivo, máquina e rolo.

Essas são regras de **análise de registros**, não parâmetros de configuração da impressora.

## 6. Critérios mínimos de transferência

| Origem | Destino | Evidência esperada |
|---|---|---|
| Saída | Exportação | Peças finais, revisão, lista, gabarito e arquivos auxiliares |
| Exportação | Impressão | Mapa, material, arquivo efetivo, quantidade e identificação |
| Impressão | Etapa posterior | Material executado, identificação do pedido e pendências |
| Impressão com problema | Origem da falha | Ocorrência documentada, evidência e pedido bloqueado |

## 7. Questões abertas

- Parâmetros de impressão específicos de cada tecido e perfil de cor.
- Critérios de teste de cor, aprovação e retenção de amostras.
- Procedimentos de calandra, intervenções na máquina e recuperação de falhas.
- Identificação da pessoa autorizada a liberar uma reposição.
- Integração efetiva de logs com o controle da produção.

As questões abertas não impedem documentar o controle de fluxo, mas impedem apresentar este texto como **SOP completo de máquina**.
