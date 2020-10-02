#include <iostream.h>
#include <conio.h>
#include <dos.h>

void startdisplay()
{
    clrscr();
    for(int x=50;x>26;x--)
    {
       delay(120);
       gotoxy(x,10);
    cputs("HAPPY BIRTHDAY APOORV BHAI ");
    }
    delay(1000);
    gotoxy(22,14);
    cputs("THERE IS SOMETHING FOR YOU SO PLEASE ENJOY :):)  ");
    getch();
}
int menudisplay()
{
    clrscr();
    int a;
    gotoxy(2,2);
    cputs("APOORV MAHESHWARI, THE HORIZON HEAD");
    delay(1000);
    gotoxy(25,6);
    cputs("CHOOSE ANY ONE FOR APOORV");
    delay(1000);
    gotoxy(26,10);
    cputs("1. BHABHI JI ");
    gotoxy(26,12);
    cputs("2. CRUSH");
    gotoxy(26,14);
    cputs("3. FREE TIME");
    gotoxy(26,16);
    cputs("4. EXIT");
    gotoxy(26,20);
    cin>>a;
    return a;
}
void bhabhidisplay()
{
   clrscr();
   gotoxy(25,15);
    cputs("anushtha");
    getch();
}
void crushdisplay()
{
   clrscr();
   gotoxy(25,15);
    cputs("anushtha");
    getch();
}
void freedisplay()
{
   clrscr();
   gotoxy(25,15);
    cputs("anushtha");
    getch();
}
void main()
{
   clrscr();
   startdisplay();
   int i=1;
  do{
  clrscr();
  int n=menudisplay();
  switch(n)
  {
     case 1: bhabhidisplay();
	     break;
     case 2: crushdisplay();
	     break;
     case 3: freedisplay();
	     break;
     case 4: i=0;
	     break;
  }
  delay(1000);
 }while(i);
 clrscr();
 gotoxy(10,10);
 cputs("Stay healthy and Stay happy bro and may your day be very joyful");
 getch();
}