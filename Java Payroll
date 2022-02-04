import java.util.Scanner;
public class Payroll {

	public static void main(String[] args) {
		Scanner scan =  new Scanner(System.in);
		
		System.out.println("Input Employee Type A/B: ");
		char employee_type = scan.next().charAt(0);
		
		int sss = 200;
		int pagIbig = 300;
		int philHealth = 200;
		
		if (employee_type == 'A' || employee_type == 'a' ) {
			System.out.println("Input Work Hours: ");
			int hours_worked = scan.nextInt();
			double rate = 93.75;
			double gross_pay = hours_worked * rate;
			double tax = gross_pay * 0.1;
			int deductions = (int) (sss + pagIbig + philHealth + tax);
			double net_pay = gross_pay - deductions;
			System.out.println("Employee Type: " + employee_type );
			System.out.println("Work Hours: " + hours_worked );
			System.out.println("Net Pay: " +  net_pay);
		}
		else if (employee_type == 'B' || employee_type == 'b') {
			System.out.println("Input Work Hours: ");
			int hours_worked = scan.nextInt();
			double rate = 112.5;
			double gross_pay = hours_worked * rate;
			double tax = gross_pay * 0.1;
			int deductions = (int) (sss + pagIbig + philHealth + tax);
			double net_pay = gross_pay - deductions;
			System.out.println("Employee Type: " + employee_type );
			System.out.println("Work Hours: " + hours_worked );
			System.out.println("Net Pay: " +  net_pay);
		}
		else {
			System.out.println("Invalid Input!");
		}
	}
}
