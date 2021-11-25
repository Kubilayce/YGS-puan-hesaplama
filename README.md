# YGS-puan-hesaplama

#include <stdio.h>
#include <stdlib.h>

/* run this program using the console pauser or add your own getch, system("pause") or input loop */

int main() {
	
	
	
//Ygs 1 Puan Hesaplama
//türkçe : 1.999
//matematik : 3.998
//sosyal : 1
//fen : 2.999
//Taban: 100.600

float turkce,matematik,sosyal,fen,taban,toplampuan;

taban=100.160;
printf("Turkce Netiniz: ");
scanf("%f",&turkce);

printf("Matematik Netiniz: ");
scanf("%f",&matematik);

printf("Sosyal Netiniz: ");
scanf("%f",&sosyal);

printf("Fen netiniz: ");
scanf("%f",&fen);

toplampuan=turkce*1.999+matematik*3.998+sosyal*1+fen*2.999+taban;
printf("YGS - 1 Toplam Sonucunuz: %f",toplampuan);
		
	return 0;
}
