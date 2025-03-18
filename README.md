using System;

internal class Program
{
    private static void Main()
    {
        // Solicita ao usuário para inserir um número inteiro
        Console.WriteLine("Digite um número inteiro:");
        int numero = Convert.ToInt32(Console.ReadLine());

        // Verifica se o número é par ou ímpar
        if (numero % 2 == 0)
        {
            // Caso o número seja par
            Console.WriteLine("O número é par:");
        }
        else
        {
            // Caso o número seja ímpar
            Console.WriteLine("O número é ímpar:");
        }
    }
}

        
