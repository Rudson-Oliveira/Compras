# ROP-05: Processo de Inserção de Pedido de Compra de Medicamentos no Portal Bionexo

## Objetivo
Padronizar processos logísticos de compras de medicamentos via portal Bionexo.

## Frequência
Mensal - após reunião de definição de datas das rotas

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
4. Visualizar arquivos > Baixar arquivo > Abrir arquivo
5. Salvar arquivo:
   - `Servidor de dados > Compras > 2 Público > 3 Pedido de Compra Medicamentos > Histórico de Pedidos > 2024 > [Mês]`

### Ação 2 - Preparação do Template
1. Acessar: `Servidor de dados > Compras > 2 Público > 9 Bionexo`
2. Abrir arquivo **template pedido de compra**
3. Selecionar a planilha de pedido de compra salva anteriormente
4. Copiar dados das **colunas A e C**
5. Selecionar planilha template de compra > célula A1
6. Colar dados copiados
7. Salvar planilha

### Ação 3 - Envio ao Bionexo
1. Acessar plataforma **Bionexo** (web)
2. Fazer login com dados do comprador
3. Navegar: Menu > Integração via arquivo
4. Selecionar layout **P TXT/CSV**
5. Escolher arquivo:
   - `Servidor de dados > Compras > 2 Público > 9 Bionexo > template pedido de compra`
6. Anexar e enviar
7. Após processamento, clicar em **Carrinho**
8. Preencher informações da cotação:
   - Data e hora de finalização
   - Demais dados solicitados
9. **Criar cotação**

---

## Gerenciamento de Riscos

| Risco | Mitigação |
|-------|----------|
| Divergência no item e quantidade solicitada | **VERIFICAR O CÓDIGO PAI COM A QUANTIDADE ANTES DE SUBIR PARA O BIONEXO** |

---

## Recomendações

- Executar esse processo **assim que** for feita a Demanda de Compra no Sistema Hospitalar
- Realizar após reunião de definição de datas das rotas

---

## Locais de Armazenamento

| Tipo | Caminho |
|------|--------|
| Pedidos de Compra | `Servidor de dados > Compras > 2 Público > 3 Pedido de Compra Medicamentos > Histórico de Pedidos > [Ano] > [Mês]` |
| Template Bionexo | `Servidor de dados > Compras > 2 Público > 9 Bionexo` |
| ROP Original | Setor da Garantia da Qualidade (Coordenação do SAD) |

---

*Última revisão: 12/2024 (Revisão 03)*
