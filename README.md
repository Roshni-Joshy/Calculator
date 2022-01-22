// Calculator using switch case

class Calculator {
 public static void main(String args[]) {
int a=10,b=20;
int choice=3;
System.out.print("**** Menu ****\n 1.Add \n 2.Subtract \n 3. Multiply \n 4. Division \n 5. Remainder");
	switch(choice)
	{ case 1:
	int sum;
	sum=a+b;
	System.out.println("Sum:"+sum);
	break;
	case 2:
	int diff;
	diff=a-b;
	System.out.println("Difference:"+diff);
	break;
	case 3:
	int product;
	product=a*b;
	System.out.println("Product:"+product);
	break;
	case 4:
	int quotient;
	quotient=a/b;
	System.out.println("Quotient:"+quotient);
	break;
	case 5:
	int remainder;
	remainder=a%b;
	System.out.println("Remainder:"+remainder);
	break;
	default:
	System.out.println("invalid option entered");	
	}
  }
}

