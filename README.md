# Music-player
//I have made a music player with the help of C++


#include<windows.h>                  // windows.h is a header file used in windows as related to WIndows API
#include<iostream>
#in;cude<mmstream.h>

#pragma comment (lib, "winmm.lib")

int main () {

std::cout<<"Playing music\n";
PlaySound(TEXT("megalovania.wav"), NULL, SND_FILENAME | SND_SYNC);  // It is just my computer saved music file you cn take your as per your music
std::cout<<"That was fun \n";
return 0;

}

//NOTE : This is a simple media player you can make it more advance by integrating systems like API'S or collaborative files..
