# javanotortalamasi

import java.util.Scanner;

public class notortalamasi {

    public static void main(String[] args) {
                //değişken ekledik
                int mat, fizik, kimya, turkce, tarih, muzik;


                // scanner sınıfımızı ekledik
                Scanner input = new Scanner(System.in);

                //kullanıcı verileri ekle
                System.out.print("Matematik Notunuz:");
                mat = input.nextInt();

                System.out.print("Fizik Notunuz:");
                fizik = input.nextInt();

                System.out.print("Kimya Notunuz:");
                kimya = input.nextInt();

                System.out.print("Türkçe Notunuz:");
                turkce = input.nextInt();

                System.out.print("Tarih Notunuz:");
                tarih = input.nextInt();

                System.out.print("Müzik Notunuz:");
                muzik = input.nextInt();

                int toplam = (mat + fizik + kimya + turkce + tarih + muzik);
                double ortalama = toplam / 6;

                System.out.println("Ortalamanız: " + ortalama);
                String str = ortalama > 60 ? "Sınıfı Geçti" : "Sınıfta Kaldı";

                System.out.print(str);


            }
        }




