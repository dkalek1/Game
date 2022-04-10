# Game
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

void S_MAP(void);


int main()
{
    int stage;
    char input;
    char *pinput;
    pinput=&input
  
}


void S_MAP(void)
{
    srand(time(NULL));
    int Mx, My, RB = rand() % 4+1;
    
    for(My=0;My<5;My++)
      {for(Mx=0;Mx<5;Mx++)
        {if (Mx+My==RB)
          {printf("■ ");}
         else if (Mx<5)
          {printf("□ ");}
         else if (Mx==0&&My==0)
          {printf("☆ ");}}  
         
         
      printf("\n");}
      
    scanf("%c",&input);
    if (input='w');
