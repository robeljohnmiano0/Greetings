using System;
namespace ConsoleApp
{
    class miano {
    static void Main (string[] args){
        
        Console.Write("Enter Your Name : ");
        string name1 = Console.ReadLine();
        
        Console.Write("Enter the total number of your enrolled courses: ");
        double age2;
        age2  = Convert.ToInt32(Console.ReadLine());
        
        Console.Write("Enter the Price of your favorite book : ");
        double age;
        age = Convert.ToInt32(Console.ReadLine());

        Console.WriteLine("");
        Console.WriteLine();
        
        Console.WriteLine("Name :"+ name1);
        Console.WriteLine();
        
        Console.WriteLine("Number of your enrolled courses :"+ age2);
        Console.WriteLine();
        
        Console.WriteLine("Price of the book :"+ age);
        Console.WriteLine();
  
        Console.Write("\nPress any key to exit...");
        Console.ReadKey();
        }
    }
}
