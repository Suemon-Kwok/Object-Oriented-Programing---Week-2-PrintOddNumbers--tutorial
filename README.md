/*
Object oriented programming Lab 2 question 4

Complete the main method in the PrintOddNumbers class by using a for loop to print the odd numbers between 21 to 39 (inclusive) on separate lines of the console
For example:
Test	Result
PrintOddNumbers.main(new String[]{})	21
23
25
27
29
31
33
35
37
39

Starter code
public class PrintOddNumbers
{
    public static void main(String[] args)
    {
       
    }
}
*/
public class PrintOddNumbers 
{
	public static void main(String[] args)
	{
		for (int i = 21; i <= 39; i += 2) //iterate starting at 21 +2 using for loop 
		{
			System.out.println(i); // print
				
		}	
	}
}
