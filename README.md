# GROUP NAME-ERUDITES
NAMES;
1.BWIRE TIMOTHY TAAKA 
2.OTIM EMMANUEL
3.KAINEMBABAZI TRUST
4.PRIMAH JENEROUS
5.MONALISA ADUT MAJOK WEL
#include <stdio.h>

int main() {
    // Declare variables to store the marks for each test for three subjects
    float maths[4], physics[4], chemistry[4];
    float mathsAverage, physicsAverage, chemistryAverage;
    float mathsTotal, physicsTotal, chemistryTotal;

    // Input marks for Maths
    printf("Enter marks for Maths:\n");
    printf("Assignment: ");
    scanf("%f", &maths[0]);
    printf("Coursework: ");
    scanf("%f", &maths[1]);
    printf("Mid-term: ");
    scanf("%f", &maths[2]);
    printf("End of Term: ");
    scanf("%f", &maths[3]);

    // Input marks for Physics
    printf("\nEnter marks for Physics:\n");
    printf("Assignment: ");
    scanf("%f", &physics[0]);
    printf("Coursework: ");
    scanf("%f", &physics[1]);
    printf("Mid-term: ");
    scanf("%f", &physics[2]);
    printf("End of Term: ");
    scanf("%f", &physics[3]);

    // Input marks for Chemistry
    printf("\nEnter marks for Chemistry:\n");
    printf("Assignment: ");
    scanf("%f", &chemistry[0]);
    printf("Coursework: ");
    scanf("%f", &chemistry[1]);
    printf("Mid-term: ");
    scanf("%f", &chemistry[2]);
    printf("End of Term: ");
    scanf("%f", &chemistry[3]);

    // Calculate totals for each subject
    mathsTotal = maths[0] + maths[1] + maths[2] + maths[3];
    physicsTotal = physics[0] + physics[1] + physics[2] + physics[3];
    chemistryTotal = chemistry[0] + chemistry[1] + chemistry[2] + chemistry[3];

    // Calculate averages for each subject
    mathsAverage = mathsTotal / 4;
    physicsAverage = physicsTotal / 4;
    chemistryAverage = chemistryTotal / 4;

    // Output the average marks for each subject
    printf("\nAverage Marks for the student:\n");
    printf("\nMaths: %.2f\n", mathsAverage);
    printf("Physics: %.2f\n", physicsAverage);
    printf("Chemistry: %.2f\n", chemistryAverage);

    return 0;
}
 


# ASSIGNMENT 02 

#include <stdio.h>

int main() {
    int N, X;

    // Get the number of domestic animals
    printf("Enter the number of domestic animals: ");
    scanf("%d", &N);
    char domestic[N] [10];

    printf("Enter %d domestic animals:\n", N);
    for (int i = 0; i < N; i++) {
        scanf("%s", domestic[i]);
    }

    // Get the number of wild animals
    printf("Enter the number of wild animals: ");
    scanf("%d", &X);
    char wild[X] [10];

    printf("Enter %d wild animals:\n", X);
    for (int i = 0; i < X; i++) {
        scanf("%s", wild[i]);
    }

    // Print all animals
    printf("\nList of all animals:\n");
    for (int i = 0; i < N; i++) {
        printf("%s\n", domestic[i]);
    }
    for (int i = 0; i < X; i++) {
        printf("%s\n", wild[i]);
    }

    return 0;
}

