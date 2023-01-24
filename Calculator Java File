import java.lang.Math;
import java.util.Scanner;

class ohmsLaw {
    
    public static double voltage (double i, double r) {
        return i * r;
    }
    
    public static double amperage (double e, double r) {
        return e / r;
    }
    
    public static double resistance (double e, double i) {
        return e / i;
    }
    
    public static void main(String[] args) {
        
        for (int t = 0; t <= .9;) {
        
            Scanner myObj1 = new Scanner(System.in);
        
            System.out.println("Would you like to calculate volts, amps, or resistance\nPress e for volts\nPress i for amps\nPress r for resistance\n");
        
            String calcChoice = myObj1.nextLine();
        
            if (calcChoice.equals("e")) {
            
                Scanner iInput = new Scanner(System.in);
            
                System.out.println("Voltage is amps times resistance (i * r)");
            
                System.out.println("Enter amps: ");
            
                double iNum = iInput.nextDouble();
            
                System.out.println("Enter resistance: ");
            
                Scanner rInput = new Scanner(System.in);
            
                double rNum = rInput.nextDouble();
            
                double e = voltage(iNum, rNum);
            
                System.out.println("The voltage is " + e);
            
                t++;
            }
            else if (calcChoice.equals("i")) {
            
                Scanner eInput = new Scanner(System.in);
            
                System.out.println("Amps is voltage divided by resistance (e / r)");
            
                System.out.println("Enter voltage: ");
            
                double eNum = eInput.nextDouble();
            
                System.out.println("Enter resistance: ");
            
                Scanner rInput = new Scanner(System.in);
            
                double rNum = rInput.nextDouble();
            
                double i = amperage(eNum, rNum);
            
                System.out.println("The amperage is " + i);
            
                t++;
            }
            else if (calcChoice.equals("r")) {
            
                Scanner eInput = new Scanner(System.in);
            
                System.out.println("Resistance is voltage divided by amperage (e / i)\n");
            
                System.out.println("Enter voltage: ");
            
                double eNum = eInput.nextDouble();
            
                System.out.println("Enter amperage: ");
            
                Scanner iInput = new Scanner(System.in);
            
                double iNum = iInput.nextDouble();
            
                double r = resistance(eNum, iNum);
            
                System.out.println("The resistance is " + r);
            
                t++;
            }
            else {
                System.out.println("Input not found\n");
            }
        }
    }
}
