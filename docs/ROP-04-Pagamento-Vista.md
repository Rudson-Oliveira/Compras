# ROP-04: Contato com Financeiro para Pagamento de Compra à Vista

## Objetivo
Padronizar processo de compras à vista (PIX/Boleto)

## Frequência
Sob demanda

## Agentes Responsáveis
- Assistente Administrativo
- Analista de Compras
- Supervisor de Compras

---

## Fluxo de Ações - Pagamento PIX

### Ação 1 - Abertura de Requerimento
1. Acessar `www.hospitalar.app`
2. Navegar: Módulos > Financeiro > Requerimentos emitidos > Adicionar requerimento
3. Preencher dados solicitados:
   - Fornecedor
   - Data de vencimento
   - Prioridade
   - Forma de pagamento
   - Demais informações
4. Salvar
5. Adicionar item:
   - Paciente
   - Tipo de pagamento
   - Descrição
   - Justificativa
   - Valor
6. Salvar

### Ação 2 - Solicitação de Pagamento
1. Anotar número do requerimento gerado
2. Enviar mensagem pelo WhatsApp com o número do requerimento solicitando pagamento
3. Ligar no **Ramal 21** (Financeiro) e informar urgência

### Ação 3 - Acompanhamento
1. Receber comprovante de pagamento via WhatsApp do Financeiro
2. Encaminhar para o fornecedor
3. Monitorar entrega dos produtos
4. Após entrega, solicitar NF por e-mail ou WhatsApp
5. Dar continuidade conforme **ROP-02** (Controle de Notas Fiscais)

---

## Fluxo de Ações - Pagamento Boleto

### Ação 1 - Compra e Protocolo
1. Providenciar compra com fornecedor ou pelo site
2. Imprimir boleto
3. Anotar no boleto:
   - Item comprado
   - Número da demanda
4. Assinar e carimbar o boleto
5. Protocolar o boleto:
   - `Área de trabalho > Servidor de dados > Compras > 1 Setor > 27 Protocolos`
   - Abrir arquivo `notas fiscais/boleto`
   - Habilitar edição
   - Digitar dados na planilha (fornecedor, data, número do boleto, valor, etc.)
   - Salvar e imprimir planilha

### Ação 2 - Entrega ao Financeiro
1. Levar ao setor Financeiro o protocolo + boleto
2. Seguir **ROP-02** (Controle de Notas Fiscais) - Ação 4

### Ação 3 - Acompanhamento
1. Monitorar entrega dos produtos
2. Após entrega, solicitar NF por e-mail ou site
3. Dar continuidade conforme **ROP-02** (Controle de Notas Fiscais)

---

## Gerenciamento de Riscos

| Risco | Mitigação |
|-------|----------|
| Produto não ser entregue | Monitoramento ativo e cobrança ao fornecedor |
| Produto entregue com divergência | Conferência com pedido de compra antes de aceitar |

---

## Recomendações

- Dar continuidade no pós-compra
- Digitar nota fiscal na planilha do produto comprado

---

## Contatos

- **Financeiro**: Ramal 21

---

## Locais de Armazenamento

- **Protocolos**: `Servidor de dados > Compras > 1 Setor > 27 Protocolos`
- **ROP Original**: Setor da Garantia da Qualidade (Coordenação do SAD)

---

*Última revisão: 12/2024 (Revisão 03)*
