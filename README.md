# Talent_Battle_Solutions
The java solutions for talent battle problems.
1)  Problem Statement:
   Take an input character from user and check whether it is an alphabet or not.
   Input : A
   Output: Alphabet
   Input : 7
   Output : Not an alphabet

 Solution:
 
 import java.util.*;
public class Main
{
	public static void main(String[] args) {
		Scanner scan=new Scanner(System.in);
		char c=scan.next().charAt(0);
		if((c>=65 && c<=90) || (c>=97 && c<=122)){
		    System.out.print("alphabet");
		}
		else{
		     System.out.print("not an alphabet");
		}
	}
}





