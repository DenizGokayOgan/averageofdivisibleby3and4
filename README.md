#  Average Of Numbers Divisible By 3 And 4
    import java.util.Scanner;

    public class Main {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        int sayi, i, j=0, toplam=0;
        Scanner scanner = new Scanner(System.in);

        System.out.print("Sayı giriniz: ");
        sayi = scanner.nextInt();
        for(i=1; i<sayi; i++){
            if((i%4==0) && (i%3==0)){
                System.out.println("3'e ve 4'e tam bölünenler: " +i);
                toplam += i;
                j += 1;
            }

        }
        System.out.println("Sayıların ortalaması: " + (toplam/j));
        }
    }
