# methodsPractice

package javaapplication23;

import java.util.Scanner;

public class JavaApplication23 {

    public static void main(String[] args) {
        Scanner reader = new Scanner(System.in);
        System.out.println("How many? ");
        int howMany = Integer.parseInt(reader.nextLine());
        
        int counter = 1;
        
        while(counter <= howMany){
            printText();
            counter++;
        }

    }

    public static void printText() {
        System.out.println("In the beginning there were the swamp, the hoe and Java.");
        }
}
