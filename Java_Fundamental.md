# Java Fundamental
1. Java is a strongly typed object oriented programming language.
2.  When there is a class, creating instance is compulsory.
3.  int, class have some pre-defined meaning in Java
4. When saving a programm, class name of main method will be the file name
5. JVM constructs class
6. main method is the starting point of an application
7. JVM will execute the program
8. Object creation is known as "Instantiation".
# What is instance variable?
- Instance variables are directly declared inside a class.
- Instance variable memory is allocated on the heap area with object creation.
- Instance variable memory is de-allocated by the garbage collector when the object becomes referenceless.
- The scope of instance variables can be used anywhere within the class.
- Default values for instance variables will be initialized if not given. E.g. Default value of int, char, String
# What is local variable?
- Local variables are directly declared inside method/block/loop within a class
- Memory is allocated inside static area. Memory is de allocated when stackframe of that method/block/loop is cleared after completing its task.
- The scope of local variables are limited to method/block/loop when it is declared.
- There is no default value for local variable
  
~~~
/*
Difference between instance variable and local variable
*/
class Calc
{
    int num1; // num1 & num2 are instance variable; they are declared inside class
    int num2;
    
    void add()
    {
        num1=10;
        num2=20;
        int res=num1+num2; // res is a local variable
        System.out.println(res);
    }
}
//program will start to execute from main method
public class Launch2
{
  public static void main(String args[]) 
  {
    Calc c = new Calc();
    c.add(); // dot means go inside
  }
}
~~~
Memory of local variable will be deactivated once the activity is finished
