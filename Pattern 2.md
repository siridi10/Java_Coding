```java
import java.util.*;
public class Main{
    public static void main(String a[]){ 
        int i ,j;
        int n=5;
        int x,y;
        for(i=1;i<=n;i++){
            x=i;
            y=n-i+1;
            for(j=1;j<=n;j++){
                if(j%2==0){
                    System.out.print(" "+x);
            
                }else{
                    System.out.print(" "+y);
                }
                x=x+n;
                y=y+n;
            }
            System.out.println("\n");
        }
    }
}
output
---------
5 6 15 16 25

4 7 14 17 24

3 8 13 18 23

2 9 12 19 22

1 10 11 20 21
```
