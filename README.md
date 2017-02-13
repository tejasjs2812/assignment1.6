# assignment1.6
Que.1)Answer-using main method

import java.util.*;

public class acad {
	public static void main(String args[]){
		int n=12;
		int m=21;
		int c;
		c=n+m;
		System.out.println(c);
		
	}

}
 Que2).Answer-input provided by user
 
 import java.util.*;

public class acad {
	public static void main(String args[]){
		int n,m,c;
		Scanner sc=new Scanner(System.in);
		n=sc.nextInt();
		 m=sc.nextInt();
		c=n+m;
		System.out.println(c);
		
	}

}

Que3)Answer-Using sum method

import java.util.*;

public class acad {
	public static void main(String args[]){
		int n,m,c;
		Scanner sc=new Scanner(System.in);
		n=sc.nextInt();
		 m=sc.nextInt();
		 c=sum(n,m);
		System.out.println(c);
		
	}

	private static int sum(int n, int m) {
		int c=0;
		c=n+m;
		return c;
	}
	

}

 
 
