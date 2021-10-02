#include <iostream>
#include <string>
using namespace std;


int main()
{
   char grade;

   cout << "Enter grade (aAbBcCdDfF) :";
   cin >> grade;
   switch(grade) {
      case 'a':
      case 'A': cout << "range 90-100" << endl;
                break;
      case 'b':
      case 'B': cout << "range 80-89" << endl;
                break;
      case 'c':
      case 'C': cout << "range 70-79" << endl;
      case 'd':
      case 'D': cout << "range 60-69" << endl;
                break;
      case 'f':
      case 'F': cout << "range 0-59" << endl;
              break;              
      default: cout << "Invaid grade" << endl;
   }
   return 0;
}
