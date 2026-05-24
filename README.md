# Conversor de Pedido Cantu

Ferramenta web para conversão de pedidos Excel para o formato CSV de importação do ERP Cantu.

## Como usar

1. Acesse o site
2. Faça upload do arquivo Excel (.xlsx) com o pedido
3. Revise os itens na tabela (edite quantidades ou valores se necessário)
4. Clique em **Baixar CSV** para exportar no formato do ERP

## Colunas aceitas no Excel

| Campo | Nomes aceitos |
|---|---|
| CNPJ do cliente | CNPJ, CNPJCLIENTE |
| CNPJ do fornecedor | CNPJFORNECEDOR, CNPJFORN, CANTUCNPJ |
| Código do produto | CODIGOINTERNOFORN, CODIGO, CODPRODUTO |
| Descrição | DESCRICAOPRODUTO, PRODUTO, DESCRICAO |
| Quantidade | QTDSOLICITADA, QUANTIDADE, QTD |
| Valor total | VALTOTLIQUIDO, VALORTOTAL, TOTAL, VALOR |
| Valor unitário | VALUNITARIO, VALORUNITARIO, VLUNITARIO, PRECO |
| Embalagem | EMBALAGEMENTRADA, EMBALAGEM, TIPOEMBALAGEM |
| Múltiplo | QTDSOLICITADAEMBALAGEM, MULTIPLO, QTDEMBALAGEM |
