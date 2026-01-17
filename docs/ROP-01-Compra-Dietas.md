# ROP-01: Recebimento de Solicitação e Fechamento de Compras de Dietas

## Objetivo
Padronizar processo logístico de compra de dieta.

## Frequência
Mensal - por volta do dia 12 de cada mês

## Agentes Responsáveis
- Assistente Administrativo
- Analista de Compras
- Supervisor de Compras

---

## Fluxo de Ações

### Ação 1 - Recebimento da Demanda
1. Acessar `www.hospitalar.app`
2. Navegar: Módulos > Administrativo > Demandas > Demandas recebidas
3. Visualizar demandas em aberto (ID)
4. Visualizar arquivos
5. Salvar arquivo em: `Servidor de dados > Uso Diário > Dietas > 2024 > [mês]`

### Ação 2 - Cotação
1. Encaminhar planilha via e-mail ou WhatsApp para todos os fornecedores de dietas
2. Solicitar orçamentos
3. Aguardar retorno de todos pelo prazo estipulado

### Ação 3 - Análise e Fechamento
1. Receber orçamentos de cada fornecedor
2. Analisar custo-benefício de cada item ofertado
3. Conferir valores do mês anterior
4. Fechar pedido com melhor preço, condição de pagamento e prazo de entrega

### Ação 4 - Lançamento do Pedido
1. Acessar: `Servidor de dados > Uso Diário > Dietas > 2024`
2. Copiar modelo da planilha referente ao fabricante (ex: Nestlé)
3. Colar na pasta referente ao mês
4. Renomear planilha com nome do fabricante
5. Lançar pedido de compra com todos os dados
6. Filtrar pedido por fornecedor
7. Ocultar colunas ID/NF/STATUS
8. Capturar tela e encaminhar para cada fornecedor

### Ação 5 - Acompanhamento de Notas Fiscais
1. Aguardar 2-3 dias para faturamento e emissão de NF
2. Após recebimento das NFs, conferir com pedido de compra
3. Lançar número da NF na planilha
4. Registrar data de validade

### Ação 6 - Follow-up (dia 25)
1. Verificar se todas as entregas foram realizadas
2. Após confirmação, lançar data da entrega na planilha
3. Salvar planilha

---

## Gerenciamento de Riscos

| Risco | Ação de Mitigação |
|-------|------------------|
| Dieta faturada com validade próxima ao vencimento | Solicitar troca imediata |
| Dieta descontinuada ou falta no distribuidor | Comunicar Nutricionista SAD para possível troca |
| Dieta não entregue até dia 25 | Contatar fornecedor imediatamente (limite: 30/31) |

---

## Calendário

| Dia | Atividade |
|-----|----------|
| ~12 | Demanda de compra de dietas |
| ~25 | Follow-up de entregas |
| 30-31 | Prazo limite de entrega |

---

## Locais de Armazenamento

- **Planilhas**: `Servidor de dados > Uso Diário > Dietas > [Ano] > [Mês]`
- **ROP Original**: Setor da Garantia da Qualidade (Coordenação do SAD)

---

*Última revisão: 12/2024 (Revisão 03)*
