# Hello_world
我的仓库
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace AL
{
    class Program
    {
        static void Main(string[] args)
        {
            while(true)
            {
                Console.ForegroundColor = ConsoleColor.Green;
                string i = Console.ReadLine();
                string j = i.Replace("吗","");
                j = j.Replace("?","!");
                j = j.Replace("我","你");
                Console.ForegroundColor = ConsoleColor.Cyan;
                Console.WriteLine(j);
            }
        }
    }
}
