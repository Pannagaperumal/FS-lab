#File structure lab
https://drive.google.com/drive/folders/1q-O5dpeIyuYn4D7AmVBc-NKDNx7tabD1?usp=sharing
#include<stdio.h>
3 int main()
4 {
5 int locks, stocks, barrels, tlocks, tstocks, tbarrels;
6 float lprice,sprice,bprice,lsales,ssales,bsales,sales,comm;
7 lprice=45.0;
8 sprice=30.0;
9 bprice=25.0;
10 tlocks=0;
11 tstocks=0;
12 tbarrels=0;
13 printf("\nenter the number of locks and to exit the loop enter -1 for locks\n");
scanf("%d", &locks);
14 while(locks!=-1) {
15 printf("enter the number of stocks and barrels\n");
scanf("%d%d",&stocks,&barrels);
16 tlocks=tlocks+locks;
17 tstocks=tstocks+stocks;
18 tbarrels=btarrels+barrels;
19 printf("\nenter the number of locks and to exit the loop enter -1 for 
locks\n"); scanf("%d",&locks);
20 }
21 printf("\ntotal locks = %d\”,tlocks);
22 printf(“total stocks =%d\n”,tstocks);
23 printf(“total barrels =%d\n",tbarrels);
24 lsales = lprice*tlocks;
25 ssales=sprice*tstocks;
26 bsales=bprice*tbarrels;
27 sales=lsales+ssales+bsales;
28 printf("\nthe total sales=%f\n",sales);
29 if(sales > 1800.0)
30 {
31 comm=0.10*1000.0;
32 comm=comm+0.15*800;
33 comm=comm+0.20*(sales-1800.0);
}
34 else if(sales > 1000)
35 {
36 comm =0.10*1000;
37 comm=comm+0.15*(sales-1000);
}
38 else 
39 comm=0.10*sales;
40 printf("the commission is=%f\n",comm);
