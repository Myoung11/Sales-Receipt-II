// Matthew Young
// Sales Receipt Revised

/* This program will give the user a sales receipt based on the number of items they have, 
   the price of each item and the sales tax percentage. It will output each individual 
   sales item and its price, the total value of the items, the total sales tax, and 
   the grand total. */

#include <iostream>
#include <iomanip>
#include <cmath>
#include <vector>

using namespace std; 

int main() 
{                             // Beginning of Main Function
    double numItems;          // Variable for number of items
    double valItem;           // Variable for price of items 
    double salesTax;          // Variable for amount of sales tax
    double totSales = 0;      // Variable for total of all prices  
    double totTax;            // Variable for total sales tax
    double grandTot;          // Variable for grand total 
    char runProg;             // Variable for if the user wants to run the program again
   vector<double> salesItems; // Vector to hold each individual sales item and price
   int numVals;               // Variable for number of sales items, also included in size of vector
   int i;                     // Variable for loops
   
   cout << "How many sales items do you have? ";  // Asks the user how many sales items they have
   cin >> numVals;                                // User inputed number of sales items 
   
   salesItems.resize(numVals);                    // Sets the size of the vector equal to the number of sales items
   
   for (i = 0; i < salesItems.size(); ++i) {                         // For loop for value of sales items
      cout << "Enter in the value of sales item " << i +1 << " : $"; // Asks user the value of each sales item
      cin >> salesItems.at(i);                                       // User inputed value of sales item
   }
   
   totSales = 0;                                                     // Sets totSales equal to zero for 'for' loop
   for (i = 0; i < salesItems.size(); ++i) {                         // For loop to find total of all prices
      totSales = totSales + salesItems.at(i);                        // Equation for totSales
   }
      

    cout << endl;                                                    // Creates a space
    
    cout << "Enter in the sales tax percentage" << endl;             // Ask user for sales tax percentage
    cout << "(Enter 10 for 10%): ";                                  // Tells user format for input
    cin >> salesTax;                                                 // User inputed sales tax percentage
    
    cout << endl;                                                    // Creates a space
    
    salesTax = salesTax / 100;                                       // Equation to turn user inputed sales tax into decimal 
    totTax = salesTax * totSales;                                    // Equation to find dollar amount of sales tax. 
    grandTot = totTax + totSales;                                    // Equation to find grand total of sales tax and prices
    
    cout << "*********************************************" << endl; // Inputs top border
    cout << "********  S A L E S  R E C E I P T  *********" << endl; //Inputs title for all output 
    cout << "*********************************************" << endl; // Inputs part of top border
    cout << "**                                         **" << endl; // Inputs border 
    for (i = 0; i < salesItems.size(); ++i) {                        // For loop using vector to hold each sales item number and price
      cout << "**  Sales item " << i + 1 << setw(13) << right << "$   ";      // Ouputs border and title for each sales item number and dollar sign
      cout << fixed << setprecision(2) << salesItems.at(i);          // Outputs each individual price for each sales item
    cout << "         **";                                           // Inputs ouside border
      cout << endl;                                                  // Creates a space
   }
    cout << "**                                         **" << endl; // Inputs border
    cout << "*********************************************" << endl; // Inputs border
    cout << "**                                         **" << endl; // Inputs border
    cout << "**                                         **" << endl; // Inputs border
    cout << "**                                         **" << endl; // Inputs border
    cout << "**                                         **" << endl; // Inputs border
    cout << "**  Total Sales" << setw(14) << right << "$   ";                 // Inputs title for total sales output and aligns dollar sign 
    cout << fixed << setprecision(2) << totSales << setw(10) << "**" << endl; // Sets amount to two decimals and aligns output for total sales
    cout << "**  Sales Tax" << setw(17) << right << "$    ";                           // Inputs title for sales tax ouput and aligns dollar sign
    cout << fixed << setprecision(2) << totTax << setw(11) << "**" << endl;   // Sets amount to two decimals and aligns output for sales tax
    cout << "**                        ----------       **" << endl;          // Inputs divider bewtween total sales, sales tax and grand total 
    cout << "**  Grand Total" << setw(14) << right << "$   ";                          // Inputs title for grand total output and aligns dollar sign
    cout << fixed << setprecision(2) << grandTot << setw(10) << "**" << endl; // Sets amount to two decimals and aligns output for grand total 
    cout << "**                                         **" << endl;          // Inputs border
    cout << "**                                         **" << endl;          // Inputs border
    cout << "*********************************************" << endl;          // Inputs border
    
    cout << endl;                                                             // Creates a space
    cout << "Do you want to run the program again? (Y/N): ";                  // Asks user if they want to run the program again
    cin >> runProg;                                                           // User inputed answer
    
    while (runProg == 'Y' || runProg == 'y') {   // While loop for when the user wants to run the program again
        
        double numItems;          // Variable for number of items
        double valItem;           // Variable for price of items 
        double salesTax;          // Variable for amount of sales tax
        double totSales = 0;      // Variable for total of all prices  
        double totTax;            // Variable for total sales tax
        double grandTot;          // Variable for grand total 
        char runProg;             // Variable for if the user wants to run the program again
        vector<double> salesItems; // Vector to hold each individual sales item and price
        int numVals;               // Variable for number of sales items, also included in size of vector
        int i;                     // Variable for loops
        
        cout << endl;                                  // Creates a space
        cout << "How many sales items do you have? ";  // Asks the user how many sales items they have
        cin >> numVals;                                // User inputed number of sales items 
  
        salesItems.resize(numVals);                    // Sets the size of the vector equal to the number of sales items
   
            for (i = 0; i < salesItems.size(); ++i) {                         // For loop for value of sales items
                cout << "Enter in the value of sales item " << i +1 << " : $"; // Asks user the value of each sales item
                cin >> salesItems.at(i);                                       // User inputed value of sales item
            }
   
        totSales = 0;                                                     // Sets totSales equal to zero for 'for' loop
            
            for (i = 0; i < salesItems.size(); ++i) {                         // For loop to find total of all prices
                totSales = totSales + salesItems.at(i);                        // Equation for totSales
            }
      

        cout << endl;                                                    // Creates a space
    
        cout << "Enter in the sales tax percentage" << endl;             // Ask user for sales tax percentage
        cout << "(Enter 10 for 10%): ";                                  // Tells user format for input
        cin >> salesTax;                                                 // User inputed sales tax percentage
    
        cout << endl;                                                    // Creates a space
    
        salesTax = salesTax / 100;                                       // Equation to turn user inputed sales tax into decimal 
        totTax = salesTax * totSales;                                    // Equation to find dollar amount of sales tax. 
        grandTot = totTax + totSales;                                    // Equation to find grand total of sales tax and prices
    
        cout << "*********************************************" << endl; // Inputs top border
        cout << "********  S A L E S  R E C E I P T  *********" << endl; //Inputs title for all output 
        cout << "*********************************************" << endl; // Inputs part of top border
        cout << "**                                         **" << endl; // Inputs border 
        
        for (i = 0; i < salesItems.size(); ++i) {                        // For loop using vector to hold each sales item number and price
            cout << "**  Sales item " << i + 1 << setw(13) << right << "$   ";      // Ouputs border and title for each sales item number and dollar sign
            cout << fixed << setprecision(2) << salesItems.at(i);          // Outputs each individual price for each sales item
            cout << "         **";                                           // Inputs ouside border
            cout << endl;                                                  // Creates a space
        }
        
        cout << "**                                         **" << endl; // Inputs border
        cout << "*********************************************" << endl; // Inputs border
        cout << "**                                         **" << endl; // Inputs border
        cout << "**                                         **" << endl; // Inputs border
        cout << "**                                         **" << endl; // Inputs border
        cout << "**                                         **" << endl; // Inputs border
        cout << "**  Total Sales" << setw(14) << right << "$   ";                 // Inputs title for total sales output and aligns dollar sign 
        cout << fixed << setprecision(2) << totSales << setw(10) << "**" << endl; // Sets amount to two decimals and aligns output for total sales
        cout << "**  Sales Tax" << setw(17) << right << "$    ";                           // Inputs title for sales tax ouput and aligns dollar sign
        cout << fixed << setprecision(2) << totTax << setw(11) << "**" << endl;   // Sets amount to two decimals and aligns output for sales tax
        cout << "**                        ----------       **" << endl;          // Inputs divider bewtween total sales, sales tax and grand total 
        cout << "**  Grand Total" << setw(14) << right << "$   ";                          // Inputs title for grand total output and aligns dollar sign
        cout << fixed << setprecision(2) << grandTot << setw(10) << "**" << endl; // Sets amount to two decimals and aligns output for grand total 
        cout << "**                                         **" << endl;          // Inputs border
        cout << "**                                         **" << endl;          // Inputs border
        cout << "*********************************************" << endl;          // Inputs border
    
        cout << endl;                                                             // Inputs space
    
        cout << "Do you want to run the program again? (Y/N): ";                  // Asks user if they want to run the program again
        cin >> runProg;                                                           // User inputed answer
    
            while (runProg == 'N' || runProg == 'n') { // Second while loop for 2+ times running through the program when user wants to end the program 
                cout << endl;                          // Creates space
                cout << "Thank You!" << endl;          // Tells user thank you
                return 0;                              // Returns nothing to output
            }
        }
    
            while (runProg == 'N' || runProg == 'n') { // Second while loop for original function when user wants to end the program
                cout << endl;                          // Creates space
                cout << "Thank You!" << endl;          // Tells user thank you
                return 0;                              // Returns nothing to ouput
            }
    
    
    

    return 0;
} // End of Main Function
