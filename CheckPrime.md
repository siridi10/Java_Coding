If the number is prime print the square of the number else print half of number.
```java
Sample Output
------------
1.Input : 17                        2.Input :                                   3.Input : 20
  Output : 289                        Output : 7.50                               Output : 10
  
  
  
Solution:-
----------

import java.util.Scanner;
public class Main
{
	public static void main(String[] args) {
	    int prime=0,i;
	    int num;
	    Scanner sc = new Scanner(System.in);
	    System.out.println("Enter Input : ");
	    num = sc.nextInt();
		for ( i=1;i<=num ;i++ ){
		    if (num%i ==0){
		        prime++;
		    } }
		    if(prime==2){
		        System.out.printf("%d%n",num*num);
		    }
		    else if (num%2==0){
		        System.out.print(num/2);
		    }
		    else{
		        float z=num;
		        System.out.print(z/2);
		    }
		
		```
		} 
	}


  
