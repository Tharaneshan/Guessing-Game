# Guessing-Game
A guessing game where you choose from the numbers 1 to 20 and you keep on guessing until you get it right.

    import java.lang.Math;
    import java.util.Scanner;
    public class GuessingGame {
      public static void main(String[] args){
      final int NUM = (int)(20 * Math.random() + 1);
      int num;
      Scanner input = new Scanner(System.in);

      do {
        System.out.println("Enter a number between 1 and 20: ");
        num = input.nextInt();
      } while(num != NUM);

      System.out.println("You win.");
    }
    }
