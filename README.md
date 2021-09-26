# Assignment-For-introduction-programming
// HCCL4


// slide 24 (odd or even)
		#include <iostream>
	using namespace std;


	int main() {
	int inum;

	cout << "Enter any number: ";
	cin >> inum;
	// If the number have remainder, it will convert to odd number
	if (inum % 2 == 0) {
		cout << "Even number ";
	}
	else {
		cout << "Odd number ";
	}


	cin.get();
	return 0;
	}
  
  //slide 25 (number checker)
	#include <iostream>
	using namespace std;

	int main() {

	int inum;
	
	cout << "Simple Number Checker Program!\n";

	cout << "Type a number: ";
	cin >> inum;

	if (inum > 0) {
		cout << " Thats positive";
	}
	else if (inum < 0) {
		cout << " Thats negative";
	}
	else {
		cout << " Zero";
	}


	return 0;
	}
	
// slide 26 (Profit or loss)
 	#include <iostream>
	using namespace std;

	int main() {

	int purchase;
	int sell;
	int loss;
	int profit;

	cout << "Enter the Purchase price : ";
	cin >> purchase;
	cout << "Enter the Selling price :  ";
	cin >> sell;
	profit = sell - purchase;

	if (profit > 0) {
		cout << profit << " Profit" << endl;
	}
	else if (profit == 0) {
		cout << profit << " Breakeven" << endl;
	}
	else {
		cout << profit << " Loss" << endl;
	}




	cin.get();
	return 0;
	} 
                              
                                                         
                                                         
 // slide 27 (Name of shape)
	#include <iostream>
	#include <string>
	using namespace std;


	int main() {

	int inum;
	string shape;

	cout << "Type 1 to 10" << endl;
	cin >> inum;
	// if you type less than 2 the message will appear here
	if (inum <= 2) {
		cout << "there is no shape that is less than 2 sides";
	}
	else if (inum == 3) {
		cout << "shape is triangle";
	}
	else if (inum == 4) {
		cout << "shape is square";
	}
	else if (inum == 5) {
		cout << "shape is Pentagon";
	}
	else if (inum == 6) {
		cout << "shape is Hexagon";
	}
	else if (inum == 7) {
		cout << "shape is Heptagon";
	}
	else if (inum == 8) {
		cout << "shape is Octagon";
	}
	else if (inum == 9) {
		cout << "shape is Nonagon";
	}
	else if (inum <= 10) {
		cout << "shape is Decagon";
	}
	else {
		cout << "10 is the maximum i can read.\n";
		// extra for fun
		cout << "Just type the shape you want or search it on google not the number" << endl;
		cin >> shape;
		cout << "This is the name of " << shape << " you are looking for\n";
	
	}



	cin.get();
	return 0;
}
