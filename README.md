# Adding-Numbers-using-While-loop-in-JAVA
import java.util.Scanner;
public class Main
{
    public static void main(String arg[]){
        Scanner sc = new Scanner(System.in);
        int a = sc.nextInt();
        int sum=0, rem;
        while(a>0){
            rem = a%10;
            sum += rem;
            a /=10;
        }
         System.out.println(sum);
        
    }
}
