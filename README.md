```java
import java.util.Scanner;

public class kullanici {
    public static void main(String[] args) {
        String kullaniciAd, sifre;
        

        Scanner inp = new Scanner(System.in);

        System.out.print("Kullanıcı Adınız :");
        kullaniciAd = inp.nextLine();
        System.out.print("Şifreniz :");
        sifre = inp.nextLine();
    

        if (kullaniciAd.equals("patika") && sifre.equals("java123")) {
            System.out.println("Giriş Yaptınız");

        } else {
            System.out.println("Bilgileriniz Yanlış");
           

        }


    }

}
    
```

