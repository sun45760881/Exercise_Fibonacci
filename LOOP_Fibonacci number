#include <stdio.h> 
#include <stdlib.h> 

int main(void) {
	int n;
	printf("Fib(N)   n=?");
	scanf("%d", &n);
	for (int i = 0; i <= n; i++)
	{
		printf("%d\n", Fib(i));
	}
}

int Fib(int n)
{
	if (n == 0 || n == 1)
	{
		return n;
	}
	else
	{
		int a = 0, b = 1, c, i;
		for (i = 2; i<= n; i++)
		{
			c = a + b;
			a = b;
			b = c;
		}
		return c;
	}

}
