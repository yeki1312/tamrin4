# tamrin4using System;

class Program
{
    static void Main()
    {
        int evenCount = 0;
        int oddCount = 0;

        Console.WriteLine("لطفاً 10 عدد وارد کنید:");

        for (int i = 0; i < 10; i++)
        {
            Console.Write($"عدد {i + 1}: ");
            int number = Convert.ToInt32(Console.ReadLine());

            if (number % 2 == 0)
            {
                evenCount++;
            }
            else
            {
                oddCount++;
            }
        }

        Console.WriteLine($"تعداد اعداد زوج: {evenCount}");
        Console.WriteLine($"تعداد اعداد فرد: {oddCount}");
    }
}
