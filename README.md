# Lesson

//Hi there, my name is Mike!)
//I`m editing my main branch
#include <iostream>
#include <cmath>
using namespace std;

int main()
{
    int const ROWS = 7;
    int const COLS = 9;

    int arr[ROWS][COLS];

    for (int i = 0; i < ROWS; i++)
    {
        for (int j = 0; j < COLS; j++)
        {
            arr[i][j] = rand() % 30;
        }
    }
    for (int i = 0; i < ROWS; i++)
    {
        for (int j = 0; j < COLS; j++)
        {
            cout << arr[i][j] << "\t";
        }
        cout << endl;
    }
    cin.get();
    return 0;
}
