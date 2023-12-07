# AI-java-Chat-and-Copilot-test
AI-java-Chat-and-Copilot-test

## Copied code from ChatGPT3.5

```java
public class PrimeChecker {
    private int number;

    public PrimeChecker(int number) {
        this.number = number;
    }

    public boolean isPrime() {
        if (number <= 1) {
            return false;
        }
        for (int i = 2; i <= Math.sqrt(number); i++) {
            if (number % i == 0) {
                return false;
            }
        }
        return true;
    }

    public static void main(String[] args) {
        int numToCheck = 17;  // Replace with the number you want to check
        PrimeChecker primeChecker = new PrimeChecker(numToCheck);

        if (primeChecker.isPrime()) {
            System.out.println(numToCheck + " is prime.");
        } else {
            System.out.println(numToCheck + " is not prime.");
        }
    }
}

```
