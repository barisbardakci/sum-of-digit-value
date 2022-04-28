# sum-of-digit-value
Java101_23 this program sums each digit of a given number by discarding their place values

https://www.patika.dev/tr

import java.util.Scanner;
public class Main
{
	public static void main(String[] args) {
	    
	    int number, sum=0, numDigit=0;
	    
	    Scanner input=new Scanner(System.in);
	    System.out.print("Enter a number : ");
	    number=input.nextInt();
	    
	    while(number!=0){
	        sum=sum+number%10;
	        number/=10;
	        numDigit++;
	    }
	    System.out.print(sum);

	}
}
