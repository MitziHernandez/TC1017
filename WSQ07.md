#include <iostream>
using namespace std;
int main ()

{
  int lim1, lim2;
  char A;
  do
  {
  cout<< "ingrese el limite inferior " <<endl;
  cin>> lim1;

  cout<< "ingrese el limite superior " <<endl;
  cin>> lim2;
  int suma=0;
  for (int i=lim1; i<lim2; i++)
  {
    suma=suma + i;
    i++;
  }
  cout<<  "la suma es: " <<suma <<endl;
  cout<< "quieres repetir el programa?, Si o No" <<endl;
  cin >> A;
} While (A == 'Y');
return 0;
}
