# Controle de Fluxo - Desafio: Contador
## Desafio de Projeto - Java Cloud Native (DIO/Bradesco)

Este repositório contém a solução para um dos desafios do curso **Java Cloud Native** oferecido pela **DIO** em parceria com o **Bradesco**.

## Descrição do Desafio

O objetivo do desafio é criar um programa em Java que solicite ao usuário dois valores inteiros e exiba uma contagem do menor até o maior valor. Caso o primeiro valor seja maior que o segundo, uma exceção personalizada deverá ser lançada.

## Estrutura do Código

O código está estruturado da seguinte forma:

- **Classe `Contador`**: Contém o método `main` para capturar os inputs do usuário e chamar o método `contar`.
- **Método `contar`**: Responsável pela lógica de contagem e pela validação dos parâmetros. Se o primeiro for maior que o segundo, uma exceção personalizada é lançada.
- **Exceção `ParametrosInvalidosException`**: Exceção customizada para tratar entradas inválidas.

## Exemplo de Uso

1. Execute o programa.
2. Digite o primeiro parâmetro (inteiro).
3. Digite o segundo parâmetro (inteiro).
4. O programa exibirá os números na contagem crescente.
5. Se o primeiro parâmetro for maior que o segundo, uma mensagem de erro será exibida.

### Exemplo de Entrada e Saída

**Entrada:**
```sh
Digite o primeiro parâmetro
12
Digite o segundo parâmetro
30
```

**Saída:**
```sh
Imprimindo o número 0
Imprimindo o número 1
Imprimindo o número 2
Imprimindo o número 3 
...
Imprimindo o número 18

```

Se a entrada fosse:
```sh
Digite o primeiro parâmetro
7
Digite o segundo parâmetro
3
```

**Saída:**
```sh
O segundo parâmetro deve ser maior que o primeiro
```


1. Certifique-se de ter o Java instalado em sua máquina.
2. Compile o código com:
   ```sh
   javac Contador.java
   ```
3. Execute o programa com:
   ```sh
   java Contador
   ```

## Melhorias Possíveis
- Tratar entradas inválidas (exemplo: entrada de letras ou valores negativos).
- Melhorar a formatação da saída para tornar a contagem mais legível.

## Autor

Desenvolvido como parte do curso **Java Cloud Native** pela **DIO** em parceria com o **Bradesco**.

---

Este repositório pode ser atualizado conforme avanço nos estudos. Fique à vontade para sugerir melhorias! 🚀

