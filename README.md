_____________________________________CODE_________________________________________
public class Methods2 {
	
	//******************* Create method to add two numbers *******************
	
	public void add(int a, int b)
	{
		int c = a+b;
		System.out.println("Addition of "+a+" and "+b+" is "+c);
	}
	
	//******************* Create method to check even or odd *******************
	 
	public void EvenOdd(int num)
	{
		if(num%2==0)
			System.out.println(num+" is even number");
		else
			System.out.println(num+" is odd number");
	}
	
	//******************* Create method to find square of number *******************
	
	public void square(int num)
	{
		System.out.println("Square of "+num+" is "+(num*num));
	}
	
	//******************* WAP for reverse an number 1234 --> 4321 *******************
	
	public void reverseNo(String num)
	{
		int i;
		System.out.print("reverse of "+num+" is --> ");
		for(i=num.length()-1; i>=0; i--) 
			System.out.print(num.charAt(i));
	System.out.println();	
	}
	
	//******************* WAP for Grade System using method *******************
	
	public void grades(int marks)
	{
		if(marks>=90 && marks<=100) {
			System.out.println("A Grade");
			}	
		else if(marks>=75 && marks<90) {
			System.out.println("B Grade");
		}
		else if(marks>=60 && marks<75) {
			System.out.println("C Grade");
		}
		else if(marks>=35 && marks<60) {
			System.out.println("D Grade");
		}
		else {
			System.out.println("You are fail");
		}
	}
	
	//******************* WAP for Calculator using method *******************
	
	public void calsi(int a, int b, String operation)
	{
		switch(operation) {
		
		case "Addition":
			System.out.println("You Choosen addition operation -->"+a+" + "+b+" = "+(a+b));
			break;
		case "Substraction":
			System.out.println("You Choosen Substraction operation -->"+a+" + "+b+" = "+(a-b));
			break;
		case "Multilication":
			System.out.println("You Choosen Multilication operation -->"+a+" + "+b+" = "+(a*b));
			break;
		case "Division":
			System.out.println("You Choosen Division operation --> "+a+" + "+b+" = "+(a/b));
			break;
		}
	}
	
	//******************* WAP for Find Cube *******************
	public void cube(int num)
	{
		System.out.println("Cube of "+num+" is "+(num*num*num));
	}

	//*************** WAP for print whole information related to u ****************
		public void info(String name, String education, String dob, String hobby)
		{
			
			System.out.println("My name is "+name);
			System.out.println("My Education is "+education);
			System.out.println("My date of birth is "+dob);
			System.out.println("My hobby is "+hobby);
		}
	
	public static void main(String args[])
	{
		Methods2 m = new Methods2();
		
		m.square(4);
		m.EvenOdd(10);
	    m.add(10, 20);
	    m.reverseNo("1234");
	    m.grades(82);
	    m.calsi(10, 20, "multiplication");
	    m.cube(3);
	    m.info("Soniya yadav", "Btech in CS", "19 may 2004", "music");
	   
	}
  _____________________________________OUTPUT_________________________________________

Square of 4 is 16
10 is even number
Addition of 10 and 20 is 30
reverse of 1234 is --> 4321
B Grade
Cube of 3 is 27
My name is Soniya yadav
My Education is Btech in CS
My date of birth is 19 may 2004
My hobby is music


}
