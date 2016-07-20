# positive
import java.util.Scanner;

public class PosNeg{

	
	public static void main(String[] args) {
		Scanner scanner=new Scanner(System.in);
		int n=scanner.nextInt();
		if(n>0){
			System.out.println("Positive number");
		}
		else if(n<0)
		{
			System.out.println("Negative number");
		}
		
		
		scanner.close();
	}

}
