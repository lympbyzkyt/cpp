#include <iostream>
using namespace std;

int main() {

    int choice;

    cout << "Enter 1 to calculate volume of sphere, 2 for calculating volume of cylinder or 3 for calculating volume of cone: ";
    cin >> choice;

    switch (choice)
    {
        case 1: 
        {
            int rds,vl;
            cout << "Enter the radius of a sphere: ";
            cin >> rds;
            vl = (43.14 * rds * rds * rds)/3;
            cout << "The volume of sphere is = "<< vl << "\n";
            break;
        }
        case 2: 
        {
            int rds1,hght;
            float vl2;

            cout << "\nNow we will calculate the volume of a cylinder.\n";
            cout << "Input the base radius of the cylinder: ";
            cin >> rds1;
            cout << "Input the height of the cylinder: ";
            cin >> hght;
            vl2 = (3.14 * rds1 * rds1 * hght);
            cout << "The volume of a cylinder is: "<< vl2 << "\n"; 
            break;
        }

        case 3: 
        {    
            const float pi = 3.14159;
            float rds2, hght2, vl3;
            cout << "Input Cone's radius: ";
            cin >> rds2;
            cout << "Input Cone's height: ";
            cin >> hght2;
            // Cone's volume.
            vl3 = (1.0/3.0) * pi * (rds2 * rds2) * hght2;
            cout << "The volume of the cone is: " << vl3;
            break;
        }

        default:
        {
            cout << "Not 1 for sphere, 2 for cylinder or 3 for cone"; 
            break;
        }
    }
}
