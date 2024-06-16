 #include<stdio.h>
int main()
{
    int n;
    scanf("%d",&n);
    if(n>87)
    {
        printf("diff is: %d",((n-87)*3));
    }
    else
    {
        printf("diff is: %d",(87-n));
    }
    
}
