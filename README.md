import java.util.*;
public class Matrixadd {


	public static void main(String[] args) {
		Scanner in=new Scanner(System.in);
		// TODO Auto-generated method stub
          int r,c,i,j;
          System.out.println("Enter the number of rows");
          r=in.nextInt();
          System.out.println("Enter the number of columns");
          c=in.nextInt();
          int a[][]=new int[r][c];
          int b[][]=new int[r][c];
          int mat[][]=new int[r][c];
          for(i=0;i<r;i++)
          {
        	  for(j=0;j<c;j++)
        	  {
        		  System.out.println("enter the elements of 1 matrix");
        		  a[i][j]=in.nextInt();

        	  }
          }
          for(i=0;i<r;i++)
          {
        	  for(j=0;j<c;j++)
        	  {
        		  System.out.println("enter the elements of 2 matrix");
        		  b[i][j]=in.nextInt();

        	  }
          }
          for(i=0;i<r;i++)
          {
        	  for(j=0;j<c;j++)
        	  {

        		 mat[i][j]=a[i][j]+b[i][j];

        	  }
          }
          System.out.println("The sum of matrix ");
          for(i=0;i<r;i++)
          {
        	  for(j=0;j<c;j++)
        	  {

        		 System.out.print(mat[i][j]+" \t");
        	  }
        	  System.out.println( );
          }
	}

}
