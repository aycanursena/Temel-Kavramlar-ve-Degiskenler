```
package Giris;
import java.util.Scanner;

public class DaireAlan_Cevre {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
         double pi, yaricap, alan1, cevre, olcu, alan2;
         pi = 3.14;

        System.out.print("Dairenin Yarıçapı :");
        yaricap = input.nextDouble();

        alan1 = pi * yaricap * yaricap;
        System.out.println("Dairenin Alanı :" + alan1);

        cevre = 2 * pi * yaricap;
        System.out.println("Dairenin Çevresi :" + cevre);

        // Yarıçapı ve merkez açısının ölçüsü verilen dairenin alanı

        System.out.print("Merkez Açısının Ölçüsü :");
        olcu = input.nextDouble();

        alan2 = ( pi * (yaricap * yaricap)) * olcu / 360 ;
        System.out.println("Yarıçap ve Ölçüsü Bilinen Dairenin Alanı :" + alan2);
    }
}
```
