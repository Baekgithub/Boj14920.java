# Boj14920.java
import java.util.*;
import java.io.*;

public class Main{
    public static void main(String[] args){
        Scanner sc = new Scanner(System.in);
        int num = sc.nextInt();
        int c = 0;
        while(true)
        {
            if(num == 1)
               break;
            if(num%2 == 0)
            {
               num = num/2;
               c++;
             }
             else if(num%2 != 0)
             {
                num = num*3 +1;
                c++;
              }         }
         sc.close();
         System.out.print(c+1;)
         }
}
