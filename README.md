# challenges-sas-s1
int max = candles[0];
    int cand = 0;


    for(int i=0;i<candles_count; i++) {
        if(candles[i] > max) {
            max = candles[i];
        }        
    }
    for (int i=0;i<candles_count;i++) {
        if(candles[i]==max) {
            cand++;
        }            
    }
    return cand;
    
