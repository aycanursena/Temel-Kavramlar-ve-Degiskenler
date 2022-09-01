```
package Giris;
import java.util.Scanner;

public class SinifiGeçmeDurumu {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);

        int matematik, fizik, turkce, kimya, muzik, toplam = 0, dersSayisi = 0;
        double ort;

        System.out.print("Matematik Dersi Notu :");
        matematik = input.nextInt();
        if (matematik >= 0 && matematik <= 100){
            toplam += matematik;
            dersSayisi++;
        }else {
            System.out.println("Ders notu 0 ile 100 aralığında olmalı! Ortalamaya katılmaz.");
        }
        System.out.print("Fizik Dersi Notu :");
        fizik = input.nextInt();
        if (fizik >= 0 && fizik <= 100){
            toplam += fizik;
            dersSayisi++;
        }else {
            System.out.println("Ders notu 0 ile 100 aralığında olmalı! Ortalamaya katılmaz.");
        }
        System.out.print("Türkçe Dersi Notu :");
        turkce = input.nextInt();
        if (turkce >= 0 && turkce <= 100){
            toplam += turkce;
            dersSayisi++;
        }else {
            System.out.println("Ders notu 0 ile 100 aralığında olmalı! Ortalamaya katılmaz.");
        }
        System.out.print("Kimya Dersi Notu :");
        kimya = input.nextInt();
        if (kimya >= 0 && kimya <= 100){
            toplam +=kimya;
            dersSayisi++;
        }else {
            System.out.println("Ders notu 0 ile 100 aralığında olmalı! Ortalamaya katılmaz.");
        }
        System.out.print("Müzik Dersi Notu :");
        muzik = input.nextInt();
        if (muzik >= 0 && muzik <= 100){
            toplam += muzik;
            dersSayisi++;
        }else {
            System.out.println("Ders notu 0 ile 100 aralığında olmalı! Ortalamaya katılmaz.");
        }

        ort = toplam / dersSayisi;
        System.out.println("Ortalamanız :" + ort);
        if (ort > 50) {
            System.out.println("Sınıf Geçildi.");
        }else
            System.out.println("Sınıf Geçilemedi.");
    }
}
```
