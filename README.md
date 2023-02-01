 package java_project;

	import java.util.Scanner;

	class mathscalculator {

		public static void main(String[] args) {
			
				 
				int firstno = 0, secondno = 0, sum, subtraction, multiplication, division, modulus;
				
				Scanner in = new Scanner(System.in);
				
				System.out.print("Enter First Number -> ");
				firstno = in.nextInt();
				
				System.out.print("Enter Second Number -> ");
				secondno = in.nextInt();
				
				sum = firstno + secondno;
				subtraction = firstno - secondno;
				multiplication = firstno * secondno;
				division = firstno / secondno;
				modulus =  firstno % secondno;
				
				System.out.println("sum of Two No is ->  " + sum );
				System.out.println("subtraction of Two No is ->  " + subtraction );
				System.out.println("Multification of Two No is ->  " + multiplication );
				System.out.println("Division of Two No is ->  " + division );
				System.out.println("Modulus of Two No is ->  " + modulus );
			}

		}
