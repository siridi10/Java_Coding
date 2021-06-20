```java
import java.util.Scanner;

public class Main {
   public static void main(String args[]){
       long num;
       long count=0;
       Scanner sc = new Scanner(System.in);
       System.out.println("Enter the  number ::");
       num = sc.nextLong();
       while(num!=0){
           num=num/10;
           ++count;
       }
       System.out.println(count);
   }
}

Output:-
------
Enter the  number ::
2321232145669874565
19
```
