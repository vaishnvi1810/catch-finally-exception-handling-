# catch-finally-exception-handling-
catch finally exception handling
public class Main {
  public static void main(String[] args) {
    try {
      int[] myNumbers = {1, 2, 3,4,5};
      System.out.println(myNumbers[5]);
    } catch (Exception e) {
      System.out.println("Something is missing");
    }
  }
}
