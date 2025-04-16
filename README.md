# Socket API Test

[![Linguagem Java](https://img.shields.io/badge/Linguagem-Java-red)](https://www.java.com/)

## Descrição

Projeto desenvolvido em **Java** para estudo e testes práticos de APIs utilizando **sockets**. Este repositório tem como objetivo explorar a comunicação entre sistemas, com foco no entendimento de conceitos de redes e integração por meio de APIs.

## Funcionalidades

- Comunicação via sockets para troca de dados entre cliente e servidor.
- Implementação de APIs simples para simular cenários reais de integração.
- Estudo de conceitos fundamentais de redes, como conexões TCP/IP.

## Estrutura do Projeto

- **`src/`**: Contém os arquivos fonte do projeto.
- **`README.md`**: Documentação do projeto.

## Pré-requisitos

Certifique-se de ter os seguintes itens instalados em sua máquina:

- [Java JDK](https://www.oracle.com/java/technologies/javase-downloads.html) 8 ou superior
- Um editor de código ou IDE (como [IntelliJ IDEA](https://www.jetbrains.com/idea/) ou [Eclipse](https://www.eclipse.org/))
- [Git](https://git-scm.com/) para clonar o repositório

## Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/icrcode/socket-api-test.git
   cd socket-api-test
2. Compile o código:
   ```bash
    javac -d bin src/**/*.java
3. Execute o servidor:
   ```bash
   java -cp bin com.exemplo.SocketServer
4. Execute o cliente:
   ```bash
   java -cp bin com.exemplo.SocketClient
   
## Licença

Este projeto está licenciado sob a MIT License.
