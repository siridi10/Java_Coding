
```java
import java.util.Scanner;

public class Main
{
	public static void main(String[] args) {
	    char c;
	    Scanner sc= new Scanner(System.in);
	    System.out.print("Enter c : ");
	    c=sc.next().charAt(0);
	    if ((c >= 'a' && c <= 'z') || ( c >= 'A' && c <= 'Z')){
	        System.out.println("Yes " + c + " is Alphabet");
	    } else{
	        System.out.println("No " + c + " is not Alphabet");
	    }
	}
}

Output:-
-------
1.Enter c : 1
No 1 is not Alphabet

2.Enter c : A
Yes A is Alphabet
```
