# java-teast-nihs
//j028
import java.util.Scanner;

public class JPD03 {

	public static void main(String[] args) {

		int[] scores = { 100, 100, 95, 95, 92, 91, 90, 100, 88, 88, 87, 87, 90, 91, 85, 80, 81, 82, 82, 89 };
		// To Do
		
		try {
			Scanner sc = new Scanner(System.in);
			// TO DO
			int search = sc.nextInt();
			int count = 0;
			for(int score:scores){
			  if (score == search){
			    count++;
			  }
			}
			System.out.print(count);
			
		} catch (Exception e) {
			System.out.print("error");
			return;
		}
	}
}
//j030
import java.util.Scanner;

public class JPD03 {

	public static void main(String[] args) {

		int[] scores = { 100, 100, 95, 95, 92, 91, 90, 100, 88, 88, 87, 87, 90, 91, 85, 80, 81, 82, 82, 89 };
		// To Do
		
		try {
			Scanner sc = new Scanner(System.in);
			// TO DO
			int search = sc.nextInt();
			int count = 0;
			for(int score:scores){
			  if (score == search){
			    count++;
			  }
			}
			System.out.print(count);
			
		} catch (Exception e) {
			System.out.print("error");
			return;
		}
	}
}
//j025
import java.util.Scanner;

public class JPD03 {

	public static void main(String[] args) {

		long[] n = new long[50];
		n[0] = 0;
		n[1] = 1;
		// TO DO
    for(int i=2;i<n.length;i++){
      n[i]=n[i-1]+n[i-2];
    }
		try {
			Scanner sc = new Scanner(System.in);
			// TO DO
      int index = sc.nextInt();
    System.out.printf("%d:%d",index+1,n[index]);
		} catch (Exception e) {
			System.out.print("error");
			return;
		}
	}
}
