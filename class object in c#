using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace classcsharp
{
    class student //class
    {
        string name;
        int rollno;
        int age;
        int standard;
        public void setstudent(string name,int rollno,int age,int standard) //function and method
        {
            this.name = name;
            this.rollno = rollno;
            this.age = age;
            this.standard = standard;

        }
        public void getstudent()
        {
            Console.WriteLine("enter your name {0}",this.name);
            Console.WriteLine("enter your roll no {0}", this.rollno);
            Console.WriteLine("enter your age {0}", this.age);
            Console.WriteLine("enter your standard {0}", this.standard);
        }
        static void Main(string[] args) // main function
        {
            Console.WriteLine("enter your name");
            string name = Console.ReadLine();
            Console.WriteLine("enter your roll.no");
            int roll = int.Parse(Console.ReadLine());
            Console.WriteLine("enter your age");
            int age = int.Parse(Console.ReadLine());
            Console.WriteLine("enter your standard");
            int standard = int.Parse(Console.ReadLine());
            student diksha = new student(); // diksha is a object
            diksha.setstudent(name,roll,age,standard); //call the method and function
            diksha.getstudent();
            Console.WriteLine("--------------");
            Console.WriteLine("enter your name");
            string name2 = Console.ReadLine();
            Console.WriteLine("enter your roll.no");
            int roll2 = int.Parse(Console.ReadLine());
            Console.WriteLine("enter your age");
            int age2 = int.Parse(Console.ReadLine());
            Console.WriteLine("enter your standard");
            int standard2 = int.Parse(Console.ReadLine());
            student dhruv =new student();  // dhruv is a object
            dhruv.setstudent(name, roll, age, standard);  // call the method and function
            dhruv.getstudent();

            Console.ReadLine();

        }
    }
}
