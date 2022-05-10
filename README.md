# Sayıları Büyükten Küçüğe Sıralama

**ÖDEV**
* Girilen 3 sayıyı "küçükten büyüğe" sıralayan programı yazınız.

**CEVAP:**

```
import java.util.Scanner;

public class SayilariBuyuktenKucugeSiralama {
    public static void main(String[] args) {

        int a, b, c;

        Scanner inp = new Scanner(System.in);

        System.out.print("1. sayiyi giriniz : ");
        a = inp.nextInt();

        System.out.print("2. sayiyi giriniz : ");
        b= inp.nextInt();

        System.out.print("3. sayiyi giriniz : ");
        c = inp.nextInt();

        if((a < b) && (a< c)){
            System.out.println("a < b < c");
            if(b < c){
                System.out.println("b < a < c");
            }
            else {
                System.out.println("a < c < b");
            }
        }
        else if ((b < a) && (b < c)){
            if(a < c){
                System.out.println("b < a < c");
            }
            else {
                System.out.println("b < c < a");
            }
            }
        else {
            if(a<b){
                System.out.println("c < a < b");
            }
            else {
                System.out.println("c < b < a");
            }
        }
        }
    }



```
www.patika.dev
