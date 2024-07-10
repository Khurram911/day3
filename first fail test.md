using System;

class MainClass
{

    public static int TimeConvert(int num)
    {
        int hr = 0;
        int min = 0;
        if (num > 60)
        {
            min = num % 60;
            hr = num / 60;
        }
        else
        {
            hr = 0;
            min = num;
        }
        string Time = string.Format($"{hr}:{min}");
     
e        return Tim;

    }

    static void Main()
    {

        // keep this function call here
        Console.WriteLine(TimeConvert(Console.ReadLine()));

    }

}
