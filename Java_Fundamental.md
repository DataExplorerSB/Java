# What is instance variable?

 > Java is a strongly typed object oriented programming language
 When there is class, creating instance is compulsory.
When saving a programm, class name of main method will be the file name
JVM constructs class
int, class have some pre-defined meaning in Java
dot means go inside
main method is the starting point of an application
JVM will execute the program
Object creation is known as Instantiation
instance variable vs. local variable
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
    c.add();
  }
}
~~~
Memory of local variable will be deactivated once the activity is finished
