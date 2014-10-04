tugas-hitung-volume
===================
#include <stdio.h>
#include <conio.h>
main(){
float pilihan, pilihan1, hasil ;
int menu;
printf ("Nama : Tias wahyu saputra\n");
printf ("NIM  : 3143111029\n");
printf ("Prodi: D3 ( MI )MANAGEMEN INFORMATIKA\n\n\n");
kembali :
printf("MENGHITUNG VOLUME KUBUS, SILINDER, DAN LUAS LINGKARAN\n\n\n");
printf("pilih salah satu :\n\n");
printf ("1. Volume Kubus\n");
printf ("2. Volume Silinder\n");
printf ("3. Luas Lingkaran\n\n");
printf ("masukkan pilihan : ");

scanf ("%d",&menu);

switch (menu) {
case 1:
printf ("masukkan panjang sisi kubus =");
scanf ("%f",&pilihan);
hasil =(pow(pilihan,3));
printf ("volume kubus adalah= %.2f",hasil);
break;

case 2:
printf ("masukkan panjang jari-jari lingkaran =");
scanf ("%f",&pilihan);
printf ("masukkan tinggi silinder =");
scanf ("%f",&pilihan1);
hasil =(3.14*pow(pilihan,2)*pilihan1);
printf ("volume silinder adalah= %.2f",hasil);
break;

case 3:
printf ("masukkan panjang jari-jari lingkaran =");
scanf ("%f",&pilihan);
hasil =(3.14*pow(pilihan,2));
printf ("luas lingkaran adalah= %.2f",hasil);
break;

default:
    printf("\n\jawaban anda salah,silahkan di coba kembali\n\n");
goto kembali;
}
getch ();
}
