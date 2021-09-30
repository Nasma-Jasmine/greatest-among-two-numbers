# greatest-among-two-numbers
import java.util.*;
class Greaterno
{
  public static void main(String args[])
  {
     int num1,num2;
     Scanner sc=new Scanner(System.in);
     System.out.println("Enter The Two Numbers:");
     num1=sc.nextInt();
     num2=sc.nextInt();
        if(num1>num2)
           {
              System.out.println("The First no Is Greater Than The Second No.");              
           }

        else if(num2>num1)
          {
             System.out.println("The Second No Is Greater Than The First No.");
          }

        else
         {
            System.out.println("Both are Equal.");
         }

 }

}
