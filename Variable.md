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
![image](https://github.com/user-attachments/assets/c0de481f-c9b4-4068-a88f-0c8a5399cede)
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
### Example to differentiate between static and instance variable
We assume in a school there are 20 students in a english class. A student feels thirsty during class and asks the classteacher from where he can drink water. Teacher tells him to drink water from the water storage tank. After few days, a new problem arised. Since all students started to dronk water from storage tank, it started to get empty within few time and students can not refill water anymore from water tank. Therefore, teachers urged all stuents to bring water bottels from home. In this example, water bottle of each individual student is instance variable, where one student's water bottle does not effect on other student's water bottle. On the other hand, water tank resembles static variable, because if water tank gets empty, it affects directly on other student's water bottle to refill. Summary, if static variable changes, it changes everywhere. While in case of instance variable, each object has  its own indidividual variable, which will not affect on other object's variable means if one student finishes his bottle of water, it does not have any effect on other students's bottle.
![image](https://github.com/user-attachments/assets/adaee2d9-a7b5-4fe9-ab8e-548ddf7f5c26)

