# challenges-sas-s1
int stair = n-1;
    
    for (int i = 0; i < n; ++i){
        for (int j = 0; j < n; ++j){
            if (j >= stair){
                printf("#");
            } else{
                printf(" ");
            }
        }
        stair -= 1;
        printf("\n");
