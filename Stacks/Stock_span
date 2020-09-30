#include <iostream>
#include<stack>
using namespace std;
void stock_span(long long int *price,long long int n,long long int *span)
{
stack<long long int>s;
s.push(0);
span[0]=1;
for(int i=1;i<=n-1;i++)
{
long long int cur_price=price[i];
while(!s.empty() and price[s.top()]<=cur_price)
{
s.pop();

}
