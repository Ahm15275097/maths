
        include <iostream>
        include <string>
        using namespace std;

        Program Start
        int main() {
          cout << "Welcome to the program! " << endl;
          // Labelling x, y and z as integers
          int x,y,z;

          cout << "Please enter the number of hot dogs that come in a single package: ";
          cin >> x;	// The first number is taken in
          cout << "Please enter the number of buns that come in a single package: ";
          cin >> y;	// The second number is taken in

          z=x*y;	// The third variable is the product of the two numbers given

          while(x!=y) {	// A while loop.
              if(x>y)	
                x=x-y;	
              else		
                y=y-x;	
            }

          cout << 
          cout << "The minimum number of items per package" << x << endl;	
          cout << "The minimum number of servings  " << z/x << endl;	

          return 0;

}       
