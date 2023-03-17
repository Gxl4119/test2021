# test2021
#define _CRT_SECURE_NO_WARNINGS 1
#include<stdio.h>
/*
- 一元钱的兑换方案
*/
// 1 2 5 
int main()
{
	int a, b, c;
	for (a = 0; a <= 10; a++)
	{
		for (b = 0; b <= 5; b++)
		{
			for (c = 0; c <= 2; c++)
			{
				if (a * 1 + b * 2 + c * 5 == 10)
					printf("一角:%d,二角:%d,五角%d\n", a, b, c);
			}
		}
	}
	return 0;
}
