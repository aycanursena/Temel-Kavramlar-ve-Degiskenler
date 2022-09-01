```
package Giris;
import java.util.Scanner;

public class BasitHesapMakinesi {
    public static void main(String[] args) {
        int sayi1, sayi2, seçim;

        Scanner input = new Scanner(System.in);
        System.out.print("Bir sayı giriniz :");
        sayi1 = input.nextInt();
        System.out.print("Bir sayı giriniz :");
        sayi2 = input.nextInt();

        System.out.println("1 - toplama \n 2 - Çıkarma \n 3- Çarpma \n 4 - Bölme");
        System.out.print("Seçiminiz :");
        seçim = input.nextInt();

        switch (seçim){
            case 1 :
                System.out.println("Toplam :" + (sayi1 + sayi2));
                break;
            case 2 :
                System.out.println("Fark :" + (sayi1 - sayi2));
                break;
            case 3 :
                System.out.println("Çarpım :" + (sayi1 * sayi2));
                break;
            case  4 :{
                if (sayi2 != 0) {
                    System.out.println("Bölüm : " + (sayi1 / sayi2));
                }
                else
                    System.out.println("Bir sayı 0'a bölünemez.!");
                break;
            }
            default:
                System.out.println("Yanlış seçim yaptınız. Tekrar Deneyiniz.!");
                break;
        }
    }
}
```
