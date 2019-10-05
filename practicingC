#include <stdio.h>

int main()
{
   int i , j , m , n ,u , v , k , l;
   int mat1[10][10] , mat2[10][10] , mulMat[10][10];
   
   printf("enter order of first matrix\n");
   scanf("%d%d" , &m,&n);
   printf("enter order of second matrix\n");
   scanf("%d%d" , &u,&v);
   
   printf("enter first matrix\n");
   for (i = 0 ; i<m ; i++) {
       for(j = 0 ; j<n ; j++) {
        scanf("%d",&mat1[i][j]);
       }
   }
   printf("enter second matrix\n");
   for (i = 0 ; i<u ; i++) {
       for(j = 0 ; j<v ; j++) {
        scanf("%d",&mat2[i][j]);
       }
   }
   
   for (i = 0 ; i<m ; i++)
   {
       for(j = 0 ; j<v ; j++)
       mulMat[i][j] = 0 ;
   }
   
   if (n == u)
   {
       for (i = 0 ; i<m ; i++)
       {
           for (j = 0 ; j<v ; j++)
           {
               for (k = 0 ; k<n ; k++)
               {
                   mulMat[i][j] += mat1[i][k] * mat2[k][j] ;
               }
           }
       }
   }
   else
        printf("multiplication not possible");
       
    printf("The resulting matrix is: \n");    
    
   for (k = 0 ; k<m ; k++)
   {
       for(l = 0 ; l<v ; l++)
       printf("%d ",mulMat[k][l]);
       printf("\n");
       
   }
   

    return 0;
}
