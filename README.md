# prime2
prime..
import java.util.Scanner;
public class Prime
{
    public static boolean pri(int num)
    {
        int cnt=1;
        for(int i=2;i<=num;i++)
        {
            if(num%i==0)
            {
                cnt++;
            }
        }
        if(cnt==2)
        {
            return true;
        }
        return false;
    }
    public static void main(String [] args)
    [
        Scanner sc=new Scanner(System.in);
        System.out.println("Enter a number:");
        int num=sc.nextInt();
        if(pri(num))
        {
            System.out.println(n+" is a prime number");
        }
        else
        {
            System.out.println(n+" is not a prime number");
        }
    ]
}
