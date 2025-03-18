# Gerenciador de Lista (Inserir, Apagar, Listar)

Este projeto é um **gerenciador de lista interativo** que permite ao usuário inserir, apagar e listar itens em uma lista, de forma simples e prática. O programa exibe um menu de opções e o usuário pode interagir para gerenciar os itens da lista conforme desejar.

## Objetivo

O objetivo deste exercício é criar um programa interativo onde o usuário pode:
- **Inserir** valores na lista.
- **Apagar** valores a partir do índice.
- **Listar** todos os valores da lista.

## Funcionalidades

O programa oferece três opções principais para o usuário:

1. **Inserir [i]**: Permite que o usuário insira um valor na lista.
2. **Apagar [a]**: Permite que o usuário apague um item da lista fornecendo o índice do item.
3. **Listar [l]**: Exibe todos os itens da lista, mostrando seus respectivos índices.

### Detalhamento das Opções:

- **Inserir [i]**: O programa solicita ao usuário um valor e adiciona esse valor ao final da lista.
- **Apagar [a]**: O usuário deve fornecer um índice. O programa tenta remover o item correspondente. Se o índice for inválido (não numérico ou fora do intervalo), o programa exibe uma mensagem de erro.
- **Listar [l]**: O programa exibe todos os itens da lista junto com seus índices. Se a lista estiver vazia, ele informa que não há nada para listar.

## Como Funciona

1. O programa inicia um loop contínuo que exibe um menu de opções.
2. O usuário pode escolher uma opção digitando:
   - **i** para inserir um valor.
   - **a** para apagar um valor.
   - **l** para listar os valores.
3. O programa executa a ação correspondente e aguarda a próxima entrada.
4. O loop só será interrompido se o programa for fechado ou interrompido manualmente.

## Estrutura do Código

- **Inserção de itens**: Usamos a função `append()` para adicionar novos itens à lista.
- **Remoção de itens**: Usamos a função `del` para remover um item da lista, com tratamento de exceções para garantir que o índice seja válido.
- **Listagem de itens**: O programa usa a função `enumerate()` para listar os itens junto aos seus índices.

## Exemplo de Execução

### Menu de Opções:

```
Selecione uma opção
[i]nserir [a]pagar [l]istar: i
Valor: Maçã

Selecione uma opção
[i]nserir [a]pagar [l]istar: i
Valor: Banana

Selecione uma opção
[i]nserir [a]pagar [l]istar: l
0 Maçã
1 Banana

Selecione uma opção
[i]nserir [a]pagar [l]istar: a
Escolha o índice para apagar: 0

Selecione uma opção
[i]nserir [a]pagar [l]istar: l
0 Banana
```

### Caso de Erro:

```
Selecione uma opção
[i]nserir [a]pagar [l]istar: a
Escolha o índice para apagar: 5
Índice não existe na lista
```

## Como Usar

1. Clone ou baixe este repositório.
2. Abra o arquivo Python no seu editor de código favorito.
3. Execute o programa.
4. Siga as instruções fornecidas no menu e interaja com o programa para inserir, apagar ou listar itens na lista.

## Requisitos

- Python 3.x
- Sistema operacional que suporte o comando `cls` (para limpar a tela no Windows).

## Contribuindo

Se você desejar contribuir para este exercício, pode adicionar mais funcionalidades, como:
- Adicionar validação para valores repetidos na lista.
- Implementar a persistência dos dados (salvar a lista em um arquivo para uso posterior).

Para contribuir:
1. Fork o repositório.
2. Crie uma nova branch.
3. Faça suas modificações.
4. Abra um **pull request** com suas alterações.

## Licença

Este projeto é de código aberto e pode ser modificado ou compartilhado conforme necessário.

---

Se tiver alguma dúvida ou sugestão, sinta-se à vontade para entrar em contato! 😄
