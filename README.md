# Maximum-value-among-negative-numbers
I have a done a program in MAXIMUM VALUE AMONG NEGATIVE NUMBERS pattern using java programming language.

import java.util.*;
public class Main
{
	public static void main(String[] args) {
	    Scanner sc=new Scanner(System.in);
	    int n=sc.nextInt();
	    int a[]=new int[n];
	    for(int i=0;i<n;i++){
	        a[i]=sc.nextInt();
	        }
	         int b=a[0];
	   for(int i=1;i<n;i++){
	       if(a[i]>b)
	       {
	           b=a[i];
	           
	       }}
	       System.out.println(b);
		}
}
