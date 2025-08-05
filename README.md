#hello world🫡
// Parking_prix
// If you want to know how much will you pay for parking your car
// ali kamal


#include <stdio.h>

int main() {
    char parking;
    int hours;
    int day;
    printf("if you parking your car more than 24h write\nA \n");
    printf("if you parking your car a letter than 24h write \nB \n");
    printf("if you parking your car in a week write \nC \n");
    scanf("%c",&parking);
    if (parking == 'A'){
        printf("how much hours do you use : ");
        scanf("%d",&hours);
        int prix24 = hours * 10;
        printf("you can pay %d dh",prix24);
    }else if (parking == 'B'){
        printf("it's free");
    }else if (parking == 'C'){
        printf("how much day do you use : ");
        scanf("%d",&day);
        int prixday = day * 100;
        printf("you can pay %d dh", prixday);
    }else {
        printf("error");
    }
