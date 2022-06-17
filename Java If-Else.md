
**Task**
**Given an integer, , perform the following conditional actions:**
**If  is odd, print Weird**
- If  is even and in the inclusive range of  to , print Not Weird
- If  is even and in the inclusive range of  to , print Weird
- If  is even and greater than , print Not Weird
- 
- **Complete the stub code provided in your editor to print whether or not  is weird.**


~~~
imort java.io.*;
import java.util.*;

public class Solution {

    public static void main(String[] args) {
        /* Enter your code here. Read input from STDIN. Print output to STDOUT. Your class should be named Solution. */
       Scanner myObj = new Scanner(System.in);  // Create a Scanner object
        int N= myObj.nextInt();
       if(N%2==1)
        {
            System.out.println("Weird");
        }
        else 
        {
            if(N>=2&&N<=5)
            {
               System.out.println("Not Weird") ;
            }
            else if (N>=6&&N<=20)
            {
                System.out.println("Weird"); 
            }
            else if(N>20)
            {
                System.out.println("Not Weird") ;
            }
        }



    }
}

~~~
