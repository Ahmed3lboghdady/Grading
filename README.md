# Grading
This C++ program assigns a grade based on a student’s percentage input. It uses conditional statements to categorize the grade: "Fail" for less than 50, "Pass" for 50-64, "Good" for 65-74, "Very Good" for 75-84, and "Excellent" for 85-100. If the input is over 100, an error message is displayed.

    #include <iostream>
    using namespace std;
    int main()
    {
     int percentage;
     cout << "enter your percentage = ";
     cin >> percentage;
     if( percentage < 50 )
     {
     cout << "Student Grade is Fail\n";
     }
     else if( percentage < 65 )
     {
     cout << "Student Grade is Pass\n";
     }
     else if( percentage < 75)
     {
     cout << "Student Grade is Good\n";
     }
     else if( percentage < 85 )
     {
     cout << "Student Grade is Very Good!\n";
     }
     else if(percentage <= 100 )
     {
     cout << "Student Grade is Excellent!\n";
     }
     else
     {
     cout << "this is not grade because it is greater than 100\n";
     }
     return 0;
    }
