# Cliente TCP Simples

Este código é um cliente TCP simples em Python que cria uma conexão com um servidor remoto utilizando o módulo `socket`. Ele permite ao usuário informar o **host (IP)** e a **porta** para conectar-se. Caso a conexão seja bem-sucedida, o cliente será desconectado com a função `shutdown()`. Caso contrário, ele exibirá uma mensagem de erro.

Este código foi criado como parte de uma aula do curso de **Segurança da Informação** da DIO (Digital Innovation One).

## Funcionamento

1. O código tenta criar um socket TCP.
2. O usuário fornece o **host** (endereço IP ou nome de domínio) e a **porta**.
3. O cliente tenta se conectar ao host e à porta especificados.
4. Se a conexão for bem-sucedida, uma mensagem de sucesso é exibida, e a conexão é fechada.
5. Caso haja falha na conexão, um erro será mostrado.

## Exemplo de Execução

```bash
Digite o HOST ou IP a ser conectado: example.com
Digite a PORTA a ser conectada: 80
Cliente TCP conectado com sucesso no HOST example.com - PORTA 80



Essa descrição inclui a funcionalidade do código e também credita o curso de **Segurança da Informação** da DIO.

