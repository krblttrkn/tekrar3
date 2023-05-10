# Dik Üçgende Hipotenüs Bulan Program
* Java ile kullanıcıdan dik kenarların uzunluğunu alan ve hipotenüsü hesaplayan programı yazın.
# Ödev
* Üç kenar uzunluğunu kullanıcıdan aldığınız üçgenin alanını hesaplayan programı yazın.
## Formül
* **Üçgenin Çevresi** = 2 *u*
* *u* = (a+b+c)/2
* **Alan * Alan = u * (u-a) * (u-b) * (u-c)**
* **Alan = √(u(u-a)(u-b)(u-c))**
```
import java.util.Scanner;

public class Alan {
    public static void main(String[] args){
        int a,b,c;
        double u,alan;
        Scanner input = new Scanner(System.in);

        System.out.println("Aşağıda Bir Üçgene Ait Kenar Uzunlukları Giriniz :");
        System.out.print("1. Kenarın Uzunluğu : ");
        a=input.nextInt();
        System.out.print("2. Kenarın Uzunluğu : ");
        b=input.nextInt();
        System.out.print("3. Kenarın Uzunluğu : ");
        c=input.nextInt();

        u=(a+b+c)/2.0;
        alan=Math.sqrt(u*(u-a)*(u-b)*(u-c));
        System.out.print("Üçgenin Alanı : "+alan);
    }
}

```
# Patika Profilim
***
<a href="https://academy.patika.dev/profile">Patika Profilim</a>