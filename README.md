
public class testingNewTings {

	public static void main(String[] args) {
		
		int number = 9;
		int[] nums = new int[number+1];
		int len = nums.length;
		
		for (int i = 0; i <= number; i++)
		{
			nums[i]= i;
		}
		
		for (int k = 1; k <= number; k++)
		{
			for (int i = len; i >= 2; i--)
			{
				if(i > k)
				{
					System.out.print("  ");
				}
				else
				{
					System.out.print(nums[i]+" ");
				}
			}	
				
				
				for(int j = 1; j <= number; j++)
				{
					if (j > k)
					{
						System.out.print("  ");
					}
					
						else
						{
							System.out.print(nums[j]+" ");
						}
				}
					
			System.out.println();
		}
	}

}
