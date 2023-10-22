# MultiMethods
public class tst2 {
    public static void main(String[] args) {
        testMake("from Martian");
        examResults("Taleh Hasanov", 13);
        examResults("Other Person", 15);

        System.out.println(totality(7,14,23));


    }

    private static void testMake(String names) {
        System.out.println("I will back " + names);
    }

    private static void testMath(int a) {
        System.out.println(a);
    }

    private static void examResults(String ad, int c) {
        System.out.println("Your result is " + ad + c);
    }

    private static int totality(int t, int j) {
        return t+j;

    }

    private static int totality(int t, int j, int h) {
        return t + j + h;

    }
}

