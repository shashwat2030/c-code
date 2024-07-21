#include <stdio.h>
#include <stdlib.h>

int main()
{
    int ar[20],s,i,d,j;
    printf("enter array size");
    scanf("%d",&s);
    printf("enter elements for array");
    for (i=1;i<=s;i++)
    {

        scanf("%d",&ar[i]);
    }
    printf("enter prefer index:");
    scanf("%d",&j);
m=j;
while(m<=s-1)
{

    a[m]=a[m+1];
    m++;
}
s=s-1;
printf("array after deletion:\n");
for(c=0;c<=s;c++)
{

    printf("%d\n"a[i]);
}
 return 0;
}

