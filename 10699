#include <stdio.h>
#include <time.h>

int main(void) {
    time_t t;
    struct tm *tm_info;

    time(&t);              
    t += 9 * 60 * 60;        
    tm_info = gmtime(&t);    

    printf("%04d-%02d-%02d\n",
           tm_info->tm_year + 1900, 
           tm_info->tm_mon + 1,     
           tm_info->tm_mday);      

    return 0;
}
