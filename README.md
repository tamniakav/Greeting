# Greeting
Just another repository
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Greeting
{
    class Greeting
    {
        static void Main(string[] args)
        {
            string firstName = Console.ReadLine();
            string lastName = Console.ReadLine();
            int ages = int.Parse(Console.ReadLine());

            Console.WriteLine($"Hello, {firstName} {lastName}. \r\nYou are {ages} years old.");
        }
    }
}
