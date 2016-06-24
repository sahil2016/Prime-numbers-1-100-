public class PrimeNumbers {

	/**
	 * @param args
	 */
	public static void main(String[] args) {
		// TODO Auto-generated method stub
		int p=1;
		for(int i=2;i<100;i++)
		{
			for(int div=2;div<i;div++)
			{
				if(i%div==0){
					p=0;
					break;
				}
				p=1;
			}
			if(p==1)
			{
				System.out.println(""+i);
			}
			
		}

	}

}
