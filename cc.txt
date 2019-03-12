void main()
{
    int X,Y,Z;
    int a,b,c;
    scanf("%d",&X);
    scanf("%d",&Y);
    scanf("%d",&Z);
    if(X<Y)
    {
        a=X;
        X=Y;
        Y=a;
    }
    if(X<Z)
    {
        b=X;
        X=Z;
        Z=b;
    }
    if(Y<Z)
    {
        c=Y;
        Y=Z;
        Z=c;
    }
    printf("%-10d%-10d%-10d",X,Y,Z);
}