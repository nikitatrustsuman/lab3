#include <stdio.h>
#include <math.h>
int main() {
  double a, c;

  printf("Введіть значення c: ");
  scanf("%lf", &c);
  
  printf("Введіть значення a: ");
  scanf("%lf", &a);

  if (c < 5) a = a*a - 4*a / a*c;
  else if (5 <= c && c <= 10) a = a*c * sqrt(a*c - 8*a);
       else a = c*c - 2*a;

  printf("Значення a: %lf\n", a);


  return 0;
}
