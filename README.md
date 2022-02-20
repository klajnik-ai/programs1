public class Main {
 public static void main(String[] args) {
  for (int i = 1; i <= 4; i++) {
   for (int j = 1; j <= i; j++) {
    System.out.print(j+" ");
   }
   System.out.println("");
  }
 }
}

public class Pyramid02 {
 public static void main(String[] args) {
  for (int i = 1; i <= 4; i++) {
   for (int j = 1; j <= i; j++) {
    System.out.print(i+" ");
   }
   System.out.println("");
  }
 }
}


public class Main {
 public static void main(String[] args) {
  for (int i = 1; i <= 4; i++) {
   for (int j = 1; j <= i; j++) {
    System.out.print("* ");
   }
   System.out.println("");
  }
 }
}


public class Main {
 public static void main(String[] args) {
  for (int i = 1; i <= 4; i++) {
   for (int j = 4; j >= i; j--) {
    System.out.print("* ");
   }
   System.out.println("");
  }
 }
}

public class Main {
 public static void main(String[] args) {
  for (int i = 1; i <= 4; i++) {
   for (int j = 1; j <= 4; j++) {
    if(i<=j){
     System.out.print("* ");
    }else{
     System.out.print("  ");
    }
   }
   System.out.println("");
  }
 }
}





8
88
888
8888

8888
888
88
8

9999
 999
  99
   9

   9
  99
 999
9999



public class Main {
 public static void main(String[] args) {
  for (int i = 1; i <= 4; i++) {
   for (int j = 4; j >= 1; j--) {
    if(i>=j){
     System.out.print("* ");
    }else{
     System.out.print("  ");
    }
   }
   System.out.println("");
  }
 }
}






// prg to print table of any number
import java.util.Scanner;
public class Main {
 public static void main(String[] args) {
  Scanner sc = new Scanner(System.in);
  System.out.println("Enter any number");
  int num=sc.nextInt();
  for(int i=1;i<=10;i++){
   System.out.println(num+" * "+i+" = "+(num*i));
  }
 }
}



/*  prg. to check palindrome number  */
import java.util.Scanner;
public class PalindromeNumber {
 public static void main(String[] args) {
  Scanner sc = new Scanner(System.in);
  System.out.println("Enter any number");
  int num = sc.nextInt();
  int originalNum=num;
  int revNum=0;
  while(num>0){
   int d = num%10;
   revNum = revNum*10+d;
   num=num/10;
  }
  if(originalNum==revNum){
   System.out.println(originalNum+ " is a palindrome");
  }else{
   System.out.println(originalNum+ " is not a palindrome");
  }
 }
}




import java.util.Scanner;

public class Main
{
   public static void main(String[] args)
   {
      int num, i=2, count=0;
      Scanner s = new Scanner(System.in);
      
      System.out.print("Enter a Number: ");
      num = s.nextInt();
      
      while(i<num)
      {
         if(num%i == 0)
         {
            count++;
            break;
         }
         i++;
      }
      
      if(count==0)
         System.out.println("\n" +num+ " is a Prime Number.");
      else
         System.out.println("\n" +num+ " is not a Prime Number.");
   }
}



/*  prg. to do sum of the digits of any number  */
import java.util.Scanner;

public class SumDigits {

 public static void main(String[] args) {
  Scanner sc = new Scanner(System.in);
  System.out.println("Enter any number");
  int num = sc.nextInt();
  int s=0;
  while(num>0){
   int d = num%10;
   s = s+d;
   num=num/10;
  }
  System.out.println(s);
 }
}
