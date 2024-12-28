# coding
import java.util.*;

public class ReverseWords {
    public static String reverseWords(String s) {
        // Trim leading/trailing spaces and split by one or more spaces
        String[] words = s.trim().split("\\s+");
        StringBuilder reversed = new StringBuilder();

        // Iterate from the last word to the first
        for (int i = words.length - 1; i >= 0; i--) {
            reversed.append(words[i]);
            if (i > 0) { // Add space between words, but not at the end
                reversed.append(" ");
            }
        }

        return reversed.toString();
    }

    public static void main(String[] args) {
        // Sample Input 1
        String input1 = "Welcome to Coding Ninjas";
        System.out.println("Reversed: " + reverseWords(input1)); // Output: Ninjas Coding to Welcome

        // Sample Input 2
        String input2 = "Always indent your code";
        System.out.println("Reversed: " + reverseWords(input2)); // Output: code your indent Always
    }
}
