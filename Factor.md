```java
import java.util.Scanner;

public class Factor {
   public static void main(String args[]){
       int num;
       Scanner sc = new Scanner(System.in);
       System.out.println("Enter the  number ::");
       num = sc.nextInt();
       for(int i=1;i<=num;i++){
           if(num%i==0){
               System.out.println("the factor of " + " " + num + " " +"is " + i);
           }
       }
   }
}

Output:-
-------
Enter the  number ::
15
the factor of  15 is 1
the factor of  15 is 3
the factor of  15 is 5
the factor of  15 is 15
```
