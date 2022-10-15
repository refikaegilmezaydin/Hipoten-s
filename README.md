# Hipoten-s
hipotenüs bulan programdır
package Deneme;
import java.util.Scanner;
public class nus {
    public static void main(String[] args) {
        Scanner tenus = new Scanner(System.in);
        double a, b, c;
        System.out.println("1. DİK KENAR UZUNLUĞUNU GİRİN:");
        a = tenus.nextDouble();
        System.out.println("2. DİK KENAR UZUNLUĞUNU GİRİN:");
        b = tenus.nextDouble();
        c = Math.sqrt((a * a) + (b * b));
        System.out.println("HİPOTENÜSÜN UZUNLUĞU:" +c);
    }
www.patika.dev
