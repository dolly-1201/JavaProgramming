# JavaProgramming
UserInputProgram

import java.util.Scanner;

public class Main {

	public static void main(String[] args) {
	int age;
	String name;
	Scanner scanner = new Scanner(System.in);
	
	System.out.println(" Enter your name: ");
	name = scanner.nextLine();
	
	System.out.println("Enter your age: ");
	age = scanner.nextInt();
	
	System.out.println("Your name is " + name);
	System.out.println("Your age is "+ age);
	
	scanner.close();
	}
}
