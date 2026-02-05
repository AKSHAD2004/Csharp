# Csharp
using System;

class Program
{
    static void Main()
    {
        int[] source = { 1, 2, 3, 4, 5 };
        int[] destination = new int[source.Length];

        for (int i = 0; i < source.Length; i++)
        {
            destination[i] = source[i];
        }

        Console.WriteLine("Copied array:");
        foreach (int item in destination)
        {
            Console.Write(item + " ");
        }
    }
}
