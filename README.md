public class Pattern {

    public static void main(String[] args) {

        int n = 6;

        for (int i = 1; i <= n; i++) {

            int num = i % 2;   // starting number (0 or 1)

            for (int j = 1; j <= i; j++) {

                System.out.print(num + " ");
                num = 1 - num;   // toggle between 0 and 1

            }

            System.out.println();
        }
    }
}
