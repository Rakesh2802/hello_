# hello_
Import java.util.Scanner;
Import java.lang.math.*;
 class solve 
{
public static result (double meatcost,int taxprice,int tipprice)
{
double tax= taxprice*meatcost/100;
double tip= tipprice*meatcost/100;
int total = meatcost+ tax+ tip;
System.out.println(total);
}
}
public class solution
{
public static void main(String args [])
{
Scanner s = new Scanner(System.in);
double meatcost = s.nextDouble();
int tipprice =s nextInt();
int taxprice =s.nextInt();
solve.result(meatcost,taxprice,tipprice);
}
}
