# Prime-or-Not
Java program to check whether the given number is Prime or Not
import java.util.Scanner; 
class PrimeCheck 
{ 
     public static void main(String args[]) 
     {		 
        	int temp; 	  
        	Scanner scan= new Scanner (System.in); 	
        System.out.println("Enter a number:");              	
        int num=scan.nextInt();   
      	for(int i=2;i<=num/2;i++) 	
       { 
          temp=num%i; 	
          if(temp==0) 	 
          { 
               isPrime=false; 	 
               break; 	 
          } 	 
         } 	
          	if(isPrime) 	 
                 System.out.println(num+ "Is a Prime");           
          else 
        	        System.out.println(num + " is not a Prime Number"); 
        }  
}
