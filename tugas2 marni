import java.util.Scanner;

public class tugas2 {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);

        int nominal, sisa, lembar50rb, lembar20rb, lembar5rb, lembar2rb, keping500;

        System.out.print("Masukkan nominal: ");
        nominal = input.nextInt();

        // Menghitung lembar uang kertas dan keping uang logam
        lembar50rb = nominal / 50000;
        sisa = nominal % 50000;
        lembar20rb = sisa / 20000;
        sisa = sisa % 20000;
        lembar5rb = sisa / 5000;
        sisa = sisa % 5000;
        lembar2rb = sisa / 2000;
        sisa = sisa % 2000;
        keping500 = sisa / 500;

        // Menampilkan hasil perhitungan
        System.out.println(lembar50rb + " lembar 50 ribuan");
        System.out.println(lembar20rb + " lembar 20 ribuan");
        System.out.println(lembar5rb + " lembar 5 ribuan");
        System.out.println(lembar2rb + " lembar 2 ribuan");
        System.out.println(keping500 + " keping 500an");
    }
}