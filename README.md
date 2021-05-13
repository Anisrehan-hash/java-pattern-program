# java- star-pattern-program
-> Aim is to creat star pattern(traingular shape) program
1. creat class 
2. creat main method
   -> public static void main(String[] args)
   -> main method is required because the execution starts from main method.
3. To print space
   -> First itterate using for loop to set number of rows
          for(int i=0;i<=3;i++)
          In this case number of rows is 3.
   -> For printing space using formula "n-i"
          n=number of rows
          i is used to itterate the rows.
          j is used to itterate the columns.
   -> The logic behind n-i is when the number of rows increase then space will decrease
		     	for(int j=1;j<=3-i;j++)
		    	{
				    System.out.print(" ");
		    	}  
4. To print star("*")
   -> For printing star using formula "2*i-1" and itterate using for loop because number of star increases wrt number of rows.
          for(int j=1;j<=2*i-1;j++)
			    {
				     System.out.print("*");
		     	}
 5. To move the cursor next line 
          System.out.println();
