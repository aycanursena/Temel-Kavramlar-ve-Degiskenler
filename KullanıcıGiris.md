```
package Giris;
import java.util.Scanner;

public class KullaniciGiris {
    public static void main(String[] args) {
        Scanner girilenDeger = new Scanner(System.in);
        String kAdi, kSifre;
        int secim,  yeniSifre;

        System.out.print("Kullanıcı Adınız :");
        kAdi = girilenDeger.nextLine();
        System.out.print("Şifreniz :");
        kSifre = girilenDeger.nextLine();

        if (kAdi.equals("ayca") && kSifre.equals("123")) {
            System.out.println("Başarıyla Giriş Yaptınız.");
        } else if (kSifre != "123"){
            System.out.println("Giriş Başarısız.!");

            System.out.println("Şifrenizi sıfırlamak ister misiniz?");
            System.out.println("1-Evet \n 2-Hayır");
            System.out.print("Seçiminiz :");
            secim = girilenDeger.nextInt();

            if (secim == 1){
                System.out.print("Yeni şifrenizi giriniz :");
                yeniSifre = girilenDeger.nextInt();
                if (yeniSifre == 123){
                    System.out.println("Şifre oluşturulamadı, lütfen başka şifre giriniz.");
                }else
                    System.out.println("Şifre oluşturuldu.");
            }
        }
    }
}
```
