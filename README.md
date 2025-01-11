# Fact-for-loop
import java.util.Scanner;
Public class Factorial {

Scanner sc = new Scanner(System.in);
System.out.println(&quot;Enter a number:&quot;);
int n= sc.nextInt();
int fact = 1;
for(int i=1;i&lt;=n;i++)
{
fact*=i;
}
System.out.println(&quot; The factorial of &quot; + n + &quot; is &quot; + fact);
}
}
OUTPUT:
Enter a number:
5
The factorial of 5 is 120
