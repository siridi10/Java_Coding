```java
import java.util.Scanner;

public class Main{
      public static void main(String[] args){
            int n;
            Scanner sc = new Scanner(System.in);
            System.out.print("Enter the number: ");
            n = sc.nextInt();
            for(int i = 1; i<=n; i++){
                  for(int j = 1; j<=i; j++){
                        if(j<i){
                              System.out.print(i+"*");
                              }
                              else{
                                    System.out.print(i);
                              }
                        }
                  System.out.println();
            }
            for(int i = n-1; i>=1; i--){
                  for(int j = 1; j<=i; j++){
                        if(j<i){
                              System.out.print(i+"*");
                              }
                              else{
                                    System.out.print(i);
                              }
                  }
                  System.out.println();
            }
      }
}

Output:-
------
Enter the number: 4
1
2*2
3*3*3
4*4*4*4
3*3*3
2*2
1
```
