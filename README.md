# fares-najeeb
Java developer programming


import java.util.*;
 
class LeapYear
{
    public static void main(String []s)
    {
        int year; // declare varibales
        Scanner sc=new Scanner (System.in);
         
        for(int i = 0 ; i <=5 ; i++)  
        {
        try
        {
             
            System.out.print("Enter year:");
            year=sc.nextInt();
             
            if((year%400==0)||(year%100!=0 && year%4==0))
                System.out.println(year+" is a Leap Year.");
            else
                System.out.println(year+" is not a Leap Year.");
        }
        catch (Exception Ex)
        {
            System.out.println("Oops ... : " + Ex.toString());
        }
      }   
    }
}

