#include <stdio.h>
#include <string.h>

#define PASSWORD "aeiceg" 

int main() {
    char matrix[3][3];
    char diagonal[5]; 
    printf("Enter 3x3 matrix:\n");
    for(int i=0; i<3; i++) {
        for(int j=0; j<3; j++) {
            scanf(" %c", &matrix[i][j]);
        }
    }
    diagonal[0] = matrix[0][0];
    diagonal[1] = matrix[1][1];
    diagonal[2] = matrix[2][2];
    diagonal[3] = matrix[0][2];
    diagonal[4] = matrix[2][0];
    diagonal[5] = '\0';
    if(strcmp(diagonal, PASSWORD) == 0) {
        printf("Password matched!\n");
    } else {
        printf("Incorrect password\n");
    }

    return 0;
}
