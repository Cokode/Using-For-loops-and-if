# Using-For-loops-and-if


public class Main {
    public static void main(String[] args) {

        int total = 0;
        int count = 0;
        for (int i = 1; i <= 1000; i++) {
            if(i % 3 == 0 && i % 5 == 0) {
                count++;
                total = total + i;
                System.out.println("Found number " + i);
            }
            if (count == 5) {
                break;
            }
        }
        System.out.println("Sum of all numbers is " + total);
    }
}
