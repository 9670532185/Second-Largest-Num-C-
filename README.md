# Second-Largest-Num-C-
#include<iostream>
using namespace std;
int main()
{
int arr[4]={1,2,3};
int L=0;//INT_MIN;
int S=0;
for(int i=0;i<4;i++)
{
	if(arr[i]>L)
	{
		S=L;
		L=arr[i];
		
	}
	else{
		if(arr[i]>S and arr[i]<L)
		{
			S=arr[i];
		}
	}
}
cout<<S;
}

