import java.util.Scanner;

public class ZakatMaal {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        // Meminta input jumlah harta dalam bentuk desimal
        System.out.print("Masukkan jumlah harta (uang) yang dimiliki: ");
        double harta = scanner.nextDouble();

        // Menghitung zakat maal (2.5% dari harta)
        double zakat = harta * 0.025;

        // Menampilkan jumlah zakat yang harus dibayar
        System.out.printf("Jumlah zakat yang harus dibayarkan: Rp %.2f%n", zakat);

        scanner.close();
    }
}
