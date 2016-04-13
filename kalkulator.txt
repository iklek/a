#include<stdio.h>

#include<string.h>

#include<math.h>

char line[1000];

main()

{

char operator;

float value1, value2;

float result;

printf("Witaj w kalkutorze 4-funkcyjnym\n\n");

printf("Podaj pierwsza liczbe, operator dzialania i druga liczbe: \n");

fgets(line, sizeof(line), stdin);

sscanf(line, "%f %c %f",&value1, &operator, &value2);

switch(operator)

{

case'+':

{

result=value1 + value2;

}

break;

case'-':

{

result=value1 - value2;

}

break;

case'*':

{

result=value1 * value2;

}

break;

case'/':

{

if(value2 == 0)

{

printf(" Pamietaj cholero, nie dziel przez zero\n\n");

printf(" Dzialanie nie zostalo wykonane.\n");

exit(1);

}

result=value1 / value2;

}

break;

default:

{

printf("Niewlasciwie wprowadzone dane.\nTry again:)\n");

exit(1);

}

}

printf("Wynik dzialania %c wynosi: %.3f\n\n", operator, result);

return(0);

}