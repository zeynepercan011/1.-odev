# 1.-odev

//verilen say�n�n fakt�riyelini bulan kod

#include<stdio.h>
int fact(int);
int main(void)
{
	int x;
	printf("bir sayi giriniz:");
	scanf("%d" , &x);
	
	printf("faktoriyeli: %d" , fact(x));
	
	return 0;
}

int fact(int x)
{
	int sonuc=1;
	
	for(int i=1;i<=x;i++)
	{
		sonuc*=i;
	}
	
	return sonuc;
}
