```
package Giris;
import java.util.Scanner;

public class VKI_Hesaplama {
    public static void main(String[] args) {
        Scanner girilenDeğer = new Scanner(System.in);

        double kilo, boy, vki;
        System.out.print("Kilonuzu giriniz (kg) : ");
        kilo = girilenDeğer.nextDouble();

        System.out.print("Boyunuzu Giriniz (m) :");
        boy = girilenDeğer.nextDouble();

        vki = kilo / (boy * boy);
        System.out.println("Vücut Kitle İndeksiniz :" + vki);
    }
}
```
