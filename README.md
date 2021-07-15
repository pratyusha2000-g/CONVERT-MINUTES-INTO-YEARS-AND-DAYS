# CONVERT-MINUTES-INTO-YEARS-AND-DAYS
import java.util.*;
public class Main
{
	public static void main(String[] args) 
	{
	    Scanner sc=new Scanner(System.in);
		System.out.println("Enter the number of minutes ");
        int min=sc.nextInt();
        int years=min/(365*24*60);
        int days=(min/(24*60))%365;
        System.out.println("Years =\t Days =" );
        System.out.println(years+"\t"+days);
	    
	}
}
