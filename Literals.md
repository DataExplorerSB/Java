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
# In Java, you can represent the integer literal 1001 in different number systems using the following formats:
~~~
Decimal (Base 10)
int decimal = 1001;
Hexadecimal (Base 16)
int hexadecimal = 0x3E9; // 1001 in hexadecimal
Binary (Base 2)
int binary = 0b1111101001; // 1001 in binary
/////////////////////////////////////////////
public class NumberFormats {
    public static void main(String[] args) {
        int decimal = 1001;
        int hexadecimal = 0x3E9;
        int binary = 0b1111101001;

        System.out.println("Decimal: " + decimal);
        System.out.println("Hexadecimal: " + hexadecimal);
        System.out.println("Binary: " + binary);
    }
}
~~~
