# JaggedArray
## AIM:
To write a C# program to create a sample CPU usage on a network with 4 nodes using a jagged array.
## ALGORITHM:
### Step1:
Start.
### Step2:
Create a jagged array of 4arrays.

int[][] array = new int[4][];

### Step3:
Give the sample CPU usage in the jagged array.

### Step4:
Print the sample CPU usage in the jagged array.

### Step5:
Stop.

## PROGRAM:
```
/*
NAME : Paarkavy B
REG.NO:212221230072
*/
```

```
using System;
namespace jaggedarray;

class HelloWorld
{ 
    static void Main(string[]args)
    {
        int[][] cpu = new int[4][];
        cpu[0] = new int[3];
        cpu[1] = new int[5];
        cpu[2] = new int[4];
        cpu[3] = new int[6];
        for(int i=0;i<4;i++)
        {
            for (int j = 0; j < cpu[i]. Length; j++)
            {
                cpu[i][j] = i * j + 70;
            }
        }
        for(int i=0;i<4;i++)
        {
            for(int j=0;j<cpu[i].Length;j++)
            {
                Console.WriteLine("CPU usage for node{0} is {1}%", i, cpu[i][j]);
            }
        }
    }
}
```

## OUTPUT:
![output](op1.png)

## RESULT:
Thus,C# program to create a sample CPU usage on a network with 4 nodes using a jagged array is executed successfully.
