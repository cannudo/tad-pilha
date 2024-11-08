# Rodar o projeto com Maven

## Pré-requisitos

- Java JDK 8 ou superior instalado
- Apache Maven instalado

## Passos para Rodar

1. **Clone o repositório:**
    ```sh
    git clone https://github.com/cannudo/tad-pilha-rubro-negra.git
    cd pilha-rubro-negra
    ```

2. **Compile o projeto:**
    ```sh
    mvn clean install
    ```

3. **Execute os testes:**
    ```sh
    mvn test
    ```

4. **Execute a aplicação:**
    ```sh
    mvn exec:java -Dexec.mainClass="com.cannudo.Main"
    ```

## Estrutura do Projeto

- `src/main/java`: Código fonte principal
- `src/test/java`: Código fonte dos testes
- `pom.xml`: Arquivo de configuração do Maven