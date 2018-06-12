# Sample
import java.util.*;
public class Guess 
{
	public static void main(String[] args) 
	{
		int count=0;
		int n=0,temp=0;
		int a[]=new int[3];
		Scanner s=new Scanner(System.in);
		while(count<=3)
		{
			System.out.println("Enter your choice:");
			n=s.nextInt();
			if((n==1)||(n==2)||(n==3))
				{
					System.out.println("hit");
					temp=n;
					count++;
				}
			else
				{
					System.out.println("miss");
				}
		while(count>3)
		{
			if(n==temp)
				{
					System.out.println("kill");
					break;
				}
		}}
			
		System.out.println(count);
		//System.out.println("kill");
		}
	}

	


