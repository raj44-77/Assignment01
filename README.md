# Assignment01#include <stdio.h>

int main () 

{

float eng,phy, chem, math, comp;

float total, average, percentage;

printf ("enter the marks of five subjects:\n") ;

scanf("%f%f%f%f%f", &eng, &phy, &chem, &math, &comp);

total=phy+eng+chem+math+comp;

percentage=(total/500.0) *100;

printf ("total marks=%.2f\n", total) ;

printf("percentage=%.2f", percentage) ;

return 0;

}
