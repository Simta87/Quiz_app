// Fibnoacci series

//0 1 1 2 3 5 8 13 21 34 55


public class Fibnoacci {

  public static void main(String[] args) {

  	 int n = 6;

  	System.out.println(fibnoacci(n));

  }

  private static long fibnoacci(int n){
  	
  	if(n <= 1){
  		return n;
  	}

  	fibnoacci(n) = fibnoacci(n-1) + fibnoacci(n-2);

  	return fibnoacci(n);

  }
	
}
