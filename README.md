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
