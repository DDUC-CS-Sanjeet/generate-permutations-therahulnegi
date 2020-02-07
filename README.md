#include<iostream>
using namespace std;
void permutation(chat P[], int local, int end) 
{
if(local == end) 
cout<<P<<endl;
else 
for( int i = local; i<=end; i++) 
{
swap (P[local], P[i];
permutation (P, local+1, end);
swap (P[local], P[i]);
}
 }
 }
int main() 
{
int number ;
cout<<"/enter the no of character ";
cin>>number;
Char set[100];
Char alpha = 'a';
 for(int i =0; i<number; i++) 
{
set[i] = alpha;
 alpha++;
}
set [number] ='/0';
permutation (set, 0, number-1) ;
   return 0;
}
