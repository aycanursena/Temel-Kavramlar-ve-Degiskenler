#### HİPOTENÜS BULMA
```
package Giris;

import javax.sound.midi.Soundbank;
import java.util.Scanner;

public class HipotenusBulma {
    public static void main(String[] args) {

        Scanner uzunluk = new Scanner(System.in);
        int kenar1, kenar2, hipotenus;

        System.out.print("1. Kenar Uzunluğu :");
        kenar1 = uzunluk.nextInt();

        System.out.print("2. Kenar Uuznluğu :");
        kenar2 = uzunluk.nextInt();

        hipotenus = (kenar1 * kenar1) + (kenar2 * kenar2);

        System.out.println("Hipotenüs :" + Math.sqrt(hipotenus));
    }
}
```
#### ÜÇGENDE ALAN HESABI
```
package Giris;
import java.util.Scanner;

public class UcgenAlanHesaplama {
    public static void main(String[] args) {
        Scanner uzunluk = new Scanner(System.in);

        int a, b, c, cevre, u, alan;

        System.out.print("1. Kenar Uzunluğunu Giriniz :");
        a = uzunluk.nextInt();
        System.out.print("1. Kenar Uzunluğunu Giriniz :");
        b = uzunluk.nextInt();
        System.out.print("1. Kenar Uzunluğunu Giriniz :");
        c = uzunluk.nextInt();

        cevre = a + b + c;
        System.out.println("Üçgenin Çevresi :" + cevre);

        u = cevre / 2;

        alan = u + (u - a) * (u + b) * (u - c);
        System.out.println("Üçgenin Alanı :" + Math.sqrt(alan));
    }
}
```
