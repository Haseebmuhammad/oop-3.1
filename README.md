# oop-3.1
C++ program /display welcome message
#include<iostream>
using namespace std;
//GradeBook class defination
class GradeBook
{
public:
	//function that display a welcome message to the Gradebook user
	void displayMessage()const
	{ 
		cout<<"Welcome to the Grade Book!"<<endl;
		
	}//end function displayMessage
	
};// end class GradeBook
//function main begins program execution
int main()
{
	GradeBook myGradeBook;//create a GradeBook object named myGradebook
	myGradeBook.displayMessage();//call onbject display message function
}//end main
