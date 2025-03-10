## Literals
1. Representation of fixed values
a. Integer Literal
b. Floating Point lateral
c. Character Literal
d. String Literal
~~~
class LiteralExample
{
	public static void main(String[] args)
	{
		boolean result=false ;
		char ch='A';
		int i=100;
		String str="LCWD";
		System.out.println(ch);
		System.out.println(result);
		System.out.println(i);
		// integer literal
		byte n1=12;
		short n2=4444;
		int n3=35252;
		long n4=25252L;
		System.out.println(n1);
		System.out.println(n2);
		System.out.println(n3);
		System.out.println(n4);
	}
~~~
# In Java, you can represent the integer literal 26 in different number systems using the following formats:
~~~
// base 10
		int valueDec=26;

		// base 16
		// prefix--0x [Hex Decimal 0-9,A-F]
		// Representation in Hexadecimal
		int valueHex=0x1A;

		// base 2 // Representation in Binary
		// prefix-0b [Binary 0,1]
		int valueBin=0b11010;
		System.out.println(valueDec);
		System.out.println(valueHex);
		System.out.println(valueBin);
~~~
