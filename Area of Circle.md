Input should be in integer and output should be floating with 2 precision.

```java
import java.util.Scanner;

public class Main
{
	public static void main(String[] args) {
	    int diameter;
	    Scanner sc= new Scanner(System.in);
	    System.out.print("Enter diameter :");
	    diameter=sc.nextInt();
	    float r=diameter/2;
	    float pi=3.14f;
		float area= (pi)*(r*r);
		System.out.println(r);
		System.out.printf("%.2f",area);
	}
}


Output:-
-------
Enter diameter :10
5.0
78.50
```
