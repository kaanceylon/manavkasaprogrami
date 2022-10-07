# manavkasaprogrami


import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        double armut=2.14,elma=3.67,domates=1.11,muz=0.95,patlican=5.00;
        double a,b,c,d,e,total;


        Scanner inp = new Scanner(System.in);

        System.out.print("Armut Kilosunu Giriniz: ");
        a = inp.nextDouble();

        System.out.print("Elma Kilosunu Giriniz: ");
        b = inp.nextDouble();

        System.out.print("Domates Kilosunu Giriniz: ");
        c = inp.nextDouble();

        System.out.print("Muz Kilosunu Giriniz: ");
        d = inp.nextDouble();

        System.out.print("Patlıcan Kilosunu Giriniz: ");
        e = inp.nextDouble();




        total = (armut*a)+(elma*b)+(domates*c)+(muz*d)+(patlican*e);

        System.out.print("Toplam Ücret: " +total);
    }
}


