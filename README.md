include<stdio.h>
define bool int
bool isPo2(int n)
{
  if (n == 0)
    return 0;
  while (n != 1)
  {
    if (n%2 != 0)
      return 0;
    n = n/2;
  }
  return 1;
}
 int main()
{
    int n;
    scanf("%d",&n);
  if(isPo2(n)==1)
  printf("yes");
  else
  printf("no");
    return 0;
}
