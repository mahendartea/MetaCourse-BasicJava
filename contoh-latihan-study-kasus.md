import java.util.Scanner ;  


public class Pelatihan_2 {
    public static void main(String[] args) {

        

        try (Scanner input = new Scanner(System.in)) {
            
            System.out.print("Masukkan:Nilai panjang: ");
            int panjang = input.nextInt();

        
            
            System.out.print("Masukkan:Nilai Lebar: ");
            int lebar = input.nextInt();


            int hasil = panjang * lebar ;

            System.out.println("Hasil nya adalah " +hasil);


            
            
        }
        
    }
    
}