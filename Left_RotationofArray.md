```java
import java.util.Scanner;
class arrayreverse{
    public static void main(String args[]) {
        int a,n;
        Scanner sc=new Scanner(System.in);
        System.out.print("Enter the size of array");
        a=sc.nextInt();
        int [] arr=new int[a];
        System.out.println("Enter the elements");
        for(int i=0;i<a;i++){
            arr[i]=sc.nextInt();
        }
        System.out.println("Enter of bits to be reversed");
        n=sc.nextInt();
         //Rotate the given array by n times toward left  
         for(int i = 0; i < n; i++){  
            int j, first;  
            //Stores the first element of the array  
            first = arr[0];  
            for(j = 0; j < arr.length-1; j++){  
                //Shift element of array by one  
                arr[j] = arr[j+1];  
            }  
            //First element of array will be added to the end  
            arr[j] = first;  
        }    
        sc.close();
        System.out.println("Array after right rotation: ");    
        for(int i = 0; i< arr.length; i++){    
            System.out.print(arr[i] + " ");    
        }    
    }
}
```
