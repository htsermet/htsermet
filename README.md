Youtube Linki : https://www.youtube.com/watch?v=EJTijvni-CA



public class soru1 {
    public static void main(String[] args) {
        int sayi1 = 10;
        int sayi2 = 20;

        int toplam = sayi1 + sayi2;

        System.out.println("Sayıların Toplamı: " + toplam);
    }
}
Sayıların Toplamı: 30




package com.company;
import java.util.Scanner;
public class soru2 {
    public static void main(String[] args) {
        Scanner reader = new Scanner(System.in);

        System.out.print("Birinci Sayıyı Girin: ");
        int sayi1 = reader.nextInt();
        System.out.print("İkinci Sayıyı Girin: ");
        int sayi2 = reader.nextInt();

        int toplam = sayi1 + sayi2;

        System.out.println("Sayıların Toplamı: " + toplam);
    }
}
Birinci Sayıyı Girin: 15
İkinci Sayıyı Girin: 21
Sayıların Toplamı: 36


public class soru3 {
    public static void main(String[] args) {

        float sayi1 = 1.5f;
        float sayi2 = 2.0f;

        float carpim = sayi1 * sayi2;

        System.out.println("Sayıların Çarpımı: " + carpim);
    }
}

Sayıların Çarpımı: 3.0

public class soru4 {
    public static void main(String[] args) {

        int sayi = 25, bolen = 4;

        int bolum = sayi / bolen;
        int kalan = sayi % bolen;

        System.out.println("İşlem:"+sayi+"/"+bolen);
        System.out.println("Bölüm = " + bolum);
        System.out.println("Kalan = " + kalan);
    }
}
İşlem:25/4
Bölüm = 6
Kalan = 1



import java.util.Scanner;
public class soru5 {
    public static void main(String[] args) {
        Scanner reader = new Scanner(System.in);
        System.out.print("Bir Sayı Girin:");

        double sayi = reader.nextInt();

        if (sayi < 0.0)
            System.out.println(sayi + " Negatiftir.");


        else if ( sayi > 0.0)
            System.out.println(sayi + " Pozitiftir.");


        else
            System.out.println(sayi + "  Sıfırdır.");
    }
}
Bir Sayı Girin:24
24.0 Pozitiftir.



public class soru6 {
    public static void main(String[] args) {

        int sayi = 100;
        int toplam = 0;

        for(int i = 1; i <= sayi; ++i)
        {
            toplam += i;
        }

        System.out.println("1-100 arasındaki sayıların toplamı = " + toplam);
    }
}
1-100 arasındaki sayıların toplamı = 5050



import java.util.Scanner;
public class soru7 {
    public static void main(String[] args) {

        Scanner giris=new Scanner(System.in);
        int sayi;
        System.out.print("Bir tane Tam Sayı Girin :");
        sayi=giris.nextInt();

        if (sayi %2==0) {
            System.out.println(sayi+" Sayısı Çift Sayıdır");

        }
        else {
            System.out.println(sayi+" Sayısı Tek Sayıdır");
        }
    }
}

Bir tane Tam Sayı Girin :19
19 Sayısı Tek Sayıdır




public class soru8 {
    public static void main(String[] args) {
        double n1 = -5, n2 = 11.4, n3 = 5;

        System.out.println("..:: Sayılar ::..");
        System.out.println(n1);
        System.out.println(n2);
        System.out.println(n3);
        System.out.println("");
        if( n1 >= n2 && n1 >= n3)
            System.out.println(n1 + " sayısı büyüktür.");

        else if (n2 >= n1 && n2 >= n3)
            System.out.println(n2 + " sayısı büyüktür.");

        else
            System.out.println(n3 + " sayısı büyüktür.");
    }
}
..:: Sayılar ::..
-5.0
11.4
5.0

11.4 sayısı büyüktür.



public class soru9 {
    public static void main(String[] args) {
        int yil = 2018;
        boolean artik = false;

        if(yil % 4 == 0)
        {
            if( yil % 100 == 0)
            {
                if ( yil % 400 == 0)
                    artik = true;
                else
                    artik = false;
            }
            else
                artik = true;
        }
        else
            artik = false;

        if(artik)
            System.out.println(yil + " artık yıldır.");
        else
            System.out.println(yil + " artık yıl değildir.");
    }
}
2018 artık yıl değildir.



package com.company;
import java.util.Scanner;
public class soru10 {
    public static void main(String[] args) {
        Scanner reader = new Scanner(System.in);
        int vizeNot,finalNot;
        double ortalama;
        String durum="";
        System.out.print("Vize Notunuzu Girin : ");
        vizeNot=reader.nextInt();
        System.out.print("Final Notunuzu Girin : ");
        finalNot=reader.nextInt();
        ortalama=vizeNot*0.4+finalNot*0.6;
        if(ortalama>=50 && finalNot>=50){
            durum="Geçti";
        }
        else{
            durum="Kaldı";
        }
        System.out.println("Ortalama : " + ortalama);

        System.out.println("Durumunuz: " + durum);
    }
}
Vize Notunuzu Girin : 40
Final Notunuzu Girin : 60
Ortalama : 52.0
Durumunuz: Geçti



