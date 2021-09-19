import java.util.Scanner;

public class odevim {
    public static void main(String[] args) {
        // Degiskenler
        int  mat, fizik, kimya, turkce, tarih, muzik;

        // Scanner sinifim
        Scanner Not = new Scanner(System.in);

        // Kullanici bilgileri
        System.out.print("Matematik Notunuz : ");
        mat = Not.nextInt();

        System.out.print("Fizik Notunuz : ");
        fizik = Not.nextInt();

        System.out.print("Kimya Notunuz : ");
        kimya = Not.nextInt();

        System.out.print("Türkçe Notunuz : ");
        turkce = Not.nextInt();

        System.out.print("Tarih Notunuz : ");
        tarih = Not.nextInt();

        System.out.print("Müzik Notunuz : ");
        muzik = Not.nextInt();
          // Ortalama deger hesabı
        int toplam = (mat + fizik + kimya + turkce + tarih + muzik);
        double ortalama = toplam / 6.0;
        System.out.println("Ortalamanız :" + ortalama) ;

        // Sonucun belirlenmesi
        System.out.println("Ortalamanız = " + ortalama);
        boolean kosul1 = ortalama >= 60;
        System.out.println("Durum = " + (kosul1==true ? "Sınıfı Geçtiniz" : "Sınıfta Kaldınız"));

    }
}
