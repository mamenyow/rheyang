#include <stdio.h>


float calculateFee(int duration) {
    
    float fee = 20.0 * duration;
    return fee;
}

int main() {
    int duration;
    float fee;

    printf("--------------------------------------------------\n");
    printf("Welcome to the Rhea's Parking Lot!\n");
    printf("==================================================\n");
    printf("Please enter the duration of parking in hours: ");
    scanf("%d", &duration);

   
    if (duration <= 2) {
    printf("Free.\n");
    return 0;
    }

    
    fee = calculateFee(duration);

    
    printf("Parking fee: ₱%.2f\n", fee);
    printf("Please make a payment.\n");

   
    float payment;
    do {
    printf("Enter payment amount: ₱");
    scanf("%f", &payment);

       
    if (payment < fee) {
    printf("Insufficient payment. Please try again.\n");
    }
    } while (payment < fee);

   printf("==================================================\n");
    float change = payment - fee;
    printf("Payment successful!\n" );
    printf("Your change: ₱%.2f\n", change);

    printf("==================================================\n");
    printf("Thank you for using the Parking Lot System!\n");
    printf("--------------------------------------------------\n");

    return 0;
}
