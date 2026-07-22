sum of adjacent numbers
adds all adjacent numbers until a negative number comes gives total value
eg: 1,2,7,5,-1
ans:14
expalantion
add 1 and 2 =3
then 3 and 7=10
then 10 and 5=15
then -1 comes so 15 -1=14 so ans:14
code explaination:
int sum = 0;
        int x;
        do{
            x = sc.nextInt();
            sum=sum+x;
        }while(x >= 0);
at begining we have sum value 0 
and declared x
then we took x value as input then adds to sum 
then checks x value greater then 0 or not if yes it continues loop other wise returns sum value
