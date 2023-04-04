// using_namespace.cpp
#include <iostream>
#include <cstdlib>
// Строки C++.
#include <string>

int main()
{
  using namespace std; // Искать имена в std.

  string user_name = "user"; // a
  cout << "Hello, " << user_name << "!" << endl;

  user_name = "The Great Whale"; // b
  cout << "I am " << user_name;
  return EXIT_SUCCESS. 
