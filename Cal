import java.lang.*;
import java.util.*;
class Calculator
{
    public static void main(String args[])
    {
        Scanner sc=new Scanner(System.in);
        char op;
        int ans=0;
        int a,b;
        while(true)
        {  
            System.out.print("Enter the operator:");
            op=sc.next().trim().charAt(0);
            if(op=='+' || op=='-'||op=='*'||op=='/'|| op=='%')
            {
                System.out.print("Enter the values of a and b:");
                a=sc.nextInt();
                b=sc.nextInt();
                switch(op)
                {
                    case '+':
                    System.out.println("Result:"+(a+b));
                    break;

                    case '-':
                    System.out.println("Result:"+(a-b));
                    break;

                    case '*':
                    System.out.println("Result:"+(a*b));
                    break;

                    case '/':
                    System.out.println("Result:"+(a/b));
                    break;
                    
                    case  '%':
                    System.out.println("Result:"+(a%b));
                    break;

                    default:
                    System.out.println("Enter the valid intput");
                }

            }
        else{
            System.out.print("Thanks for Using");
            break;
        }
        }

    }

}
