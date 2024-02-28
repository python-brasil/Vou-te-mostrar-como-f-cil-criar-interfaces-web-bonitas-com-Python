# Vou te mostrar como é fácil criar interfaces web bonitas com Python
Este projeto é uma aplicação web simples desenvolvida com Streamlit, uma biblioteca Python para criação de aplicativos web interativos de forma rápida e fácil.

A aplicação implementa operações básicas de CRUD (Create, Read, Update, Delete) para uma lista de produtos. Aqui está uma visão geral do projeto:

- Título da Página: A página é intitulada como "CRUD de Produtos".

- Barra Lateral de Seleção de Ações: O usuário pode selecionar entre duas opções: "Adicionar Produto" e "Listar Produtos".

- Base de Dados de Produtos Simulada: Um dicionário produtos é utilizado para simular uma base de dados de produtos. Ele contém informações básicas sobre os produtos, como ID, nome e preço.

- Função para Listar Produtos: A função listar_produto() é responsável por exibir a lista de produtos na página. Para cada produto, são exibidos o ID, o nome e o preço.

- Função para Adicionar Produtos: A função adicionar_produto() permite que o usuário adicione novos produtos à lista. Ele solicita ao usuário o nome e o preço do produto através de caixas de entrada de texto e número, respectivamente. Quando o usuário clica no botão "Adicionar", o novo produto é adicionado à lista de produtos simulada.

- Lógica para Opções Selecionadas: Dependendo da opção selecionada na barra lateral, a aplicação executa a função correspondente. Se o usuário selecionar "Adicionar Produto", a função adicionar_produto() é chamada para permitir a adição de um novo produto. Se "Listar Produtos" for selecionado, a função listar_produto() é chamada para exibir a lista de produtos existentes.

Este projeto é útil para aprender sobre a criação de aplicativos web simples com Streamlit e também para entender os conceitos básicos de CRUD em aplicações web.

## Rodando projeto

Clone o projeto

```bash
  git clone https://github.com/python-brasil/Vou-te-mostrar-como-f-cil-criar-interfaces-web-bonitas-com-Python.git
```
Recomandamos criar uma venv antes de instalar as dependências
```bash
  python -m venv venv
```
em Linux
```bash
  python3 -m venv venv
```
Instale as dependências

```bash
  pip install -r requirements.txt
```

em Linux

```bash
  pip3 install -r requirements.txt
```
Rode o projeto com

```bash
  streamlit run main.py
```
## Screenshot

![Vou te mostrar como é fácil criar um sistema  Web bonito com Python](https://github.com/python-brasil/Vou-te-mostrar-como-f-cil-criar-interfaces-web-bonitas-com-Python/assets/126124866/a6d24a1b-3d61-4994-889f-6bcbea25ea53)

## Infos de commits

- :package: novas funcionalidades
- :up: atualizações
- :ant: correções de bug
- :checkered_flag: release


## Nos acompanhe nas redes

- Instagram - [@python_brasil](https://www.instagram.com/python_brasil/)
- LinkedIn - [Comunidade Python Brasil](https://www.linkedin.com/company/comunidade-python-brasil)
- GitHub - [python-brasil](https://github.com/python-brasil)
- YouTube - [@Python_Brasil](https://www.youtube.com/@Python_Brasil)
- Pinterest - [Python Brasil](https://br.pinterest.com/pythonbrasil/)
- TikTok - [@python_brasil](https://www.tiktok.com/@python_brasil)

