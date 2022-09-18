# Age-vs-Marks

#include <stdio.h>

int main() {
int main()
{
    int age,weight; 
    printf("Enter Your age\n");
    scanf("%d", &age);
    
    printf("Enter Your weight\n");
    scanf("%d", &weight);

    switch (age)
    {
    case 18:
        printf("The age is 18\n");
        switch (weight)
        {
        case 55:
            printf("You are eligible for Army Training.");
            break;
        
        default:
            printf("You are not elibible for Army Training.");
            break;
        }
        break;
    case 22:
        printf("The age is 22\n");
         switch (weight)
        {
        case 60:
            printf("You are eligible for Army Training.");
            break;
        
        default:
            printf("You are not elibible for Army Training.");
            break;
        }
        break;
    case 24:
        printf("The age is 23\n");
         switch (weight)
        {
        case 65:
            printf("You are eligible for Army Training.");
            break;
        
        default:
            printf("You are not elibible for Army Training.");
            break;
        }
        break;

    default:
       printf("Your Age is not 18,22 and 24.\n");
        break;
    }   
    return 0;
}
