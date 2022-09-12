# daire_cevre_alan


import java.util.Scanner;

public class daire {

    public static void main(String[] args) {

        int r;
        double pi=3.14;

        Scanner input=new Scanner(System.in);
        System.out.println("Dairenin yarı capını gırın : ");
        r =input.nextInt();

        double alan=pi*r*r;
        double cevre=2*pi*r;

        System.out.println("Alan : "+ alan);
        System.out.println("Cevresi : "+ cevre);



    }
}
