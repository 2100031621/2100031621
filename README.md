package p3;
import java.lang.Math;
import java.util.Scanner;

public class po {

	int n;
	po(int x,int y)
	{
	
		Scanner sc=new Scanner(System.in);
		n=sc.nextInt();
		while(x<=n)
		{
			int ans=0;
			ans+=Math.pow(x, y);
			System.out.println(ans);
			x++;
			y++;
			if(ans>=n)
			{
				break;
			}
		}
	sc.close();
	}

}
package p3;

public class po1 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		po p=new po(1,2);
	}

}
