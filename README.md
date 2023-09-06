#include <stdio.h>

int main() {
    int t1, t2, t3;
    double total_time;

    scanf("%d %d %d", &t1, &t2, &t3);

    total_time = (double)(t1 + t2 + t3);

    printf("%.2lf\n", total_time);

  return 0;
}
