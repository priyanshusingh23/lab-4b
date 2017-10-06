#include <iostream>



using namespace std;

 

int showValues(int [], int);

int sum(int [], int);

 

int main()

{

    const int SIZE = 7; //constant for the array size

    int arrayNum[SIZE] = {10, 10, 10, 10, 10, 10, 10};

    int total;

 

    cout << "The numbers in the array are: \n" << endl;

    showValues(arrayNum, SIZE); //function call to show the array contents

    cout << endl;

     

    total = sum(arrayNum, SIZE);

    cout << "The sum is: " << endl;

     

    //getch();//hold the screen

    return 0;

}//end main

int showValues(int num[], int val)

{

    //for loop to display the array elements

    for (int index = 0; index < val; index++)

        cout << num[index] << "\t"; //echo print to screen

    cout << endl;

    return 0;

}//end void

 

int sum(int arrayNum, int size)

{

    int total;

 

    if (size == 1)

        return total = arrayNum[size - 1]; // terminating point

    else

        return total + sum(arrayNum, size - 1);

                // general form

}
