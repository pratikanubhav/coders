#include<Stdio.h>
#include<math.h>
main()
{
	/*palindrome of a number*/
	int x=0,y=0,z=0;
	printf("Enter the number\n");
	scanf("%d",&x);
	
	y=x;
	while(y!=0)
	{
	
	z = z*10;
	z = z+y%10;
	y=y/10;
    }
	printf("%d",z);
	 
}
