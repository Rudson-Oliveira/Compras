# ROP-03: Recebimento de Solicitação e Fechamento de Compras na Cidade (Urgentes)

## Objetivo
Padronizar processo logístico de compra na cidade ou urgentes.

## Frequência
Sob demanda

## Agentes Responsáveis
- Assistente Administrativo
- Analista de Compras
- Supervisor de Compras

---

## Fluxo de Ações

### Ação 1 - Recebimento e Verificação da Demanda
1. Acessar `www.hospitalar.app`
2. Navegar: Módulos > Administrativo > Demandas > Demandas recebidas
3. Visualizar demandas em aberto (ID)
4. Verificar:
   - Nome do paciente
   - Se a compra será necessária na cidade do paciente
   - Quantidade e nome do medicamento/material
   - Se pode ser genérico ou Ethicon
   - Se a receita está na residência do paciente
   - Se o medicamento/material está autorizado
   - Número do aditivo
5. Visualizar arquivos da receita
6. Salvar receita para enviar aos fornecedores

### Ação 2 - Cotação
1. Verificar a cidade do paciente
2. Enviar cotação aos fornecedores cadastrados no WhatsApp da cidade do paciente
3. Se a compra não for na cidade, orar com fornecedores por e-mail ou sites

### Ação 3 - Análise e Fechamento
1. Realizar **mínimo 3 orçamentos** para cada pedido
2. Finalizar com melhor preço, qualidade e prazo de entrega
3. Enviar dados do paciente:
   - Nome completo
   - Endereço para entrega
   - Dados da Hospitalar para emissão de NF
4. Solicitar dados para pagamento (caso seja PIX)

### Ação 4 - Pagamento
Após fechamento da compra, seguir **ROP-04** (Contato com Financeiro para Compra à Vista)

### Ação 5 - Acompanhamento
1. Receber comprovante de pagamento via WhatsApp do Financeiro
2. Encaminhar para o fornecedor
3. Monitorar entrega dos produtos
4. Após entrega, solicitar NF por e-mail ou WhatsApp
5. Dar continuidade conforme ROP-02 (Controle de Notas Fiscais)

---

## Gerenciamento de Riscos

| Situação | Solução |
|----------|--------|
| Item específico não encontrado | Solicitar empréstimo em hospital mais próximo |
| Empréstimo não disponível | Realizar compra em Pouso Alegre e enviar via motorista |
| Nenhuma alternativa anterior resolveu | Informar Farmácia para contato com médico solicitando substituição |

---

## Recomendações

- **SEMPRE** solicitar informação sobre prazo de aquisição e entrega do item
- Manter atualizado o cadastro de fornecedores por cidade no WhatsApp

---

## Locais de Armazenamento

- **ROP Original**: Setor da Garantia da Qualidade (Coordenação do SAD)

---

*Última revisão: 12/2024 (Revisão 03)*
