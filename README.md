# UcgenAlan
UcgenAlan




import java.util.Scanner;

public class Dikucgen {
    public static void main(String[] args) {
    
        double u,c1,c2,c3,cevre,alan;

        Scanner input = new Scanner(System.in) ;
        System.out.println("Üçgenin alanını bulan program " ) ;
        
        System.out.println("1.Kenar" ) ;
        c1 = input.nextInt() ;
        System.out.println("2.Kenar" ) ;
        c2 =input.nextInt() ;
        System.out.println("3.Kenar" ) ;
        c3 = input.nextInt() ;

            u=(c1+c2+c3)/2 ;
            cevre=2*u;

            System.out.println ( " Üçgenin alanı : " + Math.sqrt (u*(u-c1) * (u-c2) * (u-c3)));
            System.out.println("Cevresi :" +cevre);

    }
}
