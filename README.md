# String
import java.util.Scanner;
public class vasanth {
	public static void main(String[] args) {
	Scanner sc=new Scanner(System.in);
		System.out.println("Please enter the String");
		String str=sc.nextLine();
		System.out.println("Original String"+str);
		//creating empty String
		String str1="";
		//Splitting the String to reverse the order
		String []arr=str.split(" ");
		//logic
	    for(int i=0;i<arr.length;i++) {
	    	for(int j=arr[i].length()-1;j>=0;j--) {
	    		str1=str1+arr[i].charAt(j);
	    	}
	    	 str1=str1+" ";
	    }
	    System.out.println(str1);
		
		
		
		
		
	}
	} 
