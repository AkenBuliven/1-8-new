# 1-8-new

#include <stdio.h>
#include <string.h>
#include <math.h>
#include <locale.h>
#include <stdlib.h>
#include <time.h>

int main(void) { 
	
  int k,m;
  scanf("%d%d", &k,&m);

	if (k < 1) k = 1;

  for (int i = k; i <= m; i++)
{
	printf (" %d", i);
}
  return 0;
}

Усовершенствуйте программу, написанную на прошлом шаге. Теперь необходимо вывести все натуральные числа из промежутка 
[
K
,
M
]
,
(
K
<
M
)
[K,M],(K<M)

Входные данные:
Два целых числа 
K
,
M
K,M. При этом 
M
M больше 
K
K.

Выходные данные: 
Натуральные числа в порядке возрастания принадлежащие промежутку 
[
K
,
M
]
[K,M]. Числа нужно разделять одним пробелом.


