## Entidades

- Produto ( ID do unico do produto, nome, tamanho, cor, quantidade em estoque, quantidade minima, preço, categoria).
- Estoque ( nível atual, limite mínimo de cada produto, histórico de movimentações (entrada e saída de produtos).
- Vendas (Atributos: ID da venda, produtos vendidos, quantidade, data da venda, lucro gerado).
- Financeiro (data, tipo de movimentação (entrada ou saída), produto, quantidade).
- Ordem de Compra ( ID da ordem, produto, quantidade solicitada, data de solicitação, status, fornecedor).
- Fornecedor ( ID do fornecedor, nome, informações de contato, prazos de entrega).
- Comprador ( ID do usuário, nome, e-mail (para envio de notificações) ).

# Use-Cases

1. Gerenciar Produtos - Adicionar novos produtos ao estoque, Editar informações de produtos existentes (nome, tamanho, cor, quantidade mínima, etc.), Excluir produtos.
2. Rastrear Movimentações de Estoque - Registrar movimentações de entrada e saída de produtos no estoque, Visualizar histórico de movimentações para cada produto.
3. Definir Quantidade Mínima de Estoque - Configurar limites mínimos para cada produto, Editar os limites mínimos conforme necessário.
4. Emitir Alertas de Estoque Baixo - Verificar automaticamente o nível de estoque e gerar alertas quando estiver abaixo do mínimo, Enviar alertas por e-mail e notificação no sistema.
5. Visualizar Histórico de Vendas - Consultar quantidades vendidas por período, Observar o lucro gerado por produto, Identificar produtos mais vendidos em diferentes períodos.
6. Analisar Tendências de Estoque e Vendas - Visualizar as tendências de vendas e estoque ao longo do tempo para auxiliar nas decisões de compra.
7. Gerenciar Ordens de Compra - Criar ordens de compra automaticamente com base nos níveis mínimos de estoque e tendências de vendas, Atualizar status de ordens de compra (por exemplo, em processamento, concluída).
8. Integrar com Fornecedores - Receber atualizações automáticas de prazos de entrega para novos pedidos de produtos diretamente dos fornecedores.
9. Notificar Usuários - Enviar notificações por e-mail e no sistema para alertas de estoque e atualizações de ordens de compra.