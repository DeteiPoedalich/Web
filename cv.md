# My CV
## About me
My name is Alexander Sharoiko. Currently I am a student at the Belarusian-RussianUniversity. I always like to learn something new aboutthe IT. I dont have much experience in the IT field,but I`m trying my best to become a qualified programmer.
## Experience
### Skills
* C#, 1.5 years
* HTML, 2 weeks
### Code Examples
```
static int[,] input(int[,] array)
  {
    int[,] array1 = new int[5, 3];  
    Random random = new Random();  
    for (int i = 0; i < 5; i++)  
    {  
        for (int j = 0;j < 3;j++)  
        {  
            array[i,j] = random.Next(15);               
        }  
    }  
    return array1;  
}  
static void output(int[,]array)    
{  
    for (int i = 0; i < 5; i++)
    {
    for (int j = 0; j < 3; j++)
    {
    Console.Write(array[i, j] + " ");
    }
    Console.WriteLine();
    }
}
static int[,] Array(int[,] array)
{
    int max = 0;
    int n=0, m=0;
    for(int i = 0; i 5; i++) 
    {
        for (int j = 0; j < 3; j++)
        {
            if (max < array[i, j])
            {
                max = array[i, j];
                n = i; m=j; 
            }
        }
    }
    output1(n, m, max);
    return array;
}
static void output1(int n,int m,int max)
{
    Console.WriteLine("Максимальный элемент- " + max);
    Console.WriteLine("Номер строки- "+n);
    Console.WriteLine("Номер сторлбца- "+m);   
}   
static void Main(string[] args)
{
    int[,] array = new int[5, 3];
    input(array);
    output(array);
    Array(array);
}
```
### Job Experience
Project: My CV
## Languages
* English, Level B1
* Russian
## Contact Information
* Phone Number: +375445526040
* e-mail: himanru3@gmail.com
