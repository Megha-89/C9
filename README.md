# C9
Mirror of triangle #include<stdio.h>
int main()
{
 int i,n,j;
 printf("enter the row of matrix:");
 scanf("%d",&n);
 for( int i=n;i>=1;i--){
 for( int j=1;j<=i;j++){
 if(j==1||j==i||i==n){
 printf ("* ");
 }
 else
 {
 printf(" ");
 }
 }
 printf ("\n");
 }
 return 0;
 }
 
