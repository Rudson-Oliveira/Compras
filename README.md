# 📊 Setor de Compras - Hospitalar Saúde

## Visão Geral
Documentação completa do setor de Compras, incluindo ROPs (Rotinas Operacionais Padrão), SIPOC e fluxos de processos.

---

## 📊 SIPOC - Setor de Compras

### Suppliers (Fornecedores)
| Fornecedor | Tipo |
|------------|------|
| Farmácia/Almoxarifado | Demandas de medicamentos e materiais |
| Setores internos (TI, Equipamentos) | Solicitações de compra |
| Nutricionista SAD | Demandas de dietas |
| Fornecedores externos | Cotações e produtos |
| Portal Bionexo | Plataforma de cotação |
| Setor Financeiro | Pagamentos e comprovantes |

### Inputs (Entradas)
| Entrada | Origem |
|---------|--------|
| Demandas de compra | Sistema Hospitalar (www.hospitalar.app) |
| Receitas médicas | Pacientes/Residências |
| Planilhas de pedidos | Servidor de dados |
| Orçamentos | Fornecedores |
| Autorizações e aditivos | Gestão |

### Process (Processos)
| ROP | Processo | Frequência |
|-----|----------|------------|
| ROP-01 | Compra de Dietas | Mensal (dia 12) |
| ROP-02 | Controle de Notas Fiscais | Contínuo |
| ROP-03 | Compras Urgentes na Cidade | Sob demanda |
| ROP-04 | Pagamento de Compra à Vista | Sob demanda |
| ROP-05 | Inserção Medicamentos Bionexo | Mensal |
| ROP-06 | Inserção Material Hospitalar Bionexo | Mensal |

### Outputs (Saídas)
| Saída | Destino |
|-------|--------|
| Pedidos de compra | Fornecedores |
| Notas fiscais | Financeiro/Arquivo |
| Produtos entregues | Pacientes/Setores |
| Cotações Bionexo | Portal Bionexo |
| Protocolos de boleto | Setor Financeiro |
| Follow-up de entregas | Controle interno |

### Customers (Clientes)
| Cliente | Necessidade |
|---------|-------------|
| Pacientes | Medicamentos e dietas entregues |
| Setores internos | Materiais e equipamentos |
| Farmácia | Reposição de estoque |
| Financeiro | Documentos para pagamento |
| Auditoria | Rastreabilidade das compras |

---

## 📁 Estrutura de Documentos

```
Compras/
├── README.md
├── docs/
│   ├── ROP-01-Compra-Dietas.md
│   ├── ROP-03-Compras-Urgentes.md
│   ├── ROP-04-Pagamento-Vista.md
│   ├── ROP-05-Bionexo-Medicamentos.md
│   └── ROP-06-Bionexo-Material.md
├── fluxos/
│   └── fluxo-geral-compras.md
└── melhorias/
    └── sugestoes-melhorias.md
```

---

## 👥 Agentes Responsáveis

| Cargo | Responsabilidades |
|-------|------------------|
| Assistente Administrativo | Execução das rotinas operacionais |
| Analista de Compras | Análise de cotações e fechamento |
| Supervisor de Compras | Supervisão e aprovações |

---

## 📈 Indicadores do Sistema

| Métrica | Valor Atual |
|---------|-------------|
| Pedidos em construção | 0 |
| Pedidos em andamento | 27 |
| Pedidos finalizados | 1.933 |
| Pedidos reprovados | 5 |
| Taxa de aprovação | 99,7% |

---

## ⚠️ Gerenciamento de Riscos

| Risco | Mitigação |
|-------|----------|
| Produto não entregue | Monitoramento de follow-up |
| Divergência de itens | Conferência código PAI no Bionexo |
| Dieta com validade próxima | Solicitar troca imediata |
| Item descontinuado | Contato com Nutricionista SAD |
| Falta de item urgente | Empréstimo hospitalar ou substituição |

---

## 📅 Calendário de Atividades

| Dia | Atividade |
|-----|----------|
| 12 | Demanda de compra de dietas |
| 25 | Follow-up de entregas de dietas |
| Pós-reunião | Inserção pedidos Bionexo |

---

## 📞 Contatos Importantes

- **Financeiro**: Ramal 21
- **WhatsApp Fornecedores**: Grupos por cidade

---

*Documentação mantida pelo Setor de Compras - Hospitalar Saúde*
*Última atualização: Janeiro/2026*
