# pre-activiinclude<stdio.h>

int main()
{
    char name;
    int age;
    printf("ENTER YOUR NAME:");
    scanf("%s",  &name) ;
    printf("AGE:") ;
    scanf("%d", &age);
    
    if(age<=18) {
           printf("\nyou are eligible for voting");
    }
    if(age>=17) {
           printf("\nyou are not eligible for voting");
    }
    else if{
           printf("\nInvalid age, please try again" ) 
    return 0;
}
