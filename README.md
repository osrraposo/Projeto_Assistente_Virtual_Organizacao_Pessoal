# Assistente Virtual de Organização Pessoal

Protótipo em Python criado para explorar organização pessoal e integração com inteligência artificial em um notebook do Google Colab.

## Funcionalidades

O protótipo permite:

- cadastrar, visualizar, editar e excluir tarefas;
- cadastrar, visualizar, editar e excluir lembretes;
- cadastrar, visualizar, editar e excluir eventos;
- conversar com um assistente sobre organização pessoal e produtividade.

## Tecnologias

- Python
- Google Colab
- Google Generative AI
- Pandas

## Como executar

1. Abra o notebook no Google Colab.
2. Configure uma chave de API no gerenciador de segredos do Colab com o nome `SECRET_KEY`.
3. Execute as células na ordem apresentada.
4. Inicie o menu interativo do assistente.

> A chave de API não deve ser inserida diretamente no notebook nem enviada ao GitHub.

## Estrutura

- `Projeto_Assistente_Virtual_Organizacao_Pessoal.ipynb`: implementação e demonstração do protótipo.
- `README.md`: apresentação e instruções do projeto.

## Estado do projeto

Este é um projeto de estudo. Algumas funções ainda precisam de revisão e testes, e a persistência dos dados ocorre somente durante a execução do notebook.

## Melhorias planejadas

- corrigir e testar as operações de edição;
- separar as funções do menu interativo;
- validar datas e entradas do usuário;
- adicionar persistência em arquivo ou banco de dados;
- atualizar a integração com o modelo de IA;
- criar testes automatizados.

## Autor

Thiago Santos — [@osrraposo](https://github.com/osrraposo)
