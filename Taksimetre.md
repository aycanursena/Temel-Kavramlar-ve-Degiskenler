```
package Giris;
import java.util.Scanner;

public class Taksimetre {
    public static void main(String[] args) {
        Scanner kilometre = new Scanner(System.in);

        double acilisTutar, kM_tutar, minTutar, gidilen_km, odenecekTutar;
        acilisTutar = 10;
        kM_tutar = 2.20;
        
        System.out.print("Gidilen Kilometre :");
        gidilen_km = kilometre.nextDouble();

        odenecekTutar = acilisTutar + gidilen_km * kM_tutar;
        
        System.out.print("Ödenecek Tutar :");
        System.out.println(odenecekTutar <= 20 ? odenecekTutar = 20 : odenecekTutar);
    }
}
```
