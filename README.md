Projeto Gerenciamento de Eclusa

O Sistema de Gerenciamento de Eclusa é um sistema acadêmico desenvolvido em **Java** que simula o funcionamento de uma **eclusa**, 
permitindo o **cadastro, gerenciamento e controle de entrada/saída de embarcações**. O sistema segue o padrão **MVC (Model–View–Controller)** 
e utiliza uma **interface gráfica em Swing**.

##  Funcionalidades

* Cadastro de diferentes tipos de embarcações (balsa, cargueiro, petroleiro, navio turístico).
* Associação de capitão às embarcações.
* Simulação de entrada e saída das embarcações na eclusa.
* Validação de compatibilidade de tamanho/capacidade.
* Interface gráfica para interação do usuário.
* Tratamento de erros específicos (ex.: embarcação muito grande para a eclusa).

## Estrutura do Projeto

* **Model** → contém as classes principais do domínio (embarcações, capitão, eclusa, tamanhos).
* **Controller** → gerencia a lógica e conecta interface com as regras de negócio.
* **View** → telas gráficas (Swing) para cadastro, remoção e gerenciamento de embarcações.
* **Exception** → tratamento de erros específicos, como incompatibilidade de tamanho.

## Tecnologias

* **Java 17+**
* **Maven** para gerenciamento do projeto
* **Swing** para interface gráfica

## Estrutura de Pastas

```
src/
 └── main/java
      ├── model        # Classes do domínio
      ├── controller   # Regras de controle
      ├── view         # Telas da aplicação
      └── exception    # Exceções personalizadas

