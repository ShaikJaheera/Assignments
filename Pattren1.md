# Assignments / Pattren.java
To output the pattren
        *
       * *
      *   *
     *     *
    *********     
    
    
    Scanner sc = new Scanner(System.in);

to take input from the user scanner is used
 
    System.out.println("Enter the number of rows: ");

user has to enter the number of rows they want
 
    int rows = sc.nextInt();

to read the rows


        for (int i=1; i<= rows ; i++)
        {
    To itterate the loop till i<=rows condition met.



        for (int j = i; j < rows ; j++)
        {
            System.out.print(" ");
        }
Ths part of the code is used to print the spaces, if j=i; j<rwos means if the j value is equal to i and
j is less than rows it gives spaces, if the condition fails it comes out of loop and enters into the next loop


        for (int k = 1; k <= (2*i -1) ;k++) 
        {
                    if( k==1 || i == rows || k==(2*i-1)) 
                    {
                        System.out.print("*");
                    }
                    else
                    {
                        System.out.print(" ");
                    }
        }
        
  This part is for printing the *, here if k = 1 and k<=(2*i-1) if this condition is true then it enter into the if statement
  k==1, i==rows and k==(2*i-1) if any one the condition is true it prints * , if not it enters into else part  and gives space
  
  output:
  enter the number of rows:
  5
  then it checks the condition
  for i=1;
  i=1; 1<=5 its true, then enters into j loop for printing spaces
  
  j=1, 1<5, true it gives space
  j=2, 2<5, space is given
  j=3, 3<5, space is given 
  j=4, 4<5, space is given
  j=5, 5<5, condition is false comes out of loop it prints 4 spaces
  enters into k loop
  
  k=1, k<=(2*1-1)=1 k=1 then it checks for if condition
  
  k==1, 1==1 condition is true
  it prints *
      *
  
  
  
  for i=2;
  i=2; 2<=5 its true, then enters into j loop for printing spaces
  
  j=2, 2<5, true it gives space
  j=3, 3<5, space is given 
  j=4, 4<5, space is given
  j=5, 5<5, condition is false comes out of loop, it prints 3 spaces
  
  enters into k loop
  k=1, k<=(2*1-1)=1 k=1 then it checks for if condition
  i==rows, 2==2 condition is true
  it prints * then space then *
     * *
  
  
    
  for i=3;
  i=3; 3<=5 its true, then enters into j loop for printing spaces
  
  j=3, 3<5, true it gives space
  j=4, 4<5, space is given
  j=5, 5<5, condition is false comes out of loop, it prints 2 spaces
  
  enters into k loop
  k=1, k<=(2*1-1)=1 k=1 then it checks for if condition
  i==rows, 3==3 condition is true
  it prints * then 2 space then *
    *  *

  for i=4;
  i=4; 4<=5 its true, then enters into j loop for printing spaces
  
  j=4, 4<5, true it gives space
  j=5, 5<5, condition is false comes out of loop, it prints 2 spaces
  
  enters into k loop
  k=1, k<=(2*1-1)=1 k=1 then it checks for if condition
  i==rows, 4==4 condition is true
  it prints * then 3 space then *
   *   *

  for i=5;
  i=5; 5<=5 its true, then enters into j loop for printing spaces
  

  j=5, 5<5, condition is false comes out of loop, it prints 2 spaces
  
  enters into k loop
  k=1, k<=(2*5-1)=1 k=9 then it checks for if condition
  i==rows, 5==5 condition is true
  it prints 9 * without spaces
  
        *
       * *
      *   *
     *     *
    *********   
  
  
        
        
        
        
        
        
