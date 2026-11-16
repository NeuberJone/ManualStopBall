# Inventário de fontes originais

**Status:** inventariado e organizado. Arquivos de origem preservados sem alteração.  
**Data:** 2026-11-16.

## Organização no repositório

```text
fontes/
├── originais/
│   ├── conversas/
│   │   ├── Ajustar pedidos.zip
│   │   ├── Layautistas.zip
│   │   └── Saídas de Emergência.zip
│   └── anotacoes/
│       └── Notes-20261106T165947Z-1-001.zip
└── INVENTARIO.md
```

| ZIP original | Pasta | Conteúdo descompactado | Quantidade |
|---|---|---|---:|
| `Layautistas.zip` | `originais/conversas/` | `chat.txt`, `chat.md` | 2 |
| `Ajustar pedidos.zip` | `originais/conversas/` | `chat.txt`, `chat.md` | 2 |
| `Saídas de Emergência.zip` | `originais/conversas/` | `chat.txt`, `chat.md` | 2 |
| `Notes-20261106T165947Z-1-001.zip` | `originais/anotacoes/` | 9 PDFs | 9 |

### PDFs identificados no arquivo de anotações

1. `Notes_231223_171609.pdf`
2. `Notes_240320_101523.pdf`
3. `Notes_240319_155022.pdf`
4. `Notes_240819_173330.pdf`
5. `Coyote_240704_091144.pdf`
6. `Reunião vendedores 0403_260305_110637.pdf`
7. `Notes_240515_102603.pdf`
8. `Reunião arte finalistas_260324_085423.pdf`
9. `Notes 2.pdf`

**Nota de segurança:** o repositório é **público**. Os chats contêm registros internos e podem conter nomes ou outros dados pessoais. Por isso, os arquivos foram extraídos para conferência e inventariados, mas **não** foram adicionados individualmente à árvore pública. O ZIP original já estava público antes da reorganização; a mudança de pasta não impede o acesso a versões anteriores ou o download do ZIP por quem tiver acesso ao repositório.

## Conteúdo, responsabilidade e destino

| Tipo | Setor de referência | Tratamento recomendado |
|---|---|---|
| `Layautistas` | Layout | Extrair orientações operacionais e exemplos anonimizados |
| `Ajustar pedidos` | Interface de vendas, layout, saída | Classificar dúvidas, decisões por pedido e exceções |
| `Saídas de Emergência` | Saída, qualidade | Classificar ocorrências e ações corretivas sem nomes pessoais |
| `Notes` | Transversal | Revisar PDFs um a um e vincular regras confirmadas aos POPs |

## Próximas etapas para documentação

- Fazer extração semântica e leitura visual das páginas de notas.
- Anonimizar conversas e exemplos antes de publicar trechos.
- Alimentar `governanca/RASTREABILIDADE.md` com referências verificáveis.
- Registrar regras confirmadas, exceções específicas e conflitos técnicos sem generalização.
- Avaliar colocar os arquivos brutos em **repositório privado**, removendo-os da branch atual e de novas versões públicas após a migração; retirar do HEAD **não** elimina arquivos do histórico do Git.

> Este inventário descreve a organização e a estrutura dos arquivos; não equivale a uma auditoria de conteúdo de todos os registros.
