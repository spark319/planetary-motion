# planetary-motion
#include<graphics.h>
main(){
    initwindow(500,500);
    circle(175,125,100);//main
    circle(175,125,70);//main 2
    circle(175,125,30);
    setfillstyle(SOLID_FILL,YELLOW);
    floodfill(175,125,WHITE);


    //circle(175,55,10);//top 2
    //circle(175,195,10);//down 2
    //circle(105,125,10);//left 2
    //circle(245,125,10);//right 2

    circle(105,125,10);//left 2
    delay(1000);

    setcolor(BLACK);
    circle(105,125,10);//left 2
    setcolor(7);
    circle(175,195,10);//down 2
    delay(1000);

    setcolor(BLACK);
    circle(175,195,10);//down 2
    setcolor(7);
    circle(245,125,10);//right 2
    delay(1000);

    setcolor(BLACK);
    circle(245,125,10);//right 2
    setcolor(7);
    circle(175,55,10);//top 2
    delay(1000);

    setcolor(BLACK);
    circle(175,55,10);//top 2
    setcolor(7);
    circle(105,125,10);//left 2
    delay(1000);



    int c=1;
    while(c!=0){
        circle(175,25,20);//top
        delay(1000);

        circle(105,125,10);//left 2
        delay(1000);


        setcolor(BLACK);
        circle(175,25,20);//top
        setcolor(7);
        circle(75,125,20);//left
        delay(1000);


        setcolor(BLACK);
        circle(105,125,10);//left 2
        setcolor(7);
        circle(175,195,10);//down 2
        delay(1000);

        setcolor(BLACK);
        circle(75,125,20);//left
        setcolor(7);
        circle(175,225,20);//down
        delay(1000);

        setcolor(BLACK);
        circle(175,195,10);//down 2
        setcolor(7);
        circle(245,125,10);//right 2
        delay(1000);


        setcolor(BLACK);
        circle(175,225,20);//down
        setcolor(7);
        circle(275,125,20);//right
        delay(1000);

         setcolor(BLACK);
        circle(245,125,10);//right 2
        setcolor(7);
        circle(175,55,10);//top 2
        delay(1000);

        setcolor(BLACK);
        circle(275,125,20);//right
        setcolor(7);
        circle(175,25,20);//top
        delay(1000);


        setcolor(BLACK);
        circle(175,55,10);//top 2
        setcolor(7);
        circle(105,125,10);//left 2
        delay(1000);
    }
    getch();
}
