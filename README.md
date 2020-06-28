# Clock-in-C-language


#include <stdio.h>
#include<time.h>

int main () {
__time_t currentTime;



while(1){

time(&currentTime);

printf("%s",ctime(&currentTime));

system("clear");

}
    return 0;
}
