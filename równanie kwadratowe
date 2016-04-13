#include "stdio.h"
#include "conio.h"
#include "math.h"

int main()
{
        char wybor;
        double a,b,c,delta,x,z;
        do
        {
                //clrscr();
                printf("\n Rozwiazywanie rownania kwadratowego \n\n");
                do
                {
                        printf(" Podaj a: \n a = ");
                        z=scanf("%lf",&a);
                        fflush(stdin);
                        }
                while(z==0);
                do
                {
                        printf(" Podaj b: \n b = ");
                        z=scanf("%lf",&b);
                        fflush(stdin);
                }
                while(z==0);
                do
                {
                        printf(" Podaj c: \n c = ");
                        z=scanf("%lf",&c);
                        fflush(stdin);
                }
                while(z==0);
                if(a==0)
                        if(b==0)
                                if(c==0)
                                        printf("\n Rownanie samoistne.");
                                else
                                        printf("\n Podane wspolczynniki tworza sprzecznosc.");
                        else
                        {
                                x=-c/b;
                                printf("\n Rownanie jest rownaniem liniowym.");
                                printf("\n Jego rozwiazaniem jest \n X = %lf ",x);
                        }
                else
                {
                        delta=b*b-4*a*c;
                        if(delta==0)
                        {
                                x=-b/(2*a);
                                printf("\n Rownanie posiada jedno rozwiazanie: \n X0 = %lf",x);
                        }
                        else
                                if(delta > 0)
                                {
                                        printf("\n Rownanie posiada dwa rozwiazania:");
                                        x=(-b-sqrt(delta))/(2*a);
                                        printf("\n X1 = %lf",x);
                                        x=(-b+sqrt(delta))/(2*a);
                                        printf("\n X2 = %lf",x);
                                }
                                else
                                {
                                        delta=fabs(delta);
                                        printf("\n Rownanie posiada dwa pierwiastki zespolone:");
                                        printf("\n X1 = %lf + j%lf",-b/(2*a),sqrt(delta)/(2*a));
                                        printf("\n X2 = %lf - j%lf",-b/(2*a),sqrt(delta)/(2*a));
                                }
                }
                printf("\n\n Czy chcesz kontynuowac?");
                printf("\n T - Tak N - Nie \n ");
                do
                        wybor=getch();
                while(wybor!='T'&&wybor!='t'&&wybor!='N'&&wybor!='n');
        }
        while(wybor=='T'||wybor=='t');
        return 0;
}
