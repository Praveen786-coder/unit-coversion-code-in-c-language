// Online C compiler to run C program online
#include <stdio.h>

int main() {
    char input;
    float kmsToMiles=0.621371;
    float inchesTofoot=0.0833333;
    float cmsToinches=0.393701;
    float poundTokgs=0.453592;
    float inchesToMeters=0.0254;
    float first,second;
    while(1)
    {
        printf("Enter the input character. q to quite\n 1.kmsToMiles\n 2.inchesTofoot\n  3.cmsToinches\n 4.poundTokgs\n  5.inchesToMeters\n");
        scanf("%c",&input);
        switch(input)
        {
            printf("Quite");
            case 'q':
            goto end;
            
            case '1':
             printf("enter quantity in terms of first unit\n ");
             scanf("%f",&first);
            second = first*kmsToMiles;
            printf("%f kms is equal to %fmiles\n",first,second);
            break;
            
            case '2':
             printf("enter quantity in terms of first unit\n ");
        scanf("%f",&first);
            second = first*inchesTofoot;
            printf("%f inchesis equal to %ffoot\n",first,second);
            break;
            
            case '3':
             printf("enter quantity in terms of first unit\n ");
        scanf("%f",&first);
            second = first*cmsToinches;
            printf("%f cms is equal to  %finches\n",first,second);
            break;
            
            case '4':
             printf("enter quantity in terms of first unit\n ");
        scanf("%f",&first);
            second = first*poundTokgs;
            printf("%f pounds is equal to %fkgs\n",first,second);
            break;
            
            case '5':
             printf("enter quantity in terms of first unit\n ");
        scanf("%f",&first);
            second = first*inchesToMeters;
            printf("%f inches is equal to %f meters\n",first,second);
            break;
            default:
            break;
            
        }
    }
   end:
   return 0;
}
