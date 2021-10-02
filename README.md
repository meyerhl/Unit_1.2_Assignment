# Unit_1.2_Assignment

/*The purpose of this assignment is to loop through a defined string
*variable to get a count of vowels and display the final count to
*the user. 
*
*Program needs to contain a string variable, a vowel counter 
*variable, a conversion to lower case (in instances where upper
*case might be used), and a for loop for undertermined length
*of string.
*/
public class LoopCode { 
  public static void main(String[] args) { 
    String book = "revelation"; 
    book = book.toLowerCase(); 
    int vCounter= 0; 
      for (int i=0; i<book.length(); i++) { 
        char ch = book.charAt (i); 
        if(ch == 'a'||ch =='e'||ch=='i'||ch=='o'||ch=='u') { 
          vCounter++; 
        } 
    } 
    System.out.println("Count of vowels in string: " +vCounter); 
  } 
}
