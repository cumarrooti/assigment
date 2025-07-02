# assigment
import java.util.Scanner;

public class Bank {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        double balance = 0;
        int choice = 0;

        while (choice != 4) {
            System.out.println("1. Deposit");
            System.out.println("2. Withdraw");
            System.out.println("3. Check Balance");
            System.out.println("4. Exit");
            System.out.print("Choose: ");
            choice = input.nextInt();

            if (choice == 1) {
                System.out.print("Amount: ");
                double amount = input.nextDouble();
                balance = balance + amount;
            } else if (choice == 2) {
                System.out.print("Amount: ");
                double amount = input.nextDouble();
                if (amount <= balance) {
                    balance = balance - amount;
                } else {
                    System.out.println("Not enough balance.");
                }
            } else if (choice == 3) {
                System.out.println("Balance: " + balance);
            }
        }
          Scanner input = new Scanner(System.in);
        double balance = 0;
        int choice = 0;

        while (choice != 4) {
            System.out.println("1. Deposit");
            System.out.println("2. Withdraw");
            System.out.println("3. Check Balance");
            System.out.println("4. Exit");
            System.out.print("Choose: ");
            choice = input.nextInt();

            if (choice == 1) {
                System.out.print("Amount: ");
                double amount = input.nextDouble();
                balance = balance + amount;
            } else if (choice == 2) {
                System.out.print("Amount: ");
                double amount = input.nextDouble();
                if (amount <= balance) {
                    balance = balance - amount;
                } else {
                    System.out.println("Not enough balance.");
                }
            } else if (choice == 3) {
                System.out.println("Balance: " + balance);
            }
        }
    Scanner input = new Scanner(System.in);
        double balance = 0;
        int choice = 0;

        while (choice != 4) {
            System.out.println("1. Deposit");
            System.out.println("2. Withdraw");
            System.out.println("3. Check Balance");
            System.out.println("4. Exit");
            System.out.print("Choose: ");
            choice = input.nextInt();

            if (choice == 1) {
                System.out.print("Amount: ");
                double amount = input.nextDouble();
                balance = balance + amount;
            } else if (choice == 2) {
                System.out.print("Amount: ");
                double amount = input.nextDouble();
                if (amount <= balance) {
                    balance = balance - amount;
                } else {
                    System.out.println("Not enough balance.");
                }
            } else if (choice == 3) {
                System.out.println("Balance: " + balance);
            }
        }
        System.out.print("Enter password: ");
        String pw = input.nextLine();

        boolean longEnough = pw.length() >= 8;
        boolean hasUpper = false;
        boolean hasLower = false;
        boolean hasDigit = false;
        boolean hasSymbol = false;

        for (int i = 0; i < pw.length(); i++) {
            char c = pw.charAt(i);
            if (c >= 'A' && c <= 'Z') hasUpper = true;
            else if (c >= 'a' && c <= 'z') hasLower = true;
            else if (c >= '0' && c <= '9') hasDigit = true;
            else hasSymbol = true;
        }

        if (longEnough && hasUpper && hasLower && hasDigit && hasSymbol) {
            System.out.println("Strong password.");
        } else {
            System.out.println("Weak password.");
        }
        System.out.print("Enter password: ");
        String pw = input.nextLine();

        boolean longEnough = pw.length() >= 8;
        boolean hasUpper = false;
        boolean hasLower = false;
        boolean hasDigit = false;
        boolean hasSymbol = false;

        for (int i = 0; i < pw.length(); i++) {
            char c = pw.charAt(i);
            if (c >= 'A' && c <= 'Z') hasUpper = true;
            else if (c >= 'a' && c <= 'z') hasLower = true;
            else if (c >= '0' && c <= '9') hasDigit = true;
            else hasSymbol = true;
        }

        if (longEnough && hasUpper && hasLower && hasDigit && hasSymbol) {
            System.out.println("Strong password.");
        } else {
            System.out.println("Weak password.");
        }
        System.out.print("Enter password: ");
        String pw = input.nextLine();

        boolean longEnough = pw.length() >= 8;
        boolean hasUpper = false;
        boolean hasLower = false;
        boolean hasDigit = false;
        boolean hasSymbol = false;

        for (int i = 0; i < pw.length(); i++) {
            char c = pw.charAt(i);
            if (c >= 'A' && c <= 'Z') hasUpper = true;
            else if (c >= 'a' && c <= 'z') hasLower = true;
            else if (c >= '0' && c <= '9') hasDigit = true;
            else hasSymbol = true;
        }

        if (longEnough && hasUpper && hasLower && hasDigit && hasSymbol) {
            System.out.println("Strong password.");
        } else {
            System.out.println("Weak password.");
        }
        System.out.print("Enter password: ");
        String pw = input.nextLine();

        boolean longEnough = pw.length() >= 8;
        boolean hasUpper = false;
        boolean hasLower = false;
        boolean hasDigit = false;
        boolean hasSymbol = false;

        for (int i = 0; i < pw.length(); i++) {
            char c = pw.charAt(i);
            if (c >= 'A' && c <= 'Z') hasUpper = true;
            else if (c >= 'a' && c <= 'z') hasLower = true;
            else if (c >= '0' && c <= '9') hasDigit = true;
            else hasSymbol = true;
        }

        if (longEnough && hasUpper && hasLower && hasDigit && hasSymbol) {
            System.out.println("Strong password.");
        } else {
            System.out.println("Weak password.");
        }
        System.out.print("Enter password: ");
        String pw = input.nextLine();

        boolean longEnough = pw.length() >= 8;
        boolean hasUpper = false;
        boolean hasLower = false;
        boolean hasDigit = false;
        boolean hasSymbol = false;

        for (int i = 0; i < pw.length(); i++) {
            char c = pw.charAt(i);
            if (c >= 'A' && c <= 'Z') hasUpper = true;
            else if (c >= 'a' && c <= 'z') hasLower = true;
            else if (c >= '0' && c <= '9') hasDigit = true;
            else hasSymbol = true;
        }

        if (longEnough && hasUpper && hasLower && hasDigit && hasSymbol) {
            System.out.println("Strong password.");
        } else {
            System.out.println("Weak password.");
        }
        System.out.print("Enter password: ");
        String pw = input.nextLine();

        boolean longEnough = pw.length() >= 8;
        boolean hasUpper = false;
        boolean hasLower = false;
        boolean hasDigit = false;
        boolean hasSymbol = false;

        for (int i = 0; i < pw.length(); i++) {
            char c = pw.charAt(i);
            if (c >= 'A' && c <= 'Z') hasUpper = true;
            else if (c >= 'a' && c <= 'z') hasLower = true;
            else if (c >= '0' && c <= '9') hasDigit = true;
            else hasSymbol = true;
        }

        if (longEnough && hasUpper && hasLower && hasDigit && hasSymbol) {
            System.out.println("Strong password.");
        } else {
            System.out.println("Weak password.");
        }
        System.out.print("Enter password: ");
        String pw = input.nextLine();

        boolean longEnough = pw.length() >= 8;
        boolean hasUpper = false;
        boolean hasLower = false;
        boolean hasDigit = false;
        boolean hasSymbol = false;

        for (int i = 0; i < pw.length(); i++) {
            char c = pw.charAt(i);
            if (c >= 'A' && c <= 'Z') hasUpper = true;
            else if (c >= 'a' && c <= 'z') hasLower = true;
            else if (c >= '0' && c <= '9') hasDigit = true;
            else hasSymbol = true;
        }

        if (longEnough && hasUpper && hasLower && hasDigit && hasSymbol) {
            System.out.println("Strong password.");
        } else {
            System.out.println("Weak password.");
        }
        System.out.print("Enter password: ");
        String pw = input.nextLine();

        boolean longEnough = pw.length() >= 8;
        boolean hasUpper = false;
        boolean hasLower = false;
        boolean hasDigit = false;
        boolean hasSymbol = false;

        for (int i = 0; i < pw.length(); i++) {
            char c = pw.charAt(i);
            if (c >= 'A' && c <= 'Z') hasUpper = true;
            else if (c >= 'a' && c <= 'z') hasLower = true;
            else if (c >= '0' && c <= '9') hasDigit = true;
            else hasSymbol = true;
        }

        if (longEnough && hasUpper && hasLower && hasDigit && hasSymbol) {
            System.out.println("Strong password.");
        } else {
            System.out.println("Weak password.");
        }
        System.out.print("Enter password: ");
        String pw = input.nextLine();

        boolean longEnough = pw.length() >= 8;
        boolean hasUpper = false;
        boolean hasLower = false;
        boolean hasDigit = false;
        boolean hasSymbol = false;

        for (int i = 0; i < pw.length(); i++) {
            char c = pw.charAt(i);
            if (c >= 'A' && c <= 'Z') hasUpper = true;
            else if (c >= 'a' && c <= 'z') hasLower = true;
            else if (c >= '0' && c <= '9') hasDigit = true;
            else hasSymbol = true;
        }

        if (longEnough && hasUpper && hasLower && hasDigit && hasSymbol) {
            System.out.println("Strong password.");
        } else {
            System.out.println("Weak password.");
        }
        System.out.print("Enter password: ");
        String pw = input.nextLine();

        boolean longEnough = pw.length() >= 8;
        boolean hasUpper = false;
        boolean hasLower = false;
        boolean hasDigit = false;
        boolean hasSymbol = false;

        for (int i = 0; i < pw.length(); i++) {
            char c = pw.charAt(i);
            if (c >= 'A' && c <= 'Z') hasUpper = true;
            else if (c >= 'a' && c <= 'z') hasLower = true;
            else if (c >= '0' && c <= '9') hasDigit = true;
            else hasSymbol = true;
        }

        if (longEnough && hasUpper && hasLower && hasDigit && hasSymbol) {
            System.out.println("Strong password.");
        } else {
            System.out.println("Weak password.");
        }
        System.out.print("Enter password: ");
        String pw = input.nextLine();

        boolean longEnough = pw.length() >= 8;
        boolean hasUpper = false;
        boolean hasLower = false;
        boolean hasDigit = false;
        boolean hasSymbol = false;

        for (int i = 0; i < pw.length(); i++) {
            char c = pw.charAt(i);
            if (c >= 'A' && c <= 'Z') hasUpper = true;
            else if (c >= 'a' && c <= 'z') hasLower = true;
            else if (c >= '0' && c <= '9') hasDigit = true;
            else hasSymbol = true;
        }

        if (longEnough && hasUpper && hasLower && hasDigit && hasSymbol) {
            System.out.println("Strong password.");
        } else {
            System.out.println("Weak password.");
        }
        System.out.print("Enter password: ");
        String pw = input.nextLine();

        boolean longEnough = pw.length() >= 8;
        boolean hasUpper = false;
        boolean hasLower = false;
        boolean hasDigit = false;
        boolean hasSymbol = false;

        for (int i = 0; i < pw.length(); i++) {
            char c = pw.charAt(i);
            if (c >= 'A' && c <= 'Z') hasUpper = true;
            else if (c >= 'a' && c <= 'z') hasLower = true;
            else if (c >= '0' && c <= '9') hasDigit = true;
            else hasSymbol = true;
        }

        if (longEnough && hasUpper && hasLower && hasDigit && hasSymbol) {
            System.out.println("Strong password.");
        } else {
            System.out.println("Weak password.");
        }
        System.out.print("Enter password: ");
        String pw = input.nextLine();

        boolean longEnough = pw.length() >= 8;
        boolean hasUpper = false;
        boolean hasLower = false;
        boolean hasDigit = false;
        boolean hasSymbol = false;

        for (int i = 0; i < pw.length(); i++) {
            char c = pw.charAt(i);
            if (c >= 'A' && c <= 'Z') hasUpper = true;
            else if (c >= 'a' && c <= 'z') hasLower = true;
            else if (c >= '0' && c <= '9') hasDigit = true;
            else hasSymbol = true;
        }

        if (longEnough && hasUpper && hasLower && hasDigit && hasSymbol) {
            System.out.println("Strong password.");
        } else {
            System.out.println("Weak password.");
        }
        System.out.print("Enter password: ");
        String pw = input.nextLine();

        boolean longEnough = pw.length() >= 8;
        boolean hasUpper = false;
        boolean hasLower = false;
        boolean hasDigit = false;
        boolean hasSymbol = false;

        for (int i = 0; i < pw.length(); i++) {
            char c = pw.charAt(i);
            if (c >= 'A' && c <= 'Z') hasUpper = true;
            else if (c >= 'a' && c <= 'z') hasLower = true;
            else if (c >= '0' && c <= '9') hasDigit = true;
            else hasSymbol = true;
        }

        if (longEnough && hasUpper && hasLower && hasDigit && hasSymbol) {
            System.out.println("Strong password.");
        } else {
            System.out.println("Weak password.");
        }
        System.out.print("Enter password: ");
        String pw = input.nextLine();

        boolean longEnough = pw.length() >= 8;
        boolean hasUpper = false;
        boolean hasLower = false;
        boolean hasDigit = false;
        boolean hasSymbol = false;

        for (int i = 0; i < pw.length(); i++) {
            char c = pw.charAt(i);
            if (c >= 'A' && c <= 'Z') hasUpper = true;
            else if (c >= 'a' && c <= 'z') hasLower = true;
            else if (c >= '0' && c <= '9') hasDigit = true;
            else hasSymbol = true;
        }

        if (longEnough && hasUpper && hasLower && hasDigit && hasSymbol) {
            System.out.println("Strong password.");
        } else {
            System.out.println("Weak password.");
        }

    }
}
