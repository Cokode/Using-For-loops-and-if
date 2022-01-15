# Using-For-loops-and-if


public class Main {

    Public static void main (String[] args) {
    int total = 0;
        int count = 0;
        for (int i = 1; i <= 1000; i++) {
            if(i % 3 == 0 && i % 5 == 0) {
                count++;
                System.out.println("Found number " + i);
                total = total + i;
                if (count == 5) {
                    System.out.println("Sum of all numbers is " + total);
                    break;
            }
            }
         }
        }
}
