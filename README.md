# Projeto de Programação orientada a objetos - POO

Projeto de conclusão do curso de Desenvolvimento Orientada a Objetos Utilizando a Linguagem Python

Este é um projeto simples que conta com a criação de três arquivos ".py": Main.py, Cliente.py e Conta.py. Os dois últimos contêm as infomações das classes e objetos. Bem como os métodos e funções aceitos para cada objeto.

O arquivo Main.py.: recupera os objetos das classes Cliente e Conta; inseri alguns dados para as classes segundo seus atributos, e; a partir dos métodos, retornar informações e realiza operações simpples de adição e subtração.

O projeto não conta com uma base de dados extensa, sendo somente para ilustração do modelo POO.

Em Main.py é necessário chamar os objetos pelas suas classes com os comandos:

``` from Cliente import Cliente```

```from Conta import Conta```
___
## Cliente.py
#### Atributos:
|Campo | Tipo de dado | Descrição |
|-- |-- |--|
|nome = n      | ```str```| nome completo do cliente.         |
|telefone = 0  | ```int```| telefone para contato do cliente. |

#### Métodos aceitos:
| Método | Utilização |
|--|--|
|```get_nome()```  | recupera o nome atual.|
|```set_nome(n)``` | altera o nome.        |  

## Conta.py
#### Atributos:
|Campo | Tipo de dado | Descrição |
|-- |-- |--|
|saldo = 0  | ```float``` | valor atual na conta.      |
|numero = 0 | ```int```   | numero da conta do cliente.|
|titular = t| ```str```   | igual ao nome do cliente.  |

#### Métodos aceitos:
| Método | Utilização |
|--|--|
|```saque(valor)```    | subtrai do saldo atual da Conta o ```valor``` solicitado.   |
|```deposita(valor)``` | adiciona ao saldo atual da Conta o ```valor``` solicitado.  |
|```extrato()```       | retorna um texto que apresenta o nome do Cliente e o saldo. |
