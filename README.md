# It is a Calculator using methods .
import java.util.Scanner; 
public class A
  { 
  public static void main(String[] args)
  {  
  Scanner input = new Scanner(System.in); 
  int a,b; 
  System.out.println("Enter the numbers");
  a = input.nextLine();  
  b = input.nextLine();
    int add=additionSimple(a,b); 
    int sub=substractionSimple(a,b);
    int mul=multiplicationSimple(a,b); 
    double div= divisionSimple(a,b);
    int rem= remainderSimple(a,b); 
    double sqr=squareRootSimple(a); 
    System.out.println(add+ “ “+sub+” “ + mul+” “ + div+ “ “+rem+” “+ sqr); 
    } 
    public static int additionSimple( int a, int b)
    {  
    return (a+b);  
    } 
    public static int substractionSimple(int a, int b) {  return (a-b);   
    }
    public static int multiplicationSimple(int a, int b)
    { 
    return (a*b); 
    }
    public static double divisionSimple(int a, int b)
    { 
    return (a/b); 
    } 
    public static int remainderSimple(int a, int b)
    {
    return (a%b);    
    } 
    public static double squareRootSimple(int a)
  {
  return (Math.sqrt(a));
  }
  }

