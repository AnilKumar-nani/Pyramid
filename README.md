# Pyramid

My reqiurement is to print the pyramid. so that i took a outer for loop to get the number of rows

      int n =5;
      for(int i=0;i<n;i++)
      
after that i took a inner for loop to print the spaces

    for(int j=0;j<n-i-1;j++)
      {
        System.out.print(" ");
      }
and to print the * i took another for loop 

    for(int k=0;k<2*i+1;k++)
      {
        if((i==0)||(i==n-1))
        System.out.print("*");
to print the innner space and outer * 

    else
        {
          if((k==0)||(k==2*i))
          {
            System.out.print("*");
          }
          else
          System.out.print(" ");

        }
