#include <iostream> 
#include <math.h> 
using namespace std; 
class Number {; 
public: 
 int a; 
 int number; 
 int result = 0; 
 void train(){ 
  if(number > 20) 
   cout << "нет такой квартиры"<< endl; 
  else{ 
   result = (number/4)+1; 
     cout <<"Квартира: "<< number << endl; 
  } 
 } 
 void print() 
 { 
  cout << "Этаж: "<< result; 
 } 
}; 
int main() 
{ 
 setlocale(LC_ALL, "Russian"); 
 Number num; 
 num.number = 9; 
 num.train(); 
 num.print(); 
  
  
}
