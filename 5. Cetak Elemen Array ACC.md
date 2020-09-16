# Cetak Elemen Array
Rancang sebuah program untuk mencetak elemen-elemen array untuk indeks yang diberikan.

### Format Masukan
Masukan berupa dua baris. Baris pertama terdiri atas maksimal 80 karakter yang diakhiri dengan newline. Baris kedua terdiri atas indeks array yang harus dicetak, pembacaan indeks berakhir jika bertemu indeks -1.

### Format Keluaran
Keluaran berupa satu baris yang terdiri atas elemen-elemen array untuk indeks yang diberikan. Keluaran diakhiri dengan newline.

### Contoh Masukan
```
ilmu komputer
0 1 5 6 7 -1
```

### Contoh Keluaran
```
ilkom
```

### Code
```
#include<stdio.h>
#define SIZE 80
 
int main(){
    int i;
    char a[SIZE];
     
    scanf("%[^\n]c", &a);
    scanf("%d", &i);
     
    while(i!=-1){
        printf("%c", a[i]);
        scanf("%d", &i);
    }
    printf("\n");
    return 0;
}
```
