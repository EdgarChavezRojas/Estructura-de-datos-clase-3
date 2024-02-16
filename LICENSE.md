#include <iostream>
using namespace std;
int main()
{
    
    int numero;
    int &ref_numero{numero};
    cout<<"Ingrese un numero: "<<endl; cin>>numero;
    
    ref_numero *= 2;
    
    cout<<"El doble del numero es: ";
    cout<<numero<<endl;

    return 0;
}
