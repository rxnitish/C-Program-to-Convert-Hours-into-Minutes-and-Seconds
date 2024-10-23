# C-Program-to-Convert-Hours-into-Minutes-and-Seconds
#include <stdio.h> 
  
// Function to convert hours 
// into minutes and seconds 
void ConvertHours(int n) 
{ 
    long long int minutes, seconds; 
  
    minutes = n * 60; 
    seconds = n * 3600; 
      
    printf("Minutes = %lld, Seconds = %lld 
",minutes,seconds); 
} 
  
// Driver code 
int main() 
{ 
    int n = 5; 
    ConvertHours(n); 
    return 0; 
}
