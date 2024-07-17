import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
    
       Scanner input=new Scanner(System.in);
       
       int sayi;
       
       double result=0.0;
       
       System.out.print("sayı: ");
       
       sayi=input.nextInt();
       
       for(double i=1;i<=sayi;i++){
       
           result+=(1/i);
           
       }
       
       System.out.print(result);









    }
}
