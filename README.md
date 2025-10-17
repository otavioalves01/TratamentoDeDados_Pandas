## Automação de Tratamento de Vendas em Python

Este projeto é um script em Python que lê, trata e transforma uma base de dados de vendas, exportando os resultados em CSV e Excel. Ele foi desenvolvido como forma de aprendizado em Python, manipulação de dados e boas práticas de programação, evoluindo de um código linha a linha para uma versão modular com funções.

## Funcionalidades

Ler arquivo CSV com dados de vendas.

Remover linhas duplicadas.

Tratar valores ausentes (substituindo por “Desconhecido” ou “Não informada”).

Criar coluna total_venda (quantidade × valor_unitário).

Gerar resumo de vendas por produto.

Exportar arquivos tratados em CSV e Excel.

## Estrutura do Código

leitura_arquivo(caminho_arquivo): lê o CSV e retorna o DataFrame.

remover_duplicadas(df): remove duplicatas.

tratar_dados_nulos(df): trata valores ausentes.

total_venda(df): cria a coluna total da venda.

resumo_produto(df): cria resumo por produto.

exportar_arquivos(df): exporta CSV e Excel.

main(): função principal que executa todo o fluxo.

## Tecnologias

Python

Pandas

Openpyxl

## Aprendizado

Este projeto demonstra a importância de:

Escrever código modular usando funções;

Tornar scripts mais legíveis e reutilizáveis;

Organizar o fluxo de execução com uma função main()
