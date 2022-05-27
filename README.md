# TersUcgenYapma

import java.util.Scanner;

public class Main {

    public static void main(String[] args) {

        Scanner input = new Scanner(System.in);
        System.out.print("Bir Sayi Giriniz: ");
        int number = input.nextInt();

        for (int i=number; i>0;i--){
            for (int k=1;k<=(number-i);k++){
                System.out.print(" ");
            }
            for (int j=1; j<=(2*i)-1;j++){
                System.out.print("*");
            }
            System.out.println();
        }
    }
}
