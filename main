#include <iostream>
#include <cstdlib>
using namespace std;

void menu(){
  cout << "****GRADE CALCULATOR!****"  <<endl;
cout << "FINAL EXAM: 50% " << endl;
cout << "MIDTERM EXAM: 20%" << endl;
cout << "HOMEWORK/PROJECTS: 20%" << endl;
cout << "ATTENDANCE: 10%" << endl;

cout << "SCALE OF EACH ASSIGNMENT,TEST,and ATTENDANCE is out of 100" << endl;

cout << "*-----------------------------*" << endl;
}


int fin(int x){
  float total;

  total = x * .5;
  return total;
}

int mid(int x){
  float total;

  total = x * .2;
  return total;
}

int assigned(int x, int y, int z, int a, int b){
  float total;
  float average;
  average = (x + y + z +a + b) / 5;

  total = average * .2;
  return total;
}

int attend(int x){
  float total;

  total = x * .1;
  return total;
}

int main() {
menu();

float fexam;
float mexam;
float assign, assign2, assign3, assign4, assign5;
float attendance;
float finalgrade;

cout << "Enter your final exam grade: " <<flush;
cin >>fexam;
fin(fexam);

cout << "Enter your Midterm exam grade: " <<flush;
cin >>mexam;
mid(mexam);

cout << "(5) Enter your assignment grades: " <<flush;
cin >>assign >> assign2 >> assign3 >>assign4 >> assign5;
assigned(assign, assign2, assign3, assign4, assign5);


cout << "Enter your attendance exam grade: " <<flush;
cin >>attendance;
attend(attendance);

finalgrade = attend(attendance) + mid(mexam) + fin(fexam) + assigned(assign, assign2, assign3, assign4, assign5);

cout << "Your final grade is: " << finalgrade << endl;

}
