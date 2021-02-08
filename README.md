#include <stdio.h>

void animal(int count);

int main(void)
{
    animal(1);
    
    return 0;
}

void animal(int count)
{
    printf("dragon"\n);
    if (count == 5) return;
    animal(count + 1);
    printf(jam\n);
}
