# tugas-mudah

import java.util.Scanner;

public class tugaskl {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);

        System.out.print("Masukkan sebuah bilangan: ");
        int angka = input.nextInt();

        // Mengecek apakah bilangan genap atau ganjil
        if (angka % 2 == 0) {
            System.out.println(angka + " adalah bilangan genap.");
        } else {
            System.out.println(angka + " adalah bilangan ganjil.");
        }

        input.close();
    }
}
Program meminta pengguna memasukkan satu bilangan (angka).
Menggunakan operasi modulus (% 2) untuk mengecek sisa bagi 2:
Jika angka % 2 == 0 → bilangan genap.
Jika tidak → bilangan ganjil.
Hasilnya ditampilkan ke layar.
Scanner ditutup dengan input.close().


