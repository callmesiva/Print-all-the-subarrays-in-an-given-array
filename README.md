# Print-all-the-subarrays-in-an-given-array
 
      int arr[]= {1,2,3,4,5};
      
      
      for(int i=0; i<arr.length; i++)   // increse one by one to end of the array
      {
        for(int j=i; j<arr.length; j++)    // i to end of the array
        {
          for(int k=i; k<=j; k++)          // i to j
          {
            
            System.out.print(arr[k]);
          
          }
          System.out.println();
        }
      }
 

