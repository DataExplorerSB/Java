# Variables
1. A variable is a container which holds the value while the Java program is
executed
2. Variable is a name of memory location
3. int x = 50

## Local Variables
1. Declared inside localscope
2. Inside method
3. Inside block like if,while,dowhile etc
4. It can not used outside that block scope
5. **Remember : Local variable can not work without initialisation**

~~~
class VariableTest
{
	public static void main(String args[])
	{
		System.out.println("This is variable test");
		int x=300;
		int y=60;
		int sum=x+y;
		System.out.println("value of x " + x);

		System.out.println("sum of "+x+" and "+y+" is "+sum);

		double l=330.56;
		String name="dugesh";
		System.out.println(l);
		System.out.println(name);



	}
}
~~~
## Static variable
1. Static variable can never be local

