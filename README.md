- š Hi, Iām @anand12000
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on ...
- š« How to reach me ...

<!---
anand12000/anand12000 is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
package SimpleNumberPrograms;

import java.util.Scanner;

public class addTwoNumbers {

 private static Scanner sc;

 public static void main(String[] args) {
 int Number1, Number2, Sum;
 sc = new Scanner(System.in);
 
 System.out.println("\n Please Enter the First integer Value: ");
 Number1 = sc.nextInt();

 System.out.println("\n Please Enter the Second integer Value: ");
 Number2 = sc.nextInt();
 
 Sum = Number1 + Number2;
 System.out.println("\n Sum of the two integer values is = " + Sum);
 }
}
