import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        System.out.println("Hello world!");

        Scanner input = new Scanner(System.in);
        System.out.println("hello\n");
        int varA = 10;
        int varB = 20;
        double varY = 30;
        double varX = 40;
        boolean isPlus = true; //
        
        System.out.println("masukan int A:");
        varA = input.nextInt();
        System.out.println("int A: " + varA);

        System.out.println("silahkan input B:");
        varB = input.nextInt();
        System.out.println("intB = " + varB);

        String nama = "";
        System.out.println("Masukkan nama: ");
        nama = input.nextLine();
        nama = input.nextLine();
        System.out.println("Nama : " + nama);

        System.out.println("silahkan input nilai double pertama:");
        varX = input.nextDouble();
        System.out.println("double 1 = " + varY);

        System.out.println("silahkan input nilai double kedua:");
        varY = input.nextDouble();
        System.out.println("double 2 = " + varX);

        System.out.println("silahkan input boolean:");
        isPlus = input.nextBoolean();
        System.out.println("nilai boolean = " + isPlus);
    }

}
