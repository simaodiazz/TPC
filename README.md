```csharp
using System;

class Program
{
    static void Main(string[] args)
    {
        // Exercício 1: Conversão de int para double
        int a = 10;
        double c = (double)a;
        Console.WriteLine(c);

        // Exercício 2: Conversão de double para int
        double d = 5.9;
        int e = (int)d;
        Console.WriteLine(e);

        // Exercício 3: Conversão de bool para string
        bool verdadeiro = true;
        string resultado = verdadeiro.ToString();
        Console.WriteLine(resultado);

        // Exercício 4: Conversão de int para double
        int numeroInteiro = 10;
        double numeroDouble = (double)numeroInteiro;
        Console.WriteLine(numeroDouble);

        // Exercício 5: Conversão de int para string
        int numero = 15;
        string numeroString = numero.ToString();
        Console.WriteLine(numeroString);

        // Exercício 6: Conversão de double para int
        double valor = 3.14;
        int valorInteiro = (int)valor;
        Console.WriteLine(valorInteiro);

        // Exercício 7: Conversão de string para int
        Console.Write("Digite sua idade em anos: ");
        string idadeString = Console.ReadLine();
        int idadeAnos = int.Parse(idadeString);
        int idadeMeses = idadeAnos * 12;
        int idadeDias = idadeAnos * 365;
        Console.WriteLine($"Sua idade em meses é {idadeMeses} e em dias é {idadeDias}.");

        // Exercício 8: Conversão de string para float
        Console.Write("Digite o valor em dólares americanos: ");
        string valorDolarString = Console.ReadLine();
        float valorDolar = float.Parse(valorDolarString);
        float valorEuro = valorDolar * 1.22595f;
        Console.WriteLine($"O valor em euros é: {valorEuro}");

        // Exercício 9: Conversão de string para float
        Console.Write("Digite o preço base do produto: ");
        string precoBaseString = Console.ReadLine();
        float precoBase = float.Parse(precoBaseString);
        float precoFinal = precoBase * 1.23f;
        Console.WriteLine($"O preço de venda ao público é: {precoFinal}");

        // Exercício 10: Conversão de bool para string
        Console.Write("Digite o status de inscrição (true ou false): ");
        string statusString = Console.ReadLine();
        bool status = bool.Parse(statusString);
        string statusInscricao = status ? "Inscrito" : "Não inscrito";
        Console.WriteLine($"Status de inscrição: {statusInscricao}");

        // Exercício 11: Conversão de int para double
        Console.WriteLine("Digite as três notas inteiras:");
        int nota1 = int.Parse(Console.ReadLine());
        int nota2 = int.Parse(Console.ReadLine());
        int nota3 = int.Parse(Console.ReadLine());

        double media = (nota1 + nota2 + nota3) / 3.0;
        double mediaDouble = Convert.ToDouble(media);
        Console.WriteLine($"A média aritmética é: {mediaDouble}");

        // Exercício 12: Conversão de double para int
        Console.WriteLine("Digite uma média em double:");
        double mediaDouble2 = double.Parse(Console.ReadLine());
        int mediaInt = (int)Math.Floor(mediaDouble2);
        Console.WriteLine($"O valor arredondado para baixo é: {mediaInt}");

        // Exercício 13: Conversão de float para double
        Console.WriteLine("Digite uma temperatura em graus Celsius (float):");
        float temperaturaFloat = float.Parse(Console.ReadLine());
        double temperaturaDouble = Convert.ToDouble(temperaturaFloat);
        Console.WriteLine($"A temperatura em graus Celsius (double) é: {temperaturaDouble}");

        // Exercício 14: Conversão de double para float
        Console.WriteLine("Digite um peso em quilogramas (double):");
        double pesoDouble = double.Parse(Console.ReadLine());
        float pesoFloat = (float)pesoDouble;
        Console.WriteLine($"O peso em quilogramas (float) é: {pesoFloat}");

        // Exercício 15: Declaração de variável bool
        bool estaChovendo = true;
        Console.WriteLine(estaChovendo);

        // Exercício 16: Declaração de variável char
        char letra = 'A';
        Console.WriteLine(letra);

        // Exercício 17: Declaração de variável int e leitura do usuário
        Console.WriteLine("Digite uma idade:");
        int idade = int.Parse(Console.ReadLine());
        Console.WriteLine(idade);

        // Exercício 18: Declaração de variável float e leitura do usuário
        Console.WriteLine("Digite uma altura em metros:");
        float altura = float.Parse(Console.ReadLine());
        Console.WriteLine(altura);

        // Exercício 19: Cálculo da média ponderada
        Console.WriteLine("Digite as três notas e seus respectivos pesos:");
        double nota1Ponderada = double.Parse(Console.ReadLine());
        double peso1 = double.Parse(Console.ReadLine());
        double nota2Ponderada = double.Parse(Console.ReadLine());
        double peso2 = double.Parse(Console.ReadLine());
        double nota3Ponderada = double.Parse(Console.ReadLine());
        double peso3 = double.Parse(Console.ReadLine());

        double mediaPonderada = (nota1Ponderada * peso1 + nota2Ponderada * peso2 + nota3Ponderada * peso3) / (peso1 + peso2 + peso3);
        Console.WriteLine($"A média ponderada é: {mediaPonderada}");

        // Exercício 20: Declaração de constante int
        const int ANOS = 5;
        Console.WriteLine(ANOS);

        // Exercício 21: Declaração de constante float
        const float PI = 3.14159f;
        Console.WriteLine(PI);

        // Exercício 22: Conversão de Fahrenheit para Celsius
        const float fator = 5f / 9f;
        Console.Write("Digite a temperatura em graus Fahrenheit: ");
        float fahrenheit = float.Parse(Console.ReadLine());
        float celsius = fator * (fahrenheit - 32);
        Console.WriteLine($"A temperatura em graus Celsius é: {celsius}");

        // Exercício 23: Cálculo da área de um círculo
        const double PI2 = 3.14159;
        Console.Write("Digite o raio do círculo: ");
        double raio = double.Parse(Console.ReadLine());
        double area = PI2 * raio * raio;
        Console.WriteLine($"A área do círculo é: {area}");

        // Exercício 24: Expressão 3 + 4
        Console.WriteLine(3 + 4);

        // Exercício 25: Expressão 5 / 2
        Console.WriteLine(5 / 2); // Resultado: 2

        // Exercício 26: Resto da divisão de 40 por 3
        Console.WriteLine(40 % 3);

        // Exercício 27: Parte inteira de um número
        Console.Write("Digite um número: ");
        double numero = double.Parse(Console.ReadLine());
        int parteInteira = (int)numero;
        Console.WriteLine($"A parte inteira do número é: {parteInteira}");

        // Exercício 28: Verificação de número par ou ímpar
        Console.Write("Digite um número inteiro: ");
        int numeroVerificacao = int.Parse(Console.ReadLine());
        bool ehPar = numeroVerificacao % 2 == 0;
        Console.WriteLine($"O número é {(ehPar ? "par" : "ímpar")}");

        // Exercício 29: Média aritmética de três números inteiros
        Console.WriteLine("Digite três números inteiros:");
        int num1 = int.Parse(Console.ReadLine());
        int num2 = int.Parse(Console.ReadLine());
        int num3 = int.Parse(Console.ReadLine());
        double mediaAritmetica = (num1 + num2 + num3) / 3.0;
        Console.WriteLine($"A média aritmética é: {mediaAritmetica}");

        // Exercício 30: Média aritmética com divisão inteira e real
        Console.WriteLine("Digite duas notas inteiras e uma nota real:");
        int nota1 = int.Parse(Console.ReadLine());
        int nota2 = int.Parse(Console.ReadLine());
        float nota3 = float.Parse(Console.ReadLine());
        int somaNotasInt = nota1 + nota2;
        float mediaInt = somaNotasInt / 2;
        float mediaReal = (somaNotasInt + nota3) / 3;
        Console.WriteLine($"Média (divisão inteira): {mediaInt}");
        Console.WriteLine($"Média (divisão real): {mediaReal}");

        // Exercício 31: Conversão de metros para centímetros e quilômetros
        Console.Write("Digite um comprimento em metros: ");
        double metros = double.Parse(Console.ReadLine());
        double centimetros = metros * 100;
        double quilometros = metros / 1000;
        Console.WriteLine($"O comprimento em centímetros é: {centimetros}");
        Console.WriteLine($"O comprimento em quilômetros é: {quilometros}");

        // Exercício 32: Cálculo da hipotenusa de um triângulo retângulo
        Console.Write("Digite o valor do primeiro cateto: ");
        double c1 = double.Parse(Console.ReadLine());
        Console.Write("Digite o valor do segundo cateto: ");
        double c2 = double.Parse(Console.ReadLine());
        double hipotenusa = Math.Sqrt(c1 * c1 + c2 * c2);
        Console.WriteLine($"O valor da hipotenusa é: {hipotenusa}");

        // Exercício 33: Antecessor e sucessor de um número
        Console.Write("Digite um número: ");
        int numero = int.Parse(Console.ReadLine());
        int antecessor = numero - 1;
        int sucessor = numero + 1;
        Console.WriteLine($"Antecessor: {antecessor}");
        Console.WriteLine($"Sucessor: {sucessor}");

        // Exercício 34: Operações matemáticas com atribuição combinada
        Console.Write("Digite um número inteiro: ");
        int valor = int.Parse(Console.ReadLine());
        valor += 10;
        valor *= 2;
        valor -= 5;
        Console.WriteLine($"Resultado: {valor}");

        // Exercício 35: Troca de valores entre duas variáveis
        Console.Write("Digite o valor de a: ");
        int a = int.Parse(Console.ReadLine());
        Console.Write("Digite o valor de b: ");
        int b = int.Parse(Console.ReadLine());
        int temp = a;
        a = b;
        b = temp;
        Console.WriteLine($"Valor de a: {a}");
        Console.WriteLine($"Valor de b: {b}");

        // Exercício 36: Leitura e interpolação de strings
        Console.Write("Digite seu nome: ");
        string nome = Console.ReadLine();
        Console.Write("Digite sua idade: ");
        int idade = int.Parse(Console.ReadLine());
        Console.Write("Digite seu curso: ");
        string curso = Console.ReadLine();
        Console.WriteLine($"Nome: {nome}");
        Console.WriteLine($"Idade: {idade}");
        Console.WriteLine($"Curso: {curso}");

        // Exercício 37: Calculadora Simples
        Console.Write("Digite o primeiro número: ");
        int num1 = int.Parse(Console.ReadLine());
        Console.Write("Digite o segundo número: ");
        int num2 = int.Parse(Console.ReadLine());
        Console.Write("Escolha uma operação (+, -, *, /): ");
        char operacao = char.Parse(Console.ReadLine());
        double resultado = 0;
        switch (operacao)
        {
            case '+':
                resultado = num1 + num2;
                break;
            case '-':
                resultado = num1 - num2;
                break;
            case '*':
                resultado = num1 * num2;
                break;
            case '/':
                resultado = (double)num1 / num2;
                break;
            default:
                Console.WriteLine("Operação inválida!");
                break;
        }
        Console.WriteLine($"Resultado: {resultado}");

        // Exercício 38: Verificação do maior número
        Console.Write("Digite o primeiro número: ");
        int numero1 = int.Parse(Console.ReadLine());
        Console.Write("Digite o segundo número: ");
        int numero2 = int.Parse(Console.ReadLine());
        if (numero1 > numero2)
        {
            Console.WriteLine($"Maior número: {numero1}");
        }
        else if (numero2 > numero1)
        {
            Console.WriteLine($"Maior número: {numero2}");
        }
        else
        {
            Console.WriteLine("Os números são iguais.");
        }

        // Exercício 39: Verificação de número par ou ímpar usando operador ternário
        Console.Write("Digite um número inteiro: ");
        int numero3 = int.Parse(Console.ReadLine());
        string resultadoParImpar = numero3 % 2 == 0 ? "par" : "ímpar";
        Console.WriteLine($"O número é {resultadoParImpar}.");

        // Exercício 40: Verificação de número positivo, negativo ou zero
        Console.Write("Digite um número: ");
        int numero4 = int.Parse(Console.ReadLine());
        if (numero4 > 0)
        {
            Console.WriteLine("Número positivo.");
        }
        else if (numero4 < 0)
        {
            Console.WriteLine("Número negativo.");
        }
        else
        {
            Console.WriteLine("Número zero.");
        }

        // Exercício 41: Verificação de ano bissexto
        Console.Write("Digite um ano: ");
        int ano = int.Parse(Console.ReadLine());
        bool bissexto = (ano % 4 == 0 && ano % 100 != 0) || (ano % 400 == 0);
        if (bissexto)
        {
            Console.WriteLine($"{ano} é um ano bissexto.");
        }
        else
        {
            Console.WriteLine($"{ano} não é um ano bissexto.");
        }

        // Exercício 42: Verificação de vogal ou consoante
        Console.Write("Digite um caractere: ");
        char caractere = char.Parse(Console.ReadLine());
        bool vogal = "aeiouAEIOU".Contains(caractere);
        if (vogal)
        {
            Console.WriteLine($"{caractere} é uma vogal.");
        }
        else
        {
            Console.WriteLine($"{caractere} é uma consoante.");
        }

        // Exercício 43: Verificação do tipo de triângulo
        Console.Write("Digite o valor do lado 1: ");
        double lado1 = double.Parse(Console.ReadLine());
        Console.Write("Digite o valor do lado 2: ");
        double lado2 = double.Parse(Console.ReadLine());
        Console.Write("Digite o valor do lado 3: ");
        double lado3 = double.Parse(Console.ReadLine());
        if (lado1 == lado2 && lado1 == lado3)
        {
            Console.WriteLine("Triângulo equilátero.");
        }
        else if (lado1 == lado2 || lado1 == lado3 || lado2 == lado3)
        {
            Console.WriteLine("Triângulo isósceles.");
        }
        else
        {
            Console.WriteLine("Triângulo escaleno.");
        }

        // Exercício 44: Verificação de número primo
        Console.Write("Digite um número inteiro: ");
        int numero5 = int.Parse(Console.ReadLine());
        bool primo = true;
        if (numero5 <= 1)
        {
            primo = false;
        }
        else
        {
            for (int i = 2; i <= Math.Sqrt(numero5); i++)
            {
                if (numero5 % i == 0)
                {
                    primo = false;
                    break;
                }
            }
        }
        if (primo)
        {
            Console.WriteLine($"{numero5} é um número primo.");
        }
        else
        {
            Console.WriteLine($"{numero5} não é um número primo.");
        }

        // Exercício 45: Verificação de idade para votação
        Console.Write("Digite sua idade: ");
        int idade2 = int.Parse(Console.ReadLine());
        if (idade2 >= 18)
        {
            Console.WriteLine("Você pode votar.");
        }
        else
        {
            Console.WriteLine("Você não pode votar.");
        }

        // Exercício 46: Verificação do maior entre três números
        Console.Write("Digite o primeiro número: ");
        int num1_46 = int.Parse(Console.ReadLine());
        Console.Write("Digite o segundo número: ");
        int num2_46 = int.Parse(Console.ReadLine());
        Console.Write("Digite o terceiro número: ");
        int num3_46 = int.Parse(Console.ReadLine());
        int maior = num1_46;
        if (num2_46 > maior)
        {
            maior = num2_46;
        }
        if (num3_46 > maior)
        {
            maior = num3_46;
        }
        Console.WriteLine($"Maior número: {maior}");

        // Exercício 47: Verificação da categoria de acordo com a idade
        Console.Write("Digite sua idade: ");
        int idade3 = int.Parse(Console.ReadLine());
        if (idade3 >= 0 && idade3 <= 12)
        {
            Console.WriteLine("Categoria: Criança");
        }
        else if (idade3 >= 13 && idade3 <= 17)
        {
            Console.WriteLine("Categoria: Adolescente");
        }
        else if (idade3 >= 18 && idade3 <= 59)
        {
            Console.WriteLine("Categoria: Adulto");
        }
        else if (idade3 >= 60)
        {
            Console.WriteLine("Categoria: Idoso");
        }
        else
        {
            Console.WriteLine("Idade inválida.");
        }

        // Exercício 48: Classificação da nota de um aluno
        Console.Write("Digite a nota do aluno: ");
        int nota = int.Parse(Console.ReadLine());

        if (nota >= 0 && nota <= 19)
        {
            Console.WriteLine("Muito Insuficiente");
        }
        else if (nota >= 20 && nota <= 49)
        {
            Console.WriteLine("Insuficiente");
        }
        else if (nota >= 50 && nota <= 69)
        {
            Console.WriteLine("Suficiente");
        }
        else if (nota >= 70 && nota <= 89)
        {
            Console.WriteLine("Bom");
        }
        else if (nota >= 90 && nota <= 100)
        {
            Console.WriteLine("Muito Bom");
        }
        else
        {
            Console.WriteLine("Nota inválida");
        }

        // Exercício 49: Determinação do dia da semana
        Console.Write("Digite um número (0-6) para representar o dia da semana: ");
        int diaSemana = int.Parse(Console.ReadLine());

        switch (diaSemana)
        {
            case 0:
                Console.WriteLine("Domingo");
                break;
            case 1:
                Console.WriteLine("Segunda-feira");
                break;
            case 2:
                Console.WriteLine("Terça-feira");
                break;
            case 3:
                Console.WriteLine("Quarta-feira");
                break;
            case 4:
                Console.WriteLine("Quinta-feira");
                break;
            case 5:
                Console.WriteLine("Sexta-feira");
                break;
            case 6:
                Console.WriteLine("Sábado");
                break;
            default:
                Console.WriteLine("Número inválido");
                break;
        }

        // Exercício 50: Apresentação dos dias de um mês
        Console.Write("Digite o número do mês: ");
        int mes = int.Parse(Console.ReadLine());

        switch (mes)
        {
            case 1:
                Console.WriteLine("Janeiro - 31 dias");
                break;
            case 2:
                Console.WriteLine("Fevereiro - 28 ou 29 dias");
                break;
            case 3:
                Console.WriteLine("Março - 31 dias");
                break;
            case 4:
                Console.WriteLine("Abril - 30 dias");
                break;
            case 5:
                Console.WriteLine("Maio - 31 dias");
                break;
            case 6:
                Console.WriteLine("Junho - 30 dias");
                break;
            case 7:
                Console.WriteLine("Julho - 31 dias");
                break;
            case 8:
                Console.WriteLine("Agosto - 31 dias");
                break;
            case 9:
                Console.WriteLine("Setembro - 30 dias");
                break;
            case 10:
                Console.WriteLine("Outubro - 31 dias");
                break;
            case 11:
                Console.WriteLine("Novembro - 30 dias");
                break;
            case 12:
                Console.WriteLine("Dezembro - 31 dias");
                break;
            default:
                Console.WriteLine("Mês inválido");
                break;
        }

        // Exercício 51: Determinação da estação do ano
        Console.Write("Digite o número do mês: ");
        int mes2 = int.Parse(Console.ReadLine());

        switch (mes2)
        {
            case 1:
            case 2:
            case 3:
                Console.WriteLine("Estação: Verão");
                break;
            case 4:
            case 5:
            case 6:
                Console.WriteLine("Estação: Outono");
                break;
            case 7:
            case 8:
            case 9:
                Console.WriteLine("Estação: Inverno");
                break;
            case 10:
            case 11:
            case 12:
                Console.WriteLine("Estação: Primavera");
                break;
            default:
                Console.WriteLine("Mês inválido");
                break;
        }

        // Exercício 52: Operações lógicas
        Console.WriteLine(4 == 5);
        Console.WriteLine(4 != 6);
        Console.WriteLine(4 > 5);
        Console.WriteLine(true == false);
        Console.WriteLine('a' == 'a');
        Console.WriteLine('a' == 'b');
        Console.WriteLine(2 < 3 && 3 > 4);
        Console.WriteLine(2 < 3 || 3 > 4);
        Console.WriteLine(!(2 < 3 || 3 > 4));

        // Exercício 53: Conversão de valor real para inteiro por arredondamento
        Console.Write("Digite um valor real positivo: ");
        double valorReal = double.Parse(Console.ReadLine());
        int valorInteiro = (int)Math.Round(valorReal);
        Console.WriteLine("Valor inteiro arredondado: " + valorInteiro);

        // Exercício 54: Cálculo do salário semanal
        Console.Write("Digite o número de horas trabalhadas: ");
        int horasTrabalhadas = int.Parse(Console.ReadLine());
        Console.Write("Digite o valor do salário por hora: ");
        double salarioPorHora = double.Parse(Console.ReadLine());

        double salarioSemanal;
        if (horasTrabalhadas <= 40)
        {
            salarioSemanal = horasTrabalhadas * salarioPorHora;
        }
        else
        {
            double horasExtras = horasTrabalhadas - 40;
            salarioSemanal = (40 * salarioPorHora) + (horasExtras * salarioPorHora * 2);
        }

        Console.WriteLine("Salário semanal a pagar: " + salarioSemanal);

        // Exercício 55: Ordenação de três números
        Console.Write("Digite o primeiro número: ");
        int numero1 = int.Parse(Console.ReadLine());
        Console.Write("Digite o segundo número: ");
        int numero2 = int.Parse(Console.ReadLine());
        Console.Write("Digite o terceiro número: ");
        int numero3 = int.Parse(Console.ReadLine());

        if (numero1 <= numero2 && numero1 <= numero3)
        {
            Console.Write(numero1 + " ");
            if (numero2 <= numero3)
            {
                Console.WriteLine(numero2 + " " + numero3);
            }
            else
            {
                Console.WriteLine(numero3 + " " + numero2);
            }
        }
        else if (numero2 <= numero1 && numero2 <= numero3)
        {
            Console.Write(numero2 + " ");
            if (numero1 <= numero3)
            {
                Console.WriteLine(numero1 + " " + numero3);
            }
            else
            {
                Console.WriteLine(numero3 + " " + numero1);
            }
        }
        else
        {
            Console.Write(numero3 + " ");
            if (numero1 <= numero2)
            {
                Console.WriteLine(numero1 + " " + numero2);
            }
            else
            {
                Console.WriteLine(numero2 + " " + numero1);
            }
        }

        // Exercício 56: Determinação do símbolo do zodíaco
        Console.Write("Digite o dia do seu nascimento: ");
        int dia = int.Parse(Console.ReadLine());
        Console.Write("Digite o mês do seu nascimento: ");
        int mes = int.Parse(Console.ReadLine());

        string simboloZodiaco = "";

        if ((mes == 1 && dia >= 20) || (mes == 2 && dia <= 18))
        {
            simboloZodiaco = "Aquário";
        }
        else if ((mes == 2 && dia >= 19) || (mes == 3 && dia <= 20))
        {
            simboloZodiaco = "Peixes";
        }
        else if ((mes == 3 && dia >= 21) || (mes == 4 && dia <= 19))
        {
            simboloZodiaco = "Áries";
        }
        else if ((mes == 4 && dia >= 20) || (mes == 5 && dia <= 20))
        {
            simboloZodiaco = "Touro";
        }
        else if ((mes == 5 && dia >= 21) || (mes == 6 && dia <= 20))
        {
            simboloZodiaco = "Gêmeos";
        }
        else if ((mes == 6 && dia >= 21) || (mes == 7 && dia <= 22))
        {
            simboloZodiaco = "Câncer";
        }
        else if ((mes == 7 && dia >= 23) || (mes == 8 && dia <= 22))
        {
            simboloZodiaco = "Leão";
        }
        else if ((mes == 8 && dia >= 23) || (mes == 9 && dia <= 22))
        {
            simboloZodiaco = "Virgem";
        }
        else if ((mes == 9 && dia >= 23) || (mes == 10 && dia <= 22))
        {
            simboloZodiaco = "Libra";
        }
        else if ((mes == 10 && dia >= 23) || (mes == 11 && dia <= 21))
        {
            simboloZodiaco = "Escorpião";
        }
        else if ((mes == 11 && dia >= 22) || (mes == 12 && dia <= 21))
        {
            simboloZodiaco = "Sagitário";
        }
        else if ((mes == 12 && dia >= 22) || (mes == 1 && dia <= 19))
        {
            simboloZodiaco = "Capricórnio";
        }

        Console.WriteLine("Seu símbolo do zodíaco é: " + simboloZodiaco);

        // Exercício 57: Primeiros dez números inteiros positivos
        int contador = 1;
        while (contador <= 10)
        {
            Console.WriteLine(contador);
            contador++;
        }

        // Exercício 58: Primeiros 50 números inteiros positivos
        contador = 1;
        while (contador <= 50)
        {
            Console.WriteLine(contador);
            contador++;
        }

        // Exercício 59: Tabuada do 5
        int numero = 5;
        contador = 1;
        while (contador <= 10)
        {
            Console.WriteLine(numero + " x " + contador + " = " + (numero * contador));
            contador++;
        }

        // Exercício 60: Tabuada de um número digitado pelo usuário
        Console.Write("Digite um número para a tabuada: ");
        numero = int.Parse(Console.ReadLine());
        contador = 1;
        while (contador <= 10)
        {
            Console.WriteLine(numero + " x " + contador + " = " + (numero * contador));
            contador++;
        }

        // Exercício 61: Verificação de número primo
        Console.Write("Digite um número: ");
        int numeroPrimo = int.Parse(Console.ReadLine());

        bool ehPrimo = true;
        if (numeroPrimo <= 1)
        {
            ehPrimo = false;
        }
        else
        {
            for (int i = 2; i <= Math.Sqrt(numeroPrimo); i++)
            {
                if (numeroPrimo % i == 0)
                {
                    ehPrimo = false;
                    break;
                }
            }
        }

        if (ehPrimo)
        {
            Console.WriteLine("O número é primo.");
        }
        else
        {
            Console.WriteLine("O número não é primo.");
        }

        // Exercício 62: Primeiros 50 números inteiros positivos com while
        contador = 1;
        while (contador <= 50)
        {
            Console.WriteLine(contador);
            contador++;
        }

        // 63. Contar números introduzidos pelo utilizador
        int contadorNumeros = 0;
        int numero;
        List<int> numerosIntroduzidos = new List<int>();

        do
        {
            Console.Write("Introduza um número (0 para sair): ");
            numero = int.Parse(Console.ReadLine());

            if (numero != 0)
            {
                contadorNumeros++;
                numerosIntroduzidos.Add(numero);
            }
        } while (numero != 0);

        Console.WriteLine($"Foram introduzidos {contadorNumeros} números.");

        // 64. Calcular a média dos números introduzidos pelo utilizador
        if (numerosIntroduzidos.Count > 0)
        {
            double soma = 0;

            foreach (int num in numerosIntroduzidos)
            {
                soma += num;
            }

            double media = soma / numerosIntroduzidos.Count;
            Console.WriteLine($"A média dos números introduzidos é: {media}");
        }
        else
        {
            Console.WriteLine("Nenhum número foi introduzido.");
        }

        // 65. Jogo de adivinhar número gerado pelo computador
        Random random = new Random();
        int numeroAleatorio = random.Next(1, 101);
        int tentativas = 0;
        int palpite;

        Console.WriteLine("Adivinhe o número gerado pelo computador (entre 1 e 100):");

        do
        {
            Console.Write("Insira o seu palpite: ");
            palpite = int.Parse(Console.ReadLine());
            tentativas++;

            if (palpite < numeroAleatorio)
            {
                Console.WriteLine("O número é maior.");
            }
            else if (palpite > numeroAleatorio)
            {
                Console.WriteLine("O número é menor.");
            }
            else
            {
                Console.WriteLine($"Parabéns! Adivinhou o número em {tentativas} tentativas.");
            }
        } while (palpite != numeroAleatorio);

        // 66. Soma com incrementos de 3 usando diferentes ciclos de repetição
        int somaFor = 0;
        int somaWhile = 0;
        int somaDoWhile = 0;

        for (int i = 4; i < 100; i += 3)
        {
            somaFor += i;
        }

        int j = 4;
        while (j < 100)
        {
            somaWhile += j;
            j += 3;
        }

        int k = 4;
        do
        {
            somaDoWhile += k;
            k += 3;
        } while (k < 100);

        Console.WriteLine($"Soma com incrementos de 3 (for): {somaFor}");
        Console.WriteLine($"Soma com incrementos de 3 (while): {somaWhile}");
        Console.WriteLine($"Soma com incrementos de 3 (do...while): {somaDoWhile}");

        // 67. Calcular potência sem usar Pow
        Console.Write("Introduza a base: ");
        int baseNum = int.Parse(Console.ReadLine());

        Console.Write("Introduza o expoente: ");
        int expoente = int.Parse(Console.ReadLine());

        int resultadoPotencia = 1;

        for (int i = 1; i <= expoente; i++)
        {
            resultadoPotencia *= baseNum;
        }

        Console.WriteLine($"O resultado de {baseNum} elevado a {expoente} é: {resultadoPotencia}");

        // 68. Estatísticas de altura dos alunos
        Console.Write("Introduza o número de alunos: ");
        int numeroAlunos = int.Parse(Console.ReadLine());

        double alturaMaisBaixa = double.MaxValue;
        double alturaMaisAlta = double.MinValue;
        double somaAlturas = 0;

        for (int i = 1; i <= numeroAlunos; i++)
        {
            Console.Write($"Introduza a altura do aluno {i}: ");
            double altura = double.Parse(Console.ReadLine());

            if (altura < alturaMaisBaixa)
            {
                alturaMaisBaixa = altura;
            }

            if (altura > alturaMaisAlta)
            {
                alturaMaisAlta = altura;
            }

            somaAlturas += altura;
        }

        double mediaAlturas = somaAlturas / numeroAlunos;

        Console.WriteLine($"Altura do aluno mais baixo: {alturaMaisBaixa}");
        Console.WriteLine($"Altura do aluno mais alto: {alturaMaisAlta}");
        Console.WriteLine($"Soma das alturas: {somaAlturas}");
        Console.WriteLine($"Média das alturas: {mediaAlturas}");

        // 69. Conversão decimal para binário
        Console.Write("Introduza um número decimal: ");
        int numeroDecimal = int.Parse(Console.ReadLine());

        string numeroBinario = "";
        while (numeroDecimal > 0)
        {
            int resto = numeroDecimal % 2;
            numeroBinario = resto.ToString() + numeroBinario;
            numeroDecimal = numeroDecimal / 2;
        }

        Console.WriteLine($"Número binário correspondente: {numeroBinario}");

        // 70. Conversão binário para inteiro
        Console.Write("Introduza um número binário: ");
        string numeroBinarioStr = Console.ReadLine();

        int numeroInteiro = 0;
        int potencia = 0;
        for (int i = numeroBinarioStr.Length - 1; i >= 0; i--)
        {
            int digito = int.Parse(numeroBinarioStr[i].ToString());
            numeroInteiro += digito * (int)Math.Pow(2, potencia);
            potencia++;
        }

        Console.WriteLine($"Número inteiro correspondente: {numeroInteiro}");

        // 71. Total a pagar no parque de diversões
        int totalPagar = 0;

        Console.Write("Quantidade de bilhetes para crianças até aos 4 anos: ");
        int bilhetesCrianca = int.Parse(Console.ReadLine());

        Console.Write("Quantidade de bilhetes para crianças dos 6 aos 12 anos: ");
        int bilhetesCrianca6_12 = int.Parse(Console.ReadLine());

        Console.Write("Quantidade de bilhetes para jovens dos 12 aos 17 anos: ");
        int bilhetesJovem12_17 = int.Parse(Console.ReadLine());

        Console.Write("Quantidade de bilhetes para adultos: ");
        int bilhetesAdulto = int.Parse(Console.ReadLine());

        totalPagar += bilhetesCrianca6_12 * 6;
        totalPagar += bilhetesJovem12_17 * 12;
        totalPagar += bilhetesAdulto * 18;

        Console.WriteLine($"Total a pagar: {totalPagar} euros");

        // 72. Verificar validade de um NIF
        Console.Write("Introduza o NIF: ");
        string nif = Console.ReadLine();

        bool nifValido = false;

        if (nif.Length == 9)
        {
            int[] pesos = { 9, 8, 7, 6, 5, 4, 3, 2, 1 };

            int soma = 0;

            for (int i = 0; i < 9; i++)
            {
                int digito = int.Parse(nif[i].ToString());
                soma += digito * pesos[i];
            }

            int resto = soma % 11;
            int digitoVerificador = 11 - resto;

            if (digitoVerificador >= 10)
            {
                digitoVerificador = 0;
            }

            int ultimoDigito = int.Parse(nif[8].ToString());

            nifValido = digitoVerificador == ultimoDigito;
        }

        if (nifValido)
        {
            Console.WriteLine("NIF válido.");
        }
        else
        {
            Console.WriteLine("NIF inválido.");
        }
    }
}

```