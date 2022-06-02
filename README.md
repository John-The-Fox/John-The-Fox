- 👋 Hi, I’m @John-The-Fox
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
John-The-Fox/John-The-Fox is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

#include <iostream>
#include <locale.h>

  
  using namespace std;

/*global var*/
  
  int main () {
  setlocale(LC_ALL,"");/*set utf-8*/
  //code
  }

//limite inputs
#include<limits>
while((!(cin >> answer)) || (answer > 6) || (answer < 0)){
        cin.clear();
        cin.ignore(numeric_limits<streamsize>::max(), '\n');
        cout << "apenas numeros entre 0 e 6\n";
    }
