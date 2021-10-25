 Bài 9
#include <iostream>
using namespace std;
int main()
{
    int i = 1,a;
	cout <<"a=" <<endl;
	cin >> a;	              
	int s=0;
    for (int i=1;i<=a;i++)
        s=s+i;
    cout<<"Tong cac phan tu la "<< s ;
}
Bài 10
#include <iostream>
using namespace std;
int main()
{
    int i = 1,b;
	cout <<"b=" <<endl;
	cin >> b;
    int t=1;
	for (int i =1 ; i<=b; i++)
		t=t*i;
    cout<<" b!="<< t ;
}
Bài 12
#include <iostream>
using namespace std;
int main()
{
 int i=1,a;
cout << "a=" <<endl;
	cin >> a;
	int s=0;
	for(int i=1;i<=a;i++)
    if( i / 3 ==0){s=s+i;}
	cout <<"tong cac so chia het cho3 la "<<  s;
	}
