# Vorium Shop

Bem-vindo(a) à Vorium Shop! Este é um projeto simples de comércio eletrônico em Python que permite cadastrar produtos, listar produtos, adicionar produtos ao carrinho, visualizar o carrinho, concluir o pedido e sair do sistema.

## Funcionalidades

O projeto Vorium Shop inclui as seguintes funcionalidades:

- Cadastro de produto: Você pode cadastrar produtos fornecendo o nome e o preço do produto.
- Listagem de produtos: Você pode listar os produtos cadastrados.
- Compra de produto: Você pode adicionar produtos ao carrinho fornecendo o ID do produto.
- Visualização do carrinho: Você pode visualizar os produtos em seu carrinho, juntamente com o preço total.
- Conclusão do pedido: Você pode concluir o pedido fornecendo suas informações de envio.
- Saída do sistema: Você pode sair do sistema e encerrar a sessão de compras.

## Começando

Para começar com o Vorium Shop, você precisará seguir estes passos:

1. Clonar este repositório para sua máquina local.
2. Certificar-se de que você tem o Python 3 instalado em seu sistema.
3. Abrir um terminal e navegar até o diretório do projeto.
4. Executar o arquivo main.py usando o seguinte comando: `python main.py`.
5. Seguir as instruções na tela para cadastrar produtos, adicionar produtos ao carrinho, concluir pedidos e sair do sistema.

## O programa utiliza as seguintes bibliotecas:
-tkinter e ttk: para construir a interface gráfica.
-PIL: para abrir e manipular imagens.
-tkscrolledframe: para criar uma área rolável dentro da janela.
-requests e json: para fazer a requisição HTTP e tratar a resposta JSON

##Interface Gráfica
A interface gráfica é construída usando a biblioteca tkinter. A janela principal tem o tamanho de 350x415 pixels e não pode ser redimensionada. Ela é composta por três frames:

-O frame superior contém o logo e o nome do dicionário.
-O frame do meio contém um campo de entrada para a palavra a ser pesquisada.
-O frame inferior contém a lista de significados retornados pela API.
