# PraticaIfElse

Este projeto contém um programa simples em Java que demonstra a utilização de estruturas de controle **if-else**. O objetivo do código é tomar decisões com base no valor atual disponível, decidindo se é possível comprar um computador novo ou usado.

---

## Descrição do Código

O programa compara o valor atual disponível (`valorAtual`) com os preços de dois computadores:

- **pcNovo**: Preço de um computador novo (17.000).
- **pcUsado**: Preço de um computador usado (10.000).

### Lógica de Decisão:
1. Se o valor disponível (`valorAtual`) for maior ou igual ao preço de um computador novo (`pcNovo`), imprime:
   ```
   Comprarei um pc novo!!
   ```

2. Caso contrário, verifica se o valor disponível é menor ou igual ao preço de um computador usado (`pcUsado`) e imprime:
   ```
   Comprarei um pc usado!
   ```


## Como Executar

1. Certifique-se de ter o **JDK** instalado no seu sistema.
2. Salve o código em um arquivo chamado `PraticaIfElse.java`.
3. Compile o código usando o comando:
   ```
   javac PraticaIfElse.java
   ```
4. Execute o programa com:
   ```
   java PraticaIfElse
   ```

---

## Resultado Esperado

Dependendo do valor configurado para `valorAtual`, o programa exibirá:

- **Se `valorAtual >= 17000`**:
  ```
  Comprarei um pc novo!!
  ```

- **Se `valorAtual <= 10000`**:
  ```
  Comprarei um pc usado!
  ```

- **Se `valorAtual` estiver entre os dois valores**:
  Nenhuma mensagem será exibida.

---

