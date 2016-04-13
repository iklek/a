#include <stdio.h>
#include <conio.h>
#include <math.h>
void wyznaczanie(int liczba)
{
        int cyfra,wielokrotnosc;
        if(liczba<0)
                printf("\n minus");
        liczba=abs(liczba);
        for(wielokrotnosc=1;wielokrotnosc*10<liczba;wielokrotnosc*=10);
                do
                {
                        cyfra=liczba/wielokrotnosc;
                        switch(cyfra)
                        {
                                case 0:
                                        printf(" zero"); break;
                                case 1:
                                        printf(" jeden"); break;
                                case 2:
                                        printf(" dwa"); break;
                                case 3:
                                        printf(" trzy"); break;
                                case 4:
                                        printf(" cztery"); break;
                                case 5:
                                        printf(" piec"); break;
                                case 6:
                                        printf(" szesc"); break;
                                case 7:
                                        printf(" siedem"); break;
                                case 8:
                                        printf(" osiem"); break;
                                case 9:
                                        printf(" dziewiec"); break;
                        }
                        liczba=liczba-cyfra*wielokrotnosc;
                        wielokrotnosc/=10;
                }
                while(wielokrotnosc>0);
}
main()
{
        int liczba;
        printf("\n Podaj liczbe: \n ");
        scanf("%d",&liczba);
        wyznaczanie(liczba);
        getch();
        return 0;
}
