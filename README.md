
package inlämningsuppgift_2_datum_sg;
import java.util.Scanner;
public class Inlämningsuppgift_2_Datum_SG {

    public static void main(String[] args) {
        
        Scanner scan = new Scanner(System.in);
        
        System.out.println("Ange datum nedan: ");
        System.out.println("År: ");
        int år = scan.nextInt();
        
        System.out.println("Månad: ");
        int månad = scan.nextInt();
        
        System.out.println("Dag: ");
        int dag = scan.nextByte();
        
        
        int dagarMånad; 
        dagarMånad = månad >=12 ;
        
        
        System.out.println("Den månad du har angivit innehåller " + " dagar.");
        

        
    }
    
}
