# shutdown-windows
#include&lt;stdio.h> #include&lt;stdlib.h>    // to use system() method  int main() {     printf("\n\n\t\tStudytonight - Best place to learn\n\n\n");      char ch;          printf("Do you want to shutdown your pc now (y/n)?");     scanf("%c", &amp;ch);      if(ch == 'y'|| ch == 'Y')     {   /*             /s is used to order the compiler              to shutdown the PC         */         system("C:\\WINDOWS\\System32\\shutdown /s");     }      printf("\n\n\t\t\tCoding is Fun !\n\n\n");     return 0; } You can use various options while executing shutdown.exe, for example you can use /t option to specify n
