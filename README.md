EXPLICAÇÃO DO FUNCIONAMENTO:
Esse código é um programa simples que calcula a área de um retângulo com base nas dimensões fornecidas pelo usuário via terminal.

FUNCIONAMENTO:
1. Importa a classe Scanner:
   // Permite ler dados digitados pelo usuário no terminal.

2. Cria a classe AppAreaRetanguloTerminal:
   // Contém o método main, ponto de entrada do programa.

3. Inicia o Scanner:
   Scanner scanner = new Scanner(System.in);
   // Isso prepara o programa para receber entrada do usuário.

4. Solicita a base do retângulo:
   System.out.print("Digite a base do retângulo: ");
   double base = scanner.nextDouble();
   // O usu´rio digita um número (ex: 5.0), que é armazenado na variável base.

5. Solicita a altura do retângulo:
   System.out.print("Digite a altura do retÂngulo: ");
   double altura = scanner.nextDouble();
   // O usuário digita outro número (ex: 3.0), armazenado em altura.

6. Calcula a área:
   double area = base * altura;
   // Usa a fórmula da área do retângulo: base x altura.

7. Exibe o resultado:
   System.out.println("A área do retângulo é de:" + area);
   // Mostra o valor calculado no terminal.

EXEMPLO DA EXECUÇÃO:
Digite a base do retângulo: 5
Digite a altura do retângulo: 3
A área do retângulo é de: 15.0
