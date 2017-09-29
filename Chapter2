# Chapter-2
Programming Practices from Chapter 2
Copy and paste your code from these exercises into this file.

* 2.1
public class Integers
 {
     public static void main(String[] args)
     {
         int x, y, z;
         double Average;
         
         x = 4;
         y = 9;
         z = 12;
         Average = (double)(x+y+z)/3;
         
         System.out.println("Integers: " + x + 
                            ", " + y + ", " + z + "\n\n" +
                            "Average = " + Average);
     }// end method main
 }// end class Integers
 
* 2.2
 public class Doubles
 {
     public static void main(String[] args)
     {
         double x, y;
         double Sum, Product, Difference;
         
         x = 4;
         y = 9;
         
         Sum = x+y;
         Difference = x-y;
         Product = x*y;
         
         System.out.println("Numbers: " + x + ", " + y + "\n\n" 
                            "Sum = " + Sum);
     }// end method main
 }// end class Doubles

* 2.3
public class TempConverter
{
    // Converts from Fahrenheit to Celsius using C = (9/5)(F - 32).
    
    public static void main(String[] args)
    {
        final int BASE = 32;
        final double CONVERSION_FACTOR = 5.0/9.0;
        
        int fahrenheitTemp = 24; // value to convert
        double celsiusTemp;
        
        celsiusTemp = CONVERSION_FACTOR * (fahrenheitTemp - BASE);
        
        System.out.println ("Fahrenheit Temperature: " + fahrenheitTemp);
        System.out.println ("Celsius Equivalent: " + celsiusTemp);
        
    }// end method main
}// end class TempConverter

* 2.4
public class TimeConverter
{
    // Converts from hours minutes seconds to just seconds.
    
    public static void main(String[] args)
    {
        final int time = 60;
        
        int hours = 8;
        int minutes = 19;
        int seconds = 27;
        
        int secTime = hours*time^2 + minutes*time + seconds;
        
        System.out.println ("Time: " + hours + "h " + minutes + "m " +
                            seconds + "s\n");
        System.out.println ("Seconds Equivalent: " + secTime);
        
    }// end method main
}// end class TimeConverter

* 2.5
public class NameString 
{
    public static void main(String args[]) 
    {
        String firstName = new String ("Jonathan");
        String lastName = new String (" Chau");
        String mutation1, mutation2;
        
        mutation1 = firstName.concat (lastName);
        mutation2 = mutation1.toUpperCase();

        System.out.println ("First Name: " + firstName);
        System.out.println ("Last Name: " + lastName);
        System.out.println ("Full Name: " + mutation1);
        System.out.println ("First Name Length: " + firstName.length());
        System.out.println ("Last Name Length: " + lastName.length());
        System.out.println ("Full Name Length: " + mutation1.length());
        System.out.println ("All Caps: " + mutation2);

    }// end method main
}// end class NameString

* 2.6
public class LionKing 
{
    public static void main(String args[]) 
    {
        String phrase = new String ("HAKUNA MATATA IT MEANS"
                                    + " NO WORRIES") ;
        String mutation1, mutation2;
        
        mutation1 = phrase.substring (23, 33);
        mutation2 = phrase.replace("A", "4");

        System.out.println (phrase);
        System.out.println (mutation1);
        System.out.println (mutation2);

    }// end method main
}// end class LionKing

* 2.7
public class Distance 
 {
    public static void main(String args[]) 
    {
        double miles, kilometers;
        final double MIKM = 1.60935;
        miles = 2.7;
        kilometers = miles * MIKM;
        
        System.out.println ("Miles: " + miles + "mi");
        System.out.println ("Kilometers: " + kilometers + "km");
    }// end method main
}// end class Distance

* 2.8
import java.util.*; //Allows use of a Scanner

public class Slope 
{
    public static void main(String args[]) 
    {
        Scanner keyboard = new Scanner (System.in);
        int x1, x2;
        int y1, y2;
        double slope;
        
        System.out.print ("Enter the value of the first x: ");
        x1 = keyboard.nextInt();
        
        System.out.print ("Enter the value of the first y: ");
        y1 = keyboard.nextInt();
        
        System.out.println ("\nFirst position: (" 
                            + x1 + ", " + y1 + ")\n");
        
        System.out.print ("Enter the value of the second x: ");
        x2 = keyboard.nextInt();

        System.out.print ("Enter the value of the second y: ");
        y2 = keyboard.nextInt();
        
        System.out.println ("\nSecond position: (" 
                            + x2 + ", " + y2 + ")\n");
        
        slope = ((double)y2 - y1) / (x2 - x1);
        
        System.out.println ("The slope is " + slope);
        
    }//end method main
}//end class Slope

* 2.9
import java.util.Scanner;
import java.text.DecimalFormat;

public class SphereStats 
{
    public static void main(String args[]) 
    {
        int radius;
        double SA, volume;
        final double factor = 1.333333;
        Scanner scan = new Scanner(System.in);
        
        System.out.print ("Enter the radius: ");
        radius = scan.nextInt();
        
        SA = 4 * Math.PI * Math.pow(radius, 2);
        volume = factor * Math.PI * Math.pow(radius, 3);
        
        DecimalFormat fmt = new DecimalFormat ("0.####");
        
        System.out.println ("The sphere's surface area: " + fmt.format(SA));
        System.out.println ("The sphere's volume: " + fmt.format(volume));
    }// end method main
}// end class SphereStats

* 2.10
import java.util.Scanner;
import java.text.DecimalFormat;

public class Heron 
{
    public static void main(String args[]) 
    {
        int a, b, c;
        double s, area;
        Scanner scan = new Scanner(System.in);
        
        System.out.print ("Enter the first side's length: ");
        a = scan.nextInt();
        
        System.out.print ("Enter the second side's length: ");
        b = scan.nextInt();
        
        System.out.print ("Enter the third side's length: ");
        c = scan.nextInt();
        
        s = (a + b + c)/2;
        area = Math.sqrt(s*(s - a)*(s - b)*(s - c));

        DecimalFormat fmt = new DecimalFormat ("0.###");
        
        System.out.println ("The triangle's area: " + fmt.format(area));
    }// end method main
}// end class Heron

* Extra (If you did either one)
public class TimeConverter
{
    // Converts from seconds to hours minutes seconds.
    
    public static void main(String[] args)
    {
        final int TIME = 60;
      
        int secTime = 23790;

        int hours = secTime / (TIME*TIME);
        int minutes = secTime / (TIME) - (hours*TIME);
        int seconds = secTime - hours*TIME*TIME - minutes*TIME;
        
        System.out.println ("Seconds: " + secTime + "\n");
        System.out.println ("Time Equivalent: " + hours + "h " + 
                            minutes + "m " + seconds + "s");
        
    }// end method main
}// end class TimeConverter

* Extra 2
import java.util.*; //Allows use of a Scanner

public class Slope 
{
    public static void main(String args[]) 
    {
        Scanner keyboard = new Scanner (System.in);
        int x1, x2;
        int y1, y2;
        double slope;
        
        System.out.print ("Enter the value of the first x: ");
        x1 = keyboard.nextInt();
        
        System.out.print ("Enter the value of the first y: ");
        y1 = keyboard.nextInt();
        
        System.out.println ("\nFirst position: (" 
                            + x1 + ", " + y1 + ")\n");
        
        System.out.print ("Enter the value of the second x: ");
        x2 = keyboard.nextInt();

        System.out.print ("Enter the value of the second y: ");
        y2 = keyboard.nextInt();
        
        System.out.println ("\nSecond position: (" 
                            + x2 + ", " + y2 + ")\n");

        slope = ((double)y2 - y1) / (x2 - x1);
        
        System.out.println ("The slope is " + slope);
        
    }//end method main
}//end class Slope

* Extra 3
import java.util.Scanner;
import java.text.NumberFormat;

public class Coins 
{
    public static void main(String args[]) 
    {
        int pennies, nickles, dimes, quarters;
        double pv, nv, dv, qv, total;
        Scanner scan = new Scanner(System.in);
        
        System.out.print ("Enter the amount of pennies: ");
        pennies = scan.nextInt();
        
        System.out.print ("Enter the amount of nickels: ");
        nickles = scan.nextInt();
        
        System.out.print ("Enter the amount of dimes: ");
        dimes = scan.nextInt();
        
        System.out.print ("Enter the amount of quarters: ");
        quarters = scan.nextInt();
        
        pv = pennies * .01;
        nv = nickles * .05;
        dv = dimes * .1;
        qv = quarters * .25;
        total = pv + nv + dv + qv;

        NumberFormat fmt = NumberFormat.getCurrencyInstance ();
        
        System.out.println ("Total: " + fmt.format(total));
    }// end method main
}// end class Coins
