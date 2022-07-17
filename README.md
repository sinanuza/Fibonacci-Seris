# Fibonacci-Seris
www.patika.dev



import java.util.Scanner;

public class Fibonacci {
    public static void main(String[] args) {
            int sayi;
           int a,b,c,d;
           a=1;
           b=1;
           System.out.println("Lutfen sayiyi giriniz:");
           Scanner input=new Scanner(System.in);
           sayi=input.nextInt();
        System.out.println(a);
        System.out.println(b);
           for (int i=1;i<=sayi;i++){
               c=a+b;
               a=b;
               b=c;
               System.out.println(c);
           }
        }
    }
