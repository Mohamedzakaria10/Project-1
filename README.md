using System;
using System.Linq;
using System.Collections.Generic;

namespace project_1
{
    public static class Program 
    {         
        public static void Main()
        {
          int first,second,num,i,sum;
          Console.Write("Enter the first number");
          first = int.Parse(Console.ReadLine());
          Console.Write("Enter the second number");
          second = int.Parse(Console.ReadLine());
          for(num= first;num<=second;num++)
    {
    sum=0;
    for(i=2;i<=num/2;i++)
    {
     if(num%i==0)
     {
      sum++;
      break;
     }
    }
    if (sum ==0&& num!=1)
    Console.WriteLine("{0}",num);
   }
    Console.WriteLine("end");
    Console.ReadKey();
      
           
           
    
        }
    }
}
