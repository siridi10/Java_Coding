```java
import java.util.Scanner;

class HelloWorld {
    public static void main(String[] args) {
        int year;
        Scanner sc=new Scanner(System.in);
        System.out.println("Enter the year");
        year=sc.nextInt();
        System.out.println(year);
        if((year%4==0 && year%100!=0) ||(year%400==0)){
            System.out.println("Leapyear");
            
        }
        else{
            System.out.println("not a leap year");
        }
        
    }
}

Output:-
-------
Enter the year
2015
not a leap year
```
