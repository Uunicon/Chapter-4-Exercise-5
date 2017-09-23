//# Chapter-4-Exercise-5
//It's an exercise of the book named C++ Primer Plus by Stephen Prata.
//I' d like to share my code and get some advice.

//Write a program that declares such a structure and creates a CandyBar variable called snack,initializing its members to 
//"MachaMunch",2,3,and 350,respectively.

#include <iostream>
#include <string>
using namespace std;

struct CandyBar
{
	string str1;       //input only one word
	float weg;
	int cal;
};
int main()
{
    CandyBar snack =
    {
    	"MochaMunch",2.3,350
	};
	cout<<snack.str1<<" "<<snack.weg<<" "<<snack.cal<<endl;
    
    return 0; 
}
