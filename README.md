# programm4.java
programm4.java
public class Launch 
{

	public static void main(String[] args) 
	{
		int root=0;
		int [] a = {1,2,3,4,5,6,7,8,9};
		int [] b = {1,2,8,9,12,46,76,82,15,20,30};
		for(int i=0; i<=a.length-1; ++i)
		{
			for(int j=0; j<=b.length-1; ++j)
			{
				if(b[j]%a[i]==0)
				{
					++root;
					
				}
				
			}
	
			System.out.println(a[i]+":"+root);
			root=0;
	    }
		
	}

}
