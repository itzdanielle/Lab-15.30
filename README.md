# Lab-15.30
#include <iostream>
#include <cmath> 
using namespace std;

int main() {
  
  float ar;
  float s;
  float n;
  cout << "Enter the number of sides" << endl;
  cin >> n;
  cout << "Enter the side of the hexagon" << endl;
  cin >> s;
  ar = (n * ( s * s))/(4 * tan(M_PI/n));
  cout << "The area of the hexagon is " << ar << endl;
}
