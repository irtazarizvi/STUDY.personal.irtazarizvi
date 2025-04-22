    using System;
    class Calculator
    {
        static void Main()
        {
            Console.WriteLine("CALCULATOR");
            Console.WriteLine("enter first number");
            float a=float.Parse(Console.ReadLine());
            Console.WriteLine("enter the given operator, +,-,*,/");
            char i=char.Parse(Console.ReadLine());
            Console.WriteLine("enter second number");
            float b=float.Parse(Console.ReadLine());
    
            if (i == '+')
                Console.WriteLine("a+b =" + (a + b));
            else if (i == '-')
    
                Console.WriteLine("a-b = " + (a - b));
            else if (i == '*')
                Console.WriteLine("axb=" + (a * b));
            else if (i == '/')
            {
                if (b != 0)
                    Console.WriteLine("a/b = " + (a / b));
                else
                    Console.WriteLine("undefined");
            }
            
    
            
        }
    
    }
