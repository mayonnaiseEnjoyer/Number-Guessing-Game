import java.util.Scanner;
import java.util.Random;

public class NumberGuessingGame {

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        Random random = new Random();
        
        int numberToGuess = random.nextInt(50) + 1;
        int numberOfTries = 5;

     
        System.out.println("Guess a number from 1-50");
        System.out.println("Number of Tries : " + numberOfTries);
        System.out.println("=========================================");
        
        
        while (numberOfTries > 0) {
            System.out.print("Enter your guess: ");
            int inputGuess = scanner.nextInt();
            
            System.out.println("=========================================");
            if (inputGuess < numberToGuess) {
                System.out.println("Your guess is too low.");
                numberOfTries--;
                System.out.println("Tries left : " + numberOfTries);
            }else if(inputGuess > numberToGuess){
                System.out.println("Your guess is too high.");
                numberOfTries--;
                System.out.println("Tries left : " + numberOfTries);
            }
                 
            else{
                System.out.println("=========================================");
                System.out.println("Congratulations!!!\n You guessed the correct number.");
                System.out.println("=========================================");
                break;
            }
        }
        if (numberOfTries == 0) {
            System.out.println("=========================================");
            System.out.println("GAME OVER:!!!");
            System.out.println("You ran out of tries.\nBetter luck next time.");
            System.out.println("=========================================");
        }
    }
}
