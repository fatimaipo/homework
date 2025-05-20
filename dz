дз за 11 марта
упражнение 1
using System;
class Program
{
    static void Main()
    {
        // "Ввод суммы вклада"
        Console.Write("Введите сумму вклада: ");
        decimal deposit = Convert.ToDecimal(Console.ReadLine());
        // Ввод количества месяцев
        Console.Write("Введите количество месяцев: ");
        int months = Convert.ToInt32(Console.ReadLine());

        // Процентная ставка
        decimal interestRate = 0.07m;

        // Вычисление конечной суммы вклада с учетом процентов
        for (int i = 0; i < months; i++)
        {
            deposit += deposit * interestRate;
        }

        // Вывод конечной суммы
        Console.WriteLine($"Конечная сумма вклада: {deposit:F2}");
    }
}
упражнение 2
csharp
using System;

class Program
{
    static void Main()
    {
        // Ввод суммы вклада
        Console.Write("Введите сумму вклада: ");
        decimal deposit = Convert.ToDecimal(Console.ReadLine());

        // Ввод количества месяцев
        Console.Write("Введите количество месяцев: ");
        int months = Convert.ToInt32(Console.ReadLine());

        // Процентная ставка
        decimal interestRate = 0.07m;

        // Инициализация счетчика месяцев
        int count = 0;

        // Вычисление конечной суммы вклада с учетом процентов
        while (count < months)
        {
            deposit += deposit * interestRate;
            count++;
        }
        // Вывод конечной суммы
        Console.WriteLine($"Конечная сумма вклада: {deposit:F2}");
    }



упражнение 3
using System;

class Program
{
    static void Main()
    {
        // Заголовок таблицы
        Console.WriteLine("Таблица умножения:");

        // Циклы для создания таблицы умножения
        for (int i = 1; i <= 10; i++)
        {
            for (int j = 1; j <= 10; j++)
            {
                // Вывод результата умножения
                Console.Write($"{i * j,4}"); // Форматирование для выравнивания
            }
            Console.WriteLine(); // Переход на новую строку после каждой строки таблицы
        }
    }



упражнение 4
using System;

class Program
{
    static void Main()
    {
        while (true) // Бесконечный цикл
        {
            // Ввод первого числа
            Console.Write("Введите первое число (от 0 до 10): ");
            decimal firstNumber = Convert.ToDecimal(Console.ReadLine());

            // Ввод второго числа
            Console.Write("Введите второе число (от 0 до 10): ");
            decimal secondNumber = Convert.ToDecimal(Console.ReadLine());

            // Проверка диапазона
            if (firstNumber >= 0 && firstNumber <= 10 && secondNumber >= 0 && secondNumber <= 10)
            {
                
                decimal result = firstNumber * secondNumber;
                Console.WriteLine($"Результат умножения: {result}");
                break; // 
            
            else
            {
             
                Console.WriteLine();
            }
        }
