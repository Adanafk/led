# led
#include <stdio.h>
int main ()
{
    int led;
    float R;

    printf ("escoje un numero deacuerdo al led que elijas\n1=rojo std\n2=verde std\n3= azun brillante\n ");
    scanf("%d",& led );
    if (led==1)
    {
        R= 1.5/0.015 ;
        printf ("el valor de la resitencia es  %f\n ", R );

    } else
    if (led==2)
    {
        R= 1.8/0.015 ;
         printf ("el valor de la resitencia es  %f\n ", R );
    } else
    if (led==3)
    {
      R= 3/0.2 ;
       printf ("el valor de la resitencia es  %f\n ", R );

    }
}
