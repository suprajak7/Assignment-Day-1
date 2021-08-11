# Assignment-Day-1

INTREPRETER                                                          
-Translates program one statement at a time.               
-Interpreters usually take less amount of time to analyze the source code. However, the overall execution time is comparatively slower than compilers.
-No Object Code is generated, hence are memory efficient.
-Programming languages like JavaScript, Python, Ruby use interpreters.

COMPILER :
-Scans the entire program and translates it as a whole into machine code.
-Compilers usually take a large amount of time to analyze the source code. However, the overall execution time is comparatively faster than interpreters.
-Generates Object Code which further requires linking, hence requires more memory.
-Programming languages like C, C++, Java use compilers

2.PROGRAM :

import java.util.Scanner;
class Main
{
      public static void main(String args[])
      {
          int roll;
          String name;
          float mark;
          Scanner sc=new Scanner(System.in);
          System.out.print("Enter Name: ");
          name=sc.nextLine();
          System.out.print("Enter Roll Number: ");
          roll=sc.nextInt();
          System.out.print("Enter mark: ");
          mark=sc.nextFloat();
          System.out.println("Name: "+name+"\nRoll Number:" + roll +"\nMark: "+mark);
      }
          
}

OUTPUT:
Enter Name: Supraja k
Enter Roll Number: 12
Enter mark: 90
Name: Supraja k
Roll Number:12
Mark: 90.0
