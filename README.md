import java.util.Scanner;

public class Solution {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("================================");
        for (int i = 0; i < 3; i++) {
            String s1 = sc.next();
            int x = sc.nextInt();
            // %-15s means left-justified within 15 characters
            // %03d means integer with leading zeroes, at least 3 digits
            System.out.printf("%-15s%03d%n", s1, x);
        }
        System.out.println("================================");
    }
}


