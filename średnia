#include <stdio.h>
#include <conio.h>
main()
{
        void wczyt(int [],int );
        int srednia(int [],int );
        int a[10],b[10];
        int i,n,d;
        printf("\n Podaj ilosc elementow tablic a i b. \n n = ");
        scanf("%d",&n);
        printf("\n Podaj elementy tablicy a. \n");
        wczyt(a,n);
        printf("\n Podaj elementy tablicy b. \n");
        wczyt(b,n);
        printf("\n Wczytales nastepujace elementy: \n");
        for(i=0;i<n;i++)
                printf("\n a[%d] = %d",i,a[i]);
        d=srednia(a,n);
        printf("\n Srednia wartosc a = %d",d);
        printf("\n");
        for(i=0;i<n;i++)
                printf("\n b[%d] = %d",i,b[i]);
        d=srednia(b,n);
        printf("\n Srednia wartosc b = %d",d);
        getch();
        return 0;
}
void wczyt(int c[],int n)
{
        int i;
        for(i=0;i<n;i++)
        {
                printf("\n element[%d] = ",i);
                scanf("%d",&c[i]);
        }
}
int srednia(int c[],int n)
{
        int i,z=0;
        for(i=0;i<n;i++)
                z=z+c[i];
        z=z/n;
        return z;
}
