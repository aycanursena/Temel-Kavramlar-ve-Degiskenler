```
package Giris;
import java.util.Scanner;

public class KDV_Hesapla {
    public static void main(String[] args) {
        double tutar, kdvOran, kdvTutar, kdvliTutar;

        Scanner input = new Scanner(System.in);
        System.out.print("Girilen Tutar : ");
        tutar = input.nextDouble();

        kdvOran = (tutar > 0) && (tutar < 1000) ? 0.18 : 0.08;
        kdvTutar = tutar * kdvOran;
        kdvliTutar = tutar + kdvTutar;

        System.out.println("KDV Oranı : " + kdvOran);
        System.out.println("KDV Tutarı : " +kdvTutar);
        System.out.println("KDV'li Tutar : " + kdvliTutar);
    }
}
```
