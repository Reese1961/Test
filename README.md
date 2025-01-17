package test;

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        // Declare and assign values to variables
        String name = "John Doe"; // String variable
        int age = 25; // Integer variable
        char theCharacter = 'A'; // Character variable
        double interestRate = 3.75; // Double variable

        // Display the value of each variable in the console
        System.out.println("Name: " + name);
        System.out.println("Age: " + age);
        System.out.println("Character: " + theCharacter);
        System.out.println("Interest Rate: " + interestRate);

        // Create a scanner object for user input
        Scanner scanner = new Scanner(System.in);

        // Retrieve a value from the user and store it in a variable named userInput
        System.out.print("Enter a value: ");
        String userInput = scanner.nextLine();
        System.out.println("User input: " + userInput);

        // Declare a String variable for theName with no initial value
        String theName;

        // Prompt the user to enter their name and assign that value to theName
        System.out.print("Enter your name: ");
        theName = scanner.nextLine();

        // Declare an integer variable called theAge and assign it a value retrieved from the user
        System.out.print("Enter your age: ");
        int theAge = scanner.nextInt();

        // Declare integer variables for blinks and minutes, and calculate blinksPerMinute
        int blinks = 200;
        int minutes = 7;
        double blinksPerMinute = (double) blinks / minutes; // Calculate blinks per minute

        // Display the calculated value of blinks per minute
        System.out.println("Blinks per minute: " + blinksPerMinute);

        // Declare a double variable for accountBalance and retrieve the value from the user
        System.out.print("Enter your account balance: ");
        double accountBalance = scanner.nextDouble();

        // Display account balance with only 2 decimal places in the console
        System.out.printf("Account balance: %.2f\n", accountBalance);

        // Close the scanner object to prevent resource leaks
        scanner.close();
