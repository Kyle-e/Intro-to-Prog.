# Intro-to-Prog.
Program Exercises

//Write a program that works out of a number is even or odd.

#include <iostream>
using namespace std;
 
  int main() 
  {
  int num;
  cout << "Input a number: ";
  cin >> num;
  
  if (num % 2 == 0)
  cout << num << " is an even number." endl;
  else
  cout << num << " is an odd number." endl;
  
  return 0;
  }

 
//Write a program to check whether a number is positive, negative, or 0.
 
#include <iostream>
using namespace std;
 
 int main()
 {
 double num;
 
 cout << "Input a number: ";
 cin >> num;
 
 if (num > 0)
 cout << num << " is a positive number." endl;
 else if (num < 0)
 cout << num << " is a negative number." endl;
 else if (num == 0)
 cout << num << " is zero." endl;
 
 return 0;
 }
                    
                    
//Write a program to calculate profit or loss.
                    
#include <iostream>
using namespace std;
 
 int main()
{
float price, sales, amount;
 
 cout << "Input the cost of the product/s: ";
 cin >> price;
 
 cout << "Input the selling price: ";
 cin >> sales;
 
 if (sales > price)
 {
  amount = sales - price;
  cout << "Total profit earned: " << amount;
 }
 else if (price > sales)
 amount = price - sales
 cout << "Total loss: " << amount;
 }
 else
 cout << "No profit or loss.";
 
 return 0;
 }
 
 
 //Write a program that determines the shape from its number of sides.
 
 #include <iostream>
using namespace string;

int main() {

int sides;
string shape;

cout << "How many sides does the shape have?" << endl;
cin >> sides;
// if you type less than 2 the message will appear here
if (sides <= 2) {
    cout << "Invalid input.";
}
else if (sides == 3) {
    cout << "The shape is triangle.";
}
else if (sides == 4) {
    cout << "The shape is square.";
}
else if (sides == 5) {
    cout << "The shape is pentagon.";
}
else if (inum == 6) {
    cout << "The shape is hexagon.";
}
else if (sides == 7) {
    cout << "The shape is heptagon.";
}
else if (sides == 8) {
    cout << "The shape is octagon.";
}
else if (sides == 9) {
    cout << "The shape is nonagon.";
}
else if (sides == 10) {
    cout << "The shape is decagon.";
}
else {
    cout << "Invalid input.";
}

cin.get();
return 0;
}
