# reverese-input-strings
import java.util.Scanner;

public class Program
{
	public static void main(String[] args) {
		Scanner scanner = new Scanner(System.in);
		String text = scanner.nextLine();
		char[] arr = text.toCharArray();
		String m ="";
		// a for each loop used for reverse the given string.
		for(char x:arr){
        m=x+m;
		}
		System.out.println(m);
		
	}
}
# Create a program that takes the loan amount as input, calculates and outputs the remaining amount after 3 months. 
import java.util.Scanner;

public class Program
{
	public static void main(String[] args) {
		Scanner scanner = new Scanner(System.in);
		int amount = scanner.nextInt();
		//your code goes here
		double remaining=0;
		for(int i=0;i<3;i++){
		  remaining=amount-(0.1*amount);
			amount=(int)remaining;
			

		}
		System.out.println(amount);
		
	}
}
