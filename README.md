# Unit_1.2_Assignment
//create loop that counts vowels from string

public class TestCode {
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
