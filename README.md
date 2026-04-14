import java.util.Scanner;

public class App {
    public static int maior (int a,int b){
        if (a > b) {
            return a;
            
        }else{
            return b;
            
        }
    }
    public static void main(String[] args) throws Exception {
        Scanner entrada = new Scanner(System.in);
        System.out.print("digite o primeiro numero: ");
        int a = entrada.nextInt();
        System.out.print("digite o segundo numero numero: ");
        int b = entrada.nextInt();
        System.out.print("esse e o maior numero: " + maior(a, b) );
        entrada.close();

        
    }
}
