# keerthi
import java.util.*;


public class Num {

	
	public static void main(String[] args) {

		Scanner s=new Scanner(System.in);
		int count=1;
		int no=1;
		for(int i=0;i<=5;i++)
	    {
	    	System.out.println("enter the no:");
		    int num=s.nextInt();
	    
	    if(num>=0)
	    {
	    	System.out.println("non-negative number");
	    	System.out.println(count);
	    	count++;
	    }
	    
	    
	    	else 
	    	{
	    		System.out.println("negative number");
		    	System.out.println(no);
		    	no++;
	    	}
	    }


	}

}
