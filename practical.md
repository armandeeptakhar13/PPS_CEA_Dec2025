#include <iostream>

using namespace std;

int main()
{
    int u;
    cout << "username";
    cin >> u;
    cout << u+10;
    cout << u;
    return 0;
}
#include <iostream>

using namespace std;

int main()
{
    int a=5;
    int b;
    b=++a;
    cout << a;
    cout << b;
    a=5;
    b=a++;
    cout << a;
    cout << b;
    b=--a;
    cout << a;
    cout << b;
    b=a--;
    cout << a;
    cout << b;
    return 0;
}
