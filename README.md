#include<stdio.h>
int main(){
    int input;
    int NumberOfBoxFilled;
    int Total_number_in_a_match_box;
    int leftover;
  puts("Please Enter the total number of matches you have:");  
scanf("%d",&input);

puts("Please enter the size of the match box been filled in inchies");
scanf("%d",&Total_number_in_a_match_box);

NumberOfBoxFilled= input/Total_number_in_a_match_box;
printf("You wil fill up %d match box(s)\n",NumberOfBoxFilled);

leftover = input%Total_number_in_a_match_box;
printf("There will be %d matches left.",leftover);


return 0;
}
