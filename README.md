#include <cstdlib>
#include <iostream>
using namespace std;
int main()
{   int broj;
    bool prost=true;
    cin >>broj;
    for (int i=2; i < broj && prost==true;i++)
        if (broj%i==0) prost=false;
    if (prost==true) cout << broj << " je prost" << endl;
       else cout << broj << " je slozen" << endl;
    return 0;
}
