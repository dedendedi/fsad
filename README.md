# fsad#include <stdio.h>
#include <conio.h>#include <stdio.h>
#include <conio.h>
#include <math.h>

void main()
{
	float a, b, c, d;
	clrscr();
	printf("Nhap cac he so a, b, c : ");
	scanf("%f%f%f", &a, &b, &c);
	if (a)
	{
		d = b *b - 4 *a * c;
		if (d < 0) printf("Vo nghiem !");
		if (d == 0) printf("Nghiem kep x=%4.2f", -0.5 *b / a);
		if (d > 0)
		{
			printf("Hai nghiem phan biet :\n");
			printf("x1=%4.2f", 0.5 *(-b - sqrt(d)) / a);
			printf(" x2=%4.2f", 0.5 *(-b + sqrt(d)) / a);
		}
	}
	else if (b) printf("Mot nghiem x=%4.2f", -c / b);
	else if (c) printf("Vo nghiem !");
	else printf("Vo so nghiem !");
	getch();
}
	clrscr();
	printf("Nhap cac he so a, b, c : ");
	scanf("%f%f%f", &a, &b, &c);
	if (a)
	{
		d = b *b - 4 *a * c;
		if (d < 0) printf("Vo nghiem !");
		if (d == 0) printf("Nghiem kep x=%4.2f", -0.5 *b / a);
		if (d > 0)
		{
			printf("Hai nghiem phan biet :\#include <stdio.h>
#include <conio.h>
#include <math.h>

void main()
{
	float a, b, c, d;
	clrscr();
	printf("Nhap cac he so a, b, c : ");
	scanf("%f%f%f", &a, &b, &c);
	if (a)
	{
		d = b *b - 4 *a * c;#include <stdio.h>
#include <conio.h>
#include <math.h>

void main()
{
	float a, b, c, d;
	char doc[9][5] = { "mot", "hai", "ba", "bon", "nam", "sau", "bay", "tam", "chin" };
	int van, ngan, tram, chuc, donvi, chv, dv;
	long so;
	clrscr();

	cout << "Nhap so nguyen duong < 1000000 can doc = ";
	cin >> so;
	cout << "Cach doc so " << so << " la:\n";

	van = so / 10000;
	ngan = so / 1000 % 10;
	tram = so / 100 % 10;
	chuc = so / 10 % 10;
	donvi = so % 10;

	if (van)
	{
		chv = van / 10;
	clrscr();
	printf("Nhap cac he so a, b, c : ");
	scanf("%f%f%f", &a, &b, &c);
	if (a)
	{
		d = b *b - 4 *a * c;
		if (d < 0) printf("Vo nghiem !");
		if (d == 0) printf("Nghiem kep x=%4.2f", -0.5 *b / a);
		if (d > 0)
		{
			printf("Hai nghiem phan biet :\n");
			printf("x1=%4.2f", 0.5 *(-b - sqrt(d)) / a);
			printf(" x2=%4.2f", 0.5 *(-b + sqrt(d)) / a);
		}
	}
	else if (b) printf("Mot nghiem x=%4.2f", -c / b);
	else if (c) printf("Vo nghiem !");
	else printf("Vo so nghiem !");
	getch();
}
		if (d < 0) printf("Vo nghiem !");
		if (d == 0) printf("Nghiem kep x=%4.2f", -0.5 *b / a);
		if (d > 0)
		{
			printf("Hai nghiem phan biet :\n");
			printf("x1=%4.2f", 0.5 *(-b - sqrt(d)) / a);
			printf(" x2=%4.2f", 0.5 *(-b + sqrt(d)) / a);
		}
	}
	else if (b) printf("Mot nghiem x=%4.2f", -c / b);
	else if (c) printf("Vo nghiem !");
	else printf("Vo so nghiem !");
	getch();
}, -c / b);
	else if (c) printf("Vo nghiem !");
	else printf("Vo so nghiem !");
	getch();
}
