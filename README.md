#include<stdio.h>
int main(){
    int input;
    int NumberOfBoxFilled;
    int Total_number_in_a_match_box=20;
    int leftover;
  puts("Please Enter the total number of matches you have:");  
scanf("%d",&input);

NumberOfBoxFilled= input/20;
printf("You wil fill up %d match box(s)\n",NumberOfBoxFilled);

leftover = input%20;
printf("There will be %d matches left.",leftover);


return 0;
}
