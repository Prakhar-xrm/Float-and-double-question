#include <stdio.h>
int main(){
  
  float num;
  
  scanf("%f", &num);
 
  printf("Original float value: %f\n", num);
  printf("Converted to double value: %lf\n", num);
  printf("Converted back to float value: %f\n",(float)num);
  return 0;
}
