package okan6;
import java.util.Scanner;
public class okan66 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		int toplam =0, girdi;
		Scanner input = new Scanner(System.in);
		System.out.println("toplamak istediğiniz sayıyı girin");
		girdi = input.nextInt();
		while (girdi != 0){
			toplam = girdi + toplam;
			System.out.println("toplamak istediğiniz sayıyı girin");
			girdi = input.nextInt();
		}
		System.out.println("toplam sayi" + toplam);

	}

}
