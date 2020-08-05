# Guessing-Game
A guessing game where you choose from the numbers 1 to 20 and would display an answer if you choose right or wrong.

    import java.util.Scanner;
    public class GuessingGame {
      public static void main(String[] args){
      final int NUM = 12;
      int num;
      Scanner input = new Scanner(System.in);

      do {
        System.out.println("Enter a number between 1 and 20: ");
        num = input.nextInt();
      } while(num != NUM); { 
        System.out.println("Try again.");
      }

      System.out.println("You win.");
    }
    }
