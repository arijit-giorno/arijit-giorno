- 👋 <h3>Hi, I’m @arijit-giorno</h3>
- 👀 I’m interested in everything but little bit 🍑 
- 🎉 I'm a otaku , a indian otaku
- 📫 How to reach me arijitsaha713130@gmail.com
- 
#include <stdio.h>
#include <windows.h>
int main()
{
    //system("color 3f");
    int h, m, s;
    int d = 1000; // add a delay of 1000 milisecoond and will use in main function
    printf("set time :\n");
    scanf("%d%d%d", &h, &m, &s);
    if (h > 12 || m > 60 || s > 60)
    {
        printf("ERROR!!!!!\n");
        exit(0);
    }
    while (1) // this is the infinite loop and anything inside it continues run
    {
        s++;
        if (s > 59)
        {
            m++;
            s = 0;
        }
        if (m > 59)
        {
            h++;
            m = 0;
        }
        if (h > 12)
        {
            h = 1;
        }
        printf("\n CLOCK:");
        printf("\n %02d:%02d:%02d", h, m, s); // this writes our time in this format  00:00:00
        Sleep(d);                             // this function sleep slows down while the loop and make it more real clock
        system("cls");                        // this clear the screen
    }
}

<!---
arijit-giorno/arijit-giorno is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->


<img src="https://m.media-amazon.com/images/M/MV5BODM5NDYyYmUtNjAwNi00YWNjLWI0ZjctYjZkMjIwY2VkMzA0XkEyXkFqcGdeQXVyNDQxNjcxNQ@@._V1_.jpg" width="200">
                                                                                                                                                 


