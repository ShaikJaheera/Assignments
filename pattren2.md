to prnt the given pattren
+--------------------+
|                    |
|                    |
|                    |
|                    |
|                    |
|           Jaheera  |
|                    | 
+--------------------+


     String name;
  name is declared as string data type
  
		Scanner sc=new Scanner(System.in);
  scanner to take input from the user  
  
		System.out.println("enter the name:");
  to enter the name during runtime
  
		name=sc.next();    
  to read the characers
  
		int l;
  l is declared as int data type
  
		l=name.length(); 
  to record the length of the give string
   
		int nl=l+3;
    int nll=22-nl;  
   n1 and n2 are declared
   
      if(i==1||i==9)
			{
				System.out.println("+--------------------+");
			}
  i==1 and i==9 it prints the following pattren if the condition is false then it enters into else part
  
  
       else
			 {
				  for(int j=1;j<23;j++)
				  {
				  	if(j==1||j==22) 
					  {
					  	System.out.print("|");
					  }
  it itterates the loop till j<23 if the condition is met then enters into else part
  if j==1 or j==22 the  "|" this will be priinted if not it enters into else part
  
					else
					{
	
						if(i==3 && j==nll+1)
						{
							System.out.print(name+"  "+"|");
							break;	
						}
   if i==3 and j==n11+1 then it prints the name and then 2 spaces will be given and then "|"
   then the condition breaks
   
  
            else
						{
				
							System.out.print(" ");
						}
  
  if condition fails it gives spaces
  
  
  output:
  enter the name:
  Jaheera
  i=1
  checks if condition
  1==1 
  prints +--------------------+
  
 i=2
 checks if condition
 2==1 false
 enters into else part
 j=1 1<23 enters into if part
 if(j==1||j==22) 
 1==1 , prints |
 2==1 false  j is incremented, 
 3==1 false  j is incremented,.... 
 22=22  , prints|
 
 i=3
 checks if condition
 3==1 false
 enters into else part
 j=1 1<23 enters into if part
 if(j==1||j==22) 
 1==1 , prints |
 2==1 false  j is incremented, 
 3==1 false  j is incremented,.... 
 22=22  , prints|
 
 i=4
 checks if condition
 4==1 false
 enters into else part
 j=1 1<23 enters into if part
 if(j==1||j==22) 
 1==1 , prints |
 2==1 false  j is incremented, 
 3==1 false  j is incremented,.... 
 22=22  , prints|
 
 i=5
 checks if condition
 5==1 false
 enters into else part
 j=1 1<23 enters into if part
 if(j==1||j==22) 
 1==1 , prints |
 2==1 false  j is incremented, 
 3==1 false  j is incremented,.... 
 22=22  , prints|
 
 i=6
 checks if condition
 6==1 false
 enters into else part
 j=1 1<23 enters into if part
 if(j==1||j==22) 
 1==1 , prints |
 2==1 false  j is incremented, 
 3==1 false  j is incremented,.... 
 22=22  , prints|
 
 i=7
 checks if condition
 2==1 false
 enters into else part
 j=1 1<23 enters into if part
 
 
    if(i==3 && j==nll+1)
     {
							System.out.print(name+"  "+"|");
							break;	
     }
leavening 3 colums space the name is printed

 i=8
 checks if condition
 8==1 false
 enters into else part
 j=1 1<23 enters into if part
 if(j==1||j==22) 
 1==1 , prints |
 2==1 false  j is incremented, 
 3==1 false  j is incremented,.... 
 22=22  , prints|

  i=9
  checks if condition
  9==9 
  prints +--------------------+
 
+--------------------+
|                    |
|                    |
|                    |
|                    |
|                    |
|           Jaheera  |
|                    | 
+--------------------+
 
 
 
 
 
  
  
  
