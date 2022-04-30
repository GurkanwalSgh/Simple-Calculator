# Simple-Calculator

import java.util.*;
public class menudriven
{
    public static void main()
    {
        int a,b,result,ch;
        Scanner sc = new Scanner(System.in);
        
        System.out.println("Menu Selection");
        System.out.println("Press 1. For addition");
        System.out.println("Press 2. For Subtraction");
        System.out.println("Press 3. For Multiplication");
        System.out.println("Press 4. For Division");
        System.out.print("Please enter your choice :");
        ch = sc.nextInt();
        
        if (ch==1)
        {
            System.out.print("Please enter your 1st Value :");
            a = sc.nextInt();
            System.out.print("Please enter your 2nd Value :");
            b = sc.nextInt();
            result=a+b;
            System.out.print("The Sum is :"+result);
        }
        else if (ch==2)
        {
            System.out.print("Please enter your 1st Value :");
            a = sc.nextInt();
            System.out.print("Please enter your 2nd Value :");
            b = sc.nextInt();
            result=a-b;
            System.out.print("The Difference is :"+result);
        }
        else if (ch==3)
        {   System.out.print("Please enter your 1st Value :");
            a = sc.nextInt();
            System.out.print("Please enter your 2nd Value :");
            b = sc.nextInt();
            result=a*b;
            System.out.print("The Product is :"+result);
        }
        else if (ch==4)
        {   System.out.print("Please enter your 1st Value :");
            a = sc.nextInt();
            System.out.print("Please enter your 2nd Value :");
            b = sc.nextInt();
            result=a/b;
            System.out.print("The Quotient is :"+result);
        }
        else 
        {
            System.out.print("Wrong Input");
        }
    
     }
    
        
}
