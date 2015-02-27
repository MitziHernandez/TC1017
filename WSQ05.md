#include <iostream>
using namespace std;
int F, C;

int main()
{
  cout<< "ingrese los grados fahrenheit" <<endl;
  cin>> F;
  C=(5*(F-32)/9);
  cout<< "los grados en celsius es " << C <<endl;

  if (C<100)
  cout<< "no está hirviendo" <<endl;

  else
  cout<< "sí está hirviendo" <<endl;

return 0;

}
