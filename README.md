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


                                                            //ODEV
        int a, r ;
        double pi=3.14, c;

        Scanner input = new Scanner(System.in);
        System.out.print("Yari cap giriniz =");
        r = input.nextInt();

        System.out.print("Merkez acisinin olcusunu giriniz = ");
        a = input.nextInt();

        c = (pi * (r*r) * a) / 360;

        System.out.println("Daire Alan = " + c);




    }
}
