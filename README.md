# kucuktenBuyugeSayiSiralama

import java.util.Scanner;
public class Main {

    public static void main(String[] args) {
    
        Scanner inp = new Scanner(System.in);
        
        int n1, n2, n3;
        
        System.out.println("Lütfen Birinci Sayıyı Giriniz");
        
        n1 = inp.nextInt();
        
        System.out.println("Lütfen İkinci Sayıyı Giriniz");
        
        n2 = inp.nextInt();
        
        System.out.println("Lütfen Üçüncü Sayıyı Giriniz");
        
        n3 = inp.nextInt();

        if (n1 < n2) {
            if (n1 < n3) {
                System.out.println("En Küçük Sayı" + n1);
                if (n2 < n3) {
                    System.out.println("Ortanca Sayı" + n2);
                    System.out.println(" " + n1 + "<" + n2 + "<" + n3);
                } else {
                    System.out.println("En Büyük Sayı" + n2);
                    System.out.println(" " + n1 + "<" + n3 + "<" + n2);
                }
            }

        }
        if (n2 < n1) {
            if (n2 < n3) {
                System.out.println("En Küçük Sayı" + n2);
                if (n1 < n3) {
                    System.out.println("Ortanca Sayı" + n1);
                    System.out.println(" " + n2 + "<" + n1 + "<" + n3);
                } else {
                    System.out.println("En Büyük Sayı" + n1);
                    System.out.println(" " + n2 + "<" + n3 + "<" + n1);
                }
            }
        }
        if (n3 < n1) {
            if (n3 < n2) {
                System.out.println("En Küçük Sayı" + n3);
                if (n1 < n2) {
                    System.out.println("Ortanca Sayı" + n1);
                    System.out.println(" " + n3 + "<" + n1 + "<" + n2);
                } else {
                    System.out.println("En Büyük Sayı" + n1);
                    System.out.println(" " + n3 + "<" + n2 + "<" + n1);
                }
            }
        }

    }
}
