#include <iostream>
#include <string>
 
 
using namespace std;
 
int main()
{
for (;;)
{
 
int Health = 100, Damage = 100;
 
 
 
cout << "Wake up fella, welcome this is the world of bacon, what is your name? " << endl;
string YourName;
cin >> YourName;
 
 
cout << "Are you sure that your name is: " << endl;
cout << YourName << "? " << "Type Yes or No" << endl;
string NameTrue;
cin >> NameTrue;
 
if (NameTrue == "No")
continue;
 
cout << "Allright then " << YourName << " Let's Begin your adventure! " << endl;
 
cin.get();
cin.get();
 
cout << "This is the world of Bacon " << YourName << " This is the center of the universe, and we are, leading the biggest crystal mines in this     world." << endl;
 
                cin.get();
                cout << "Well before i continue, what is your age: " << endl;
       int AgeNumber = 0;
       cin >> AgeNumber;
 
       cin.get();
 
 
cout << "Let me continue, i am Sir Theodor, and i am the leader of bacon." << endl;
 
cout << "Your objective is to answer these questions correctly so you can survive outside newcomer , but if you wont, you will loose your health..." << endl;
       
cin.get();
 
cout << "You have 100 health, if you loose everything, you have lost the game." << endl;
cout << "Good Luck " << YourName << endl;
 
cout << "Now " << YourName << " You will get some questions: " << endl;
   

string Answer = "yes";
string Response;
cout << "1. Am i a boy?(yes or no) " << endl;
cin >> Response;
if (Response == Answer)
cout << "Yey Its correct! Let's Continue! " << endl;
else
{
cout << "You dumb person! You are wrong, you lost  died health" << endl;
cout << " Health(100) " << " - " << " Damage(100) " << " = " << Health - Damage << endl;
string Die = "no";
string DieAnswer;
cout << "Want to restart the game? " << endl;
cin >> DieAnswer;
if (DieAnswer == Die)
continue;
else
{
cout << "whatever sir, goodbye !" << endl;
break;
}
}
 
string Answer1 = "integer";
string Response1;
cout << "2. What does int stand for? " << endl;
cin >> Response1;
if (Response1 == Answer1)
cout << "Yey Its correct! Let's Continue! " << endl;
else
{
cout << "You dumb person! You are wrong, you lost died health" << endl;
cout << " Health(100) " << " - " << " Damage(100) " << " = " << Health - Damage << endl;
string Die = "yes";
string DieAnswer;
cout << "Want to restart the game? " << endl;
cin >> DieAnswer;
if (DieAnswer == Die)
continue;
 
else
{
cout << "whatever sir, goodbye !" << endl;
break;
}
 
 
}
 
string Answer2 = "bacon";
string Response2;
cout << "3. What is my favorite food? " << endl;
cin >> Response2;
if (Response2 == Answer2)
cout << "Yey Its correct! Let's Continue! " << endl;
else
{
cout << "You dumb person! You are wrong, you lost died health" << endl;
cout << " Health(100) " << " - " << " Damage(100) " << " = " << Health - Damage << endl;
string Die = "yes";
string DieAnswer;
cout << "Want to restart the game? " << endl;
cin >> DieAnswer;
if (DieAnswer == Die)
continue;
 
else
{
cout << "whatever sir, goodbye !" << endl;
break;
}
 
}
 
   
string Answer3 = "yes";
string Response3;
cout << "Do you like bacon? " << endl;
cin >> Response3;
if (Response3 == Answer3)
cout << "Yey Its correct! Let's Continue! " << endl;
else
{
cout << "You dumb person! You are wrong, you died ! " << endl;
cout << " Health(100) " << " - " << " Damage(100) " << " = " << Health - Damage << endl;
string Die = "yes";
string DieAnswer;
cout << "Want to restart the game? " << endl;
cin >> DieAnswer;
if (DieAnswer == Die)
continue;
 
else
{
cout << "whatever sir, goodbye !" << endl;
break;
}
}
string Answer4 = "Wizzard";
string Response4;
cout << "4.Which heroes go to missions to save our world? " << endl;
cout << "a)Knight b)Wizzard c)Soldiers from the king d)none of the above " << endl;
cin >> Response4;
if (Response4 == Answer4)
cout << "Yey Its correct! Let's Continue! " << endl;
else
{
cout << "You dumb person! You are wrong, you died ! " << endl;
cout << " Health(100) " << " - " << " Damage(100) " << " = " << Health - Damage << endl;
string Die = "yes";
string DieAnswer;
cout << "Want to restart the game? " << endl;
cin >> DieAnswer;
if (DieAnswer == Die)
continue;
 
else
{
cout << "whatever sir, goodbye !" << endl;
break;
}
}
string Answer5 = "Diamonts";
string Response5;
cout << " 5.What item can you find deep in  caves? " << endl;
cout << "a)Gold b)Diamonts c)Iron d)none of the above " << endl;
cin >> Response5;
if (Response5 == Answer5)
cout << "Yey Its correct! Let's Continue! " << endl;
else
{
cout << "You dumb person! You are wrong, you died ! " << endl;
cout << " Health(100) " << " - " << " Damage(100) " << " = " << Health - Damage << endl;
string Die = "yes";
string DieAnswer;
cout << "Want to restart the game? " << endl;
cin >> DieAnswer;
if (DieAnswer == Die)
continue;
 
else
{
cout << "whatever sir, goodbye !" << endl;
break;
}
}
string Answer6 = "Bacon";
string Response6;
cout << "6.Which  food do people eat ? " << endl;
cout << "a)Bread b)Bacon c)Patotes d)none of the above " << endl;
cin >> Response6;
if (Response6 == Answer6)
cout << "Yey Its correct! Let's Continue! " << endl;
else
{
cout << "You dumb person! You are wrong, you died ! " << endl;
cout << " Health(100) " << " - " << " Damage(100) " << " = " << Health - Damage << endl;
string Die = "yes";
string DieAnswer;
cout << "Want to restart the game? " << endl;
cin >> DieAnswer;
if (DieAnswer == Die)
continue;
 
else
{
cout << "whatever sir, goodbye !" << endl;
break;
}
}
      string Answer7 = "Weapons";
string Response7;
cout << "7.What can you exchange with coins ? " << endl;
cout << "a)Food b)Armor c)Weapons d)none of the above " << endl;
cin >> Response7;
if (Response7 == Answer7)
cout << "Yey Its correct! Let's Continue! " << endl;
else
{
cout << "You dumb person! You are wrong, you died ! " << endl;
cout << " Health(100) " << " - " << " Damage(100) " << " = " << Health - Damage << endl;
string Die = "yes";
string DieAnswer;
cout << "Want to restart the game? " << endl;
cin >> DieAnswer;
if (DieAnswer == Die)
continue;
 
else
{
cout << "whatever sir, goodbye !" << endl;
break;
}
}
 
string Answer8 = "Norway";
string Response8;
cout << "Now.. Your Last Question, if you answer correctly,  you have won the game! " << endl;
cin.get();
cin.get();
cout << "What is my location?" << endl;
cin >> Response8;
if (Response8 == Answer8)
cout << "Congratulations, you  won the game! " << endl;
else
{
cout << "You dumb person! You are wrong, you lost died health" << endl;
cout << " Health(100) " << " - " << " Damage(100) " << " = " << Health - Damage << endl;
string Die = "yes";
string DieAnswer;
cout << "Want to restart the game? " << endl;
cin >> DieAnswer;
if (DieAnswer == Die)
continue;
 
else
{
cout << "whatever sir, goodbye !" << endl;
break;
}
 
 
}
cin.get();
cin.get();
string GameRestart = "yes";
string RestartAnswer;
cout << "Congratulations again sir, you won this game you can survive the world." << endl;
 
cin.get();
cout << "Want to restart the game?" << endl;
cin >> RestartAnswer;
if (RestartAnswer == GameRestart)
continue;
 
else
{
cout << "Allright then, goodbye! Thanks for playing. " << endl;
break;
}
cin.get();
cin.get();
 
return 0;
}
 
cout << "Press Any Key to quit ;)" << endl;
cin.get();
cin.get();
return 0;
 
}
