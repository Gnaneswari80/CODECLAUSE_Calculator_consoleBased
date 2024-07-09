package javaproject;
import java.util.*;

public class Calculator {

	public static void main(String[] args) {
		
    int opt;
    Scanner sc=new Scanner(System.in);
    Calculator c=new Calculator();
	while(true)
	{
		System.out.println("Choose option..");
		System.out.println("1.Addition  2.Subtraction");
		System.out.println("3.Multiplicaton  4.Division 5.Exit");
		opt=sc.nextInt();
		switch(opt)
		{
		case 1:c.add();break;
		case 2:c.sub();break;
		case 3:c.mult();break;
		case 4:c.div();break;
		case 5:System.exit(0);
		default:System.out.println("Inavlid option");
		
	     		
		}
		}
		
	}
	
	public void add()
	{
		int a,b;
		Scanner sc=new Scanner(System.in);
		System.out.println("Enter two numbers to add");
		a=sc.nextInt();
		b=sc.nextInt();
		System.out.println("Result= "+(a+b));
		
	}
	

	public void sub()
	{
		int a,b;
		Scanner sc=new Scanner(System.in);
		System.out.println("Enter two numbers to subtract");
		a=sc.nextInt();
		b=sc.nextInt();
		System.out.println("Result= "+(a-b));
		
	}
	
	public void mult()
	{
		int a,b;
		Scanner sc=new Scanner(System.in);
		System.out.println("Enter two numbers to multiply");
		a=sc.nextInt();
		b=sc.nextInt();
		System.out.println("Result= "+(a*b));
		
	}
	public void div()
	{
		int a,b;
		Scanner sc=new Scanner(System.in);
		System.out.println("Enter two numbers to Division");
		a=sc.nextInt();
		b=sc.nextInt();
		System.out.println("Result= "+(a/b));
		
	}
}
