//Countdown

#include <iostream>
#include <string>
#include <iomanip>
#include <array>

using namespace std;
int main()
{
	for (int i = 10; i >= 0; i--) {
		cout << i << endl;
		if (i == 0){
			cout << "We have lift off!!";
		}
	}
	return 0;
}
//Some Counting
  
#include <iostream>
#include <string>
#include <iomanip>
#include <array>

using namespace std;
void inc1() {
	for (int i = 0; i <= 50; i++) {
		cout << i << endl;
	}	cout << "//" << endl;
}
void dec1() {
	for (int i = 50; i >= 0; i--) {
		cout << i << endl;
	}	cout << "//" << endl;
}
void inc30to50() {
	for (int i = 30; i <= 50; i++) {
		cout << i << endl;
	}	cout << "//" << endl;
}
void dec50to10() {
	for (int i = 50; i >= 10; i -= 2) {
		cout << i << endl;
	}	cout << "//" << endl;
}
void inc5() {
	for (int i = 100; i <= 200; i += 5) {
		cout << i << endl;
	}	cout << "//" << endl;
}
int main()
{
	inc1();
	dec1();
	inc30to50();
	dec50to10();
	inc5();
	return 0;
}
//Odd or even
                        
#include <iostream>
#include <string>
#include <iomanip>
#include <array>

using namespace std;

int main() {

	for (int i = 20; i <= 24; i++) {
		if (i % 2 == 0) {
			cout << i << " - Even" << endl;
		}
		else
		{
			cout << i << " - Odd" << endl;
		}
	}
}                        

//Iterate through a word
                                   
#include <iostream>
#include <string>
#include <iomanip>
#include <array>

using namespace std;

int main() {

	string myWord = "ARSH";
	for (int i = 0; i <= 4; i++) {
		cout << myWord.at(i) << endl;
	}
}
//Seven stars, Seven Lines
#include <iostream>
#include <string>
#include <iomanip>
#include <array>

using namespace std;

int main() {

	
	for (int i = 0; i <= 7; i++) {		
		for (int c = 0; c <= 7; c++)
		{
			cout << '*';
		}
		cout << endl;
	}
	return 0;
} 
//Descending stars, Seven lines
#include <iostream>
#include <string>
#include <iomanip>
#include <array>

using namespace std;

int main() {

	
	for (int i = 0; i <= 7; i++) {		
		for (int c = i; c <= 7; c++)
		{
			cout << '*';
		}
		cout << endl;
	}
	return 0;
}
//Rising stars, 5 lines
  
#include <iostream>
#include <string>
#include <iomanip>
#include <array>

using namespace std;

int main() {

	
	for (int i = 1; i <= 5; i++) {		
		for (int c = 1; c <= i; c++)
		{
			cout << '*';
		}
		cout << endl;
	}
	return 0;
}
  
//Rising and Falling stars
  
#include <iostream>
#include <string>
#include <iomanip>
#include <array>

using namespace std;

int main() {

	
	for (int i = 1; i <= 5; i++) {		
		for (int c = 1; c <= i; c++)
		{
			cout << '*';
		}
		cout << endl;
	}
	for (int i = 1; i <= 5; i++) {
		for (int c = i; c <= 4; c++)
		{
			cout << '*';
		}
		cout << endl;
	}
	return 0;
}
  
//Cubes
  
#include <iostream>
#include <string>
#include <iomanip>
#include <array>

using namespace std;

int main() {

	long double num;
	cout << "Enter Number : ";
	cin >> num;
	for (int i = 1; i <= num; i++) {		
		cout << "Number is : " << i << " and the cube of " << i << " is :" << pow(i,3) << endl;
	}
	return 0;
}

//9s
                                                                                          
#include <iostream>
#include <string>
#include <iomanip>
#include <array>

using namespace std;

int main() {
	int sum = 0;
	for (int i = 100; i <= 200; i++) {		
		if (i % 9 == 0)
		{
			cout << i << " Divided 9 = " << i / 9 << endl;
			sum = sum + i;
			
		}	
	}
	cout << "\nThe sum of all the integers that are divisible by 9 are = " << sum << endl;
	return 0;
}                                                                                          
