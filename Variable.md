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
## Instance Variable
1. Declared inside class and outside the methods
2. Used with object of class inside which they are declared
3. Copy of variables are made for each object
4. Syntax:
a. object.Variable
~~~
class InstanceExample
{
	// instance variable
	int x=50;
	double y;
	// single copy: for all objects
	static int n1=100;

	public static void main(String[] args) 
	{
		
		System.out.println("program started");
		// Create object 
		InstanceExample ob=new InstanceExample();
		InstanceExample ob1=new InstanceExample();
		ob1.x=40;
		ob.x=10;
		System.out.println("ob.x "+ob.x);
		System.out.println("ob1.x "+ob1.x);
		System.out.println(ob.y);
		System.out.println(ob1.y);
		System.out.println(InstanceExample.n1);
		System.out.println(n1);
	

	}

	boolean a=true;
}
~~~

// default values by data type ki default value ko le leta hai.

## Static variable
1. Static variable can never be local
2. If static variable is used in the same class in which class it is located, then static variable can be directly used.
3. 1. Variable with static keywords are static variable
2. Single copy is made for static variable and shared amongst objects
3. Used directly with className no object is required
4. Syntax
a. ClassName.VariableName

