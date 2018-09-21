# MakeASandwich
String exercise
package stringAssignments;

import java.util.Scanner;

public class MakeSandwich {
	public static void main(String[] args) {

		Scanner scan = new Scanner(System.in);
		System.out.println("Enter please first word");
		String word1 = scan.next();
		System.out.println("Enter please second word");
		String word2 = scan.next();

		if (word1.length() % 2 == 0) {
			System.out.println(
					word1.substring(0, word1.length() / 2) + "" + word2 + "" + word1.substring(word1.length() / 2));
		} else {
			System.out.println("does not match");
		}
		scan.close();
	}
}
