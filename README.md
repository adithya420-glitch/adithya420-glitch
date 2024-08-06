

#include<iostream.h>

#include<conio.h>

#include<dos.h>

#include<stdlib.h>

#include<graphics.h>

void start1();

void start2();

void main()

{

	int gd=DETECT,gm;

	initgraph(&gd,&gm,"c:\\tc\\bgi");



	 outtextxy(200,330,"For Start Enter Any key - ") ;

	 getch();

	 start2();



	 getch();

	 start1();



	getch();

	closegraph();



}



void start2()

{



       //	int x= getmaxx()/2;

	int y= 30;

	int i, flag=0;

	while(!kbhit())

	{

	       setcolor(15);

	       line(0,getmaxy(),700,getmaxy());

	       line(0,getmaxy()-2,700,getmaxy()-2);

	       if(y>= getmaxy()-30 || y<=30)

	       {

		 flag = !flag;

	       }



		 setcolor(YELLOW);

		 circle(40,y,40);

		 setfillstyle(SOLID_FILL,YELLOW);

		 floodfill(40,y,YELLOW);

	       setcolor(15);

	       settextstyle(2,0,6);

	      outtextxy(130,250,"Hope Your Day Brings you all that your heart desire!");

	      outtextxy(150,270,"Here's Wishing You a Day Full Of Pleasant Surprises!");

	      outtextxy(350,430,"Enter Any Key -");



		 setcolor(BLACK);

		 setfillstyle(SOLID_FILL,0);

		 fillellipse(40-10,y-10,2,6);

		 fillellipse(40+14,y-10,2,6);

		 setcolor(0);

		 ellipse(40+1,y+7,205,335,20,9);

		 ellipse(40+1,y+7,205,335,20,10);

		 ellipse(40+1,y+7,205,335,20,11);





		 delay(90);

		 cleardevice();



		 if(flag==1)

		 {

		   y=y+7;

		 }

		 else

		 {

		    y=y-7;

		 }

	}

}



void start1()

{



	//cake

	setbkcolor(0);

	setcolor(15);



	setfillstyle(SOLID_FILL,8);

	rectangle(50,400,250,405);

	floodfill(51,401,15);

	setfillstyle(SOLID_FILL,4);

	rectangle(60,355,240,400);

	floodfill(61,365,15);



	setfillstyle(SOLID_FILL,4);

	rectangle(80,310,217,355);

	floodfill(81,311,15);

	setfillstyle(SOLID_FILL,4);

	rectangle(100,270,200,310);

	floodfill(101,271,15);



	setfillstyle(INTERLEAVE_FILL,9);

	circle(100,379,8);

	floodfill(100,379,15);

	setfillstyle(INTERLEAVE_FILL,9);

	circle(198,379,8);

	floodfill(198,379,15);

	setfillstyle(INTERLEAVE_FILL,9);

	circle(150,370,8);

	floodfill(150,370,15);

	setfillstyle(INTERLEAVE_FILL,5);

	circle(190,334,8);

	floodfill(190,334,15);

	setfillstyle(INTERLEAVE_FILL,5);

	circle(150,324,8);

	floodfill(150,324,15);

	setfillstyle(INTERLEAVE_FILL,5);

	circle(114,334,8);

	floodfill(114,334,15);



	setfillstyle(INTERLEAVE_FILL,11);

	circle(180,288,7);

	floodfill(180,288,15);

	setfillstyle(INTERLEAVE_FILL,11);

	circle(150,280,7);

	floodfill(150,280,15);

	setfillstyle(INTERLEAVE_FILL,11);

	circle(117,288,7);

	floodfill(117,288,15);





	setcolor(14);

	outtextxy(63,392,"\x03");

	outtextxy(72,392,"\x03");

	outtextxy(82,392,"\x03");

	outtextxy(92,392,"\x03");

	outtextxy(102,392,"\x03");

	outtextxy(112,392,"\x03");

	outtextxy(122,392,"\x03");

	outtextxy(132,392,"\x03");

	outtextxy(142,392,"\x03");

	outtextxy(152,392,"\x03");

	outtextxy(162,392,"\x03");

	outtextxy(172,392,"\x03");

	outtextxy(182,392,"\x03");

	outtextxy(192,392,"\x03");

	outtextxy(202,392,"\x03");

	outtextxy(212,392,"\x03");

	outtextxy(222,392,"\x03");

	outtextxy(232,392,"\x03");

	setcolor(15);



	setcolor(3);

	outtextxy(82,348,"\x03");

	outtextxy(92,348,"\x03");

	outtextxy(102,348,"\x03");

	outtextxy(112,348,"\x03");

	outtextxy(122,348,"\x03");

	outtextxy(132,348,"\x03");

	outtextxy(142,348,"\x03");

	outtextxy(152,348,"\x03");

	outtextxy(162,348,"\x03");

	outtextxy(172,348,"\x03");

	outtextxy(182,348,"\x03");

	outtextxy(192,348,"\x03");

	outtextxy(204,348,"\x03");

	setcolor(15);



	 setcolor(12);

	outtextxy(102,302,"\x03");

	outtextxy(112,302,"\x03");

	outtextxy(122,302,"\x03");

	outtextxy(132,302,"\x03");

	outtextxy(142,302,"\x03");

	outtextxy(152,302,"\x03");

	outtextxy(162,302,"\x03");

	outtextxy(172,302,"\x03");

	outtextxy(182,302,"\x03");

	outtextxy(192,302,"\x03");

	setcolor(15);



	//candal

	setfillstyle(INTERLEAVE_FILL,RED);

	rectangle(120,270,126,217);

	floodfill(121,227,15);

	setfillstyle(INTERLEAVE_FILL,RED);

	rectangle(150,270,156,217);

	floodfill(151,227,15);

	setfillstyle(INTERLEAVE_FILL,RED);

	rectangle(180,270,186,217);

	floodfill(181,227,15);



	line(123,210,123,217);

	line(153,210,153,217);

	line(183,210,183,217);





	setfillstyle(SOLID_FILL,YELLOW);

	ellipse(123,199,0,360,4,10);

	floodfill(123,199,15);

	setfillstyle(SOLID_FILL,YELLOW);

	ellipse(153,199,0,360,4,10);

	floodfill(152,199,15);

	setfillstyle(SOLID_FILL,YELLOW);

	ellipse(183,199,0,360,4,10);

	floodfill(183,199,15);

	settextstyle(7,0,10);

       //	outtextxy(290,230,"Rohit");  //Birthday boy Name



	while(kbhit()==0)

	{



	for(int z=0 ; z<400 ; z++)

	{



	       if(z>200)

	       {

		setfillstyle(SOLID_FILL,2);

		circle(7,10,7);

		floodfill(7,10,15);

		setfillstyle(SOLID_FILL,4);

		circle(35,10,7);

		floodfill(35,10,15);

		setfillstyle(SOLID_FILL,6);

		circle(60,10,7);

		floodfill(60,10,15);



		setfillstyle(SOLID_FILL,3);

		circle(90,10,7);

		floodfill(90,10,15);

		setfillstyle(SOLID_FILL,5);

		circle(120,10,7);

		floodfill(120,10,15);

		setfillstyle(SOLID_FILL,7);

		circle(150,10,7);

		floodfill(150,10,15);



			//1

		setfillstyle(SOLID_FILL,8);

		circle(180,10,7);

		floodfill(180,10,15);

		setfillstyle(SOLID_FILL,9);

		circle(210,10,7);

		floodfill(210,10,15);

		setfillstyle(SOLID_FILL,10);

		circle(240,10,7);

		floodfill(240,10,15);



		//2

		setfillstyle(SOLID_FILL,11);

		circle(270,10,7);

		floodfill(270,10,15);

		setfillstyle(SOLID_FILL,12);

		circle(300,10,7);

		floodfill(300,10,15);

		setfillstyle(SOLID_FILL,13);

		circle(330,10,7);

		floodfill(330,10,15);



		//3

		setfillstyle(SOLID_FILL,14);

		circle(360,10,7);

		floodfill(360,10,15);

		setfillstyle(SOLID_FILL,15);

		circle(390,10,7);

		floodfill(390,10,15);

		setfillstyle(SOLID_FILL,1);

		circle(420,10,7);

		floodfill(420,10,15);



		//4

		setfillstyle(SOLID_FILL,2);

		circle(450,10,7);

		floodfill(450,10,15);

		setfillstyle(SOLID_FILL,3);

		circle(480,10,7);

		floodfill(480,10,15);

		setfillstyle(SOLID_FILL,4);

		circle(510,10,7);

		floodfill(510,10,15);



		//5

		setfillstyle(SOLID_FILL,5);

		circle(540,10,7);

		floodfill(540,10,15);

		setfillstyle(SOLID_FILL,6);

		circle(570,10,7);

		floodfill(570,10,15);

		setfillstyle(SOLID_FILL,7);

		circle(598,10,7);

		floodfill(598,10,15);



		//buttom

		setfillstyle(SOLID_FILL,8);

		circle(7,470,7);

		floodfill(7,470,15);

		setfillstyle(SOLID_FILL,9);

		circle(35,470,7);

		floodfill(35,470,15);

		setfillstyle(SOLID_FILL,10);

		circle(60,470,7);

		floodfill(60,470,15);



		setfillstyle(SOLID_FILL,11);

		circle(90,470,7);

		floodfill(90,470,15);

		setfillstyle(SOLID_FILL,12);

		circle(120,470,7);

		floodfill(120,470,15);

		setfillstyle(SOLID_FILL,13);

		circle(150,470,7);

		floodfill(150,470,15);



		//1

		setfillstyle(SOLID_FILL,14);

		circle(180,470,7);

		floodfill(180,470,15);

		setfillstyle(SOLID_FILL,15);

		circle(210,470,7);

		floodfill(210,470,15);

		setfillstyle(SOLID_FILL,1);

		circle(240,470,7);

		floodfill(240,470,15);



		//2

		setfillstyle(SOLID_FILL,2);

		circle(270,470,7);

		floodfill(270,470,15);

		setfillstyle(SOLID_FILL,3);

		circle(300,470,7);

		floodfill(300,470,15);

		setfillstyle(SOLID_FILL,4);

		circle(330,470,7);

		floodfill(330,470,15);



		//3

		setfillstyle(SOLID_FILL,5);

		circle(360,470,7);

		floodfill(360,470,15);

		setfillstyle(SOLID_FILL,6);

		circle(390,470,7);

		floodfill(390,470,15);

		setfillstyle(SOLID_FILL,7);

		circle(420,470,7);

		floodfill(420,470,15);



		//4

		setfillstyle(SOLID_FILL,8);

		circle(450,470,7);

		floodfill(450,470,15);

		setfillstyle(SOLID_FILL,9);

		circle(480,470,7);

		floodfill(480,470,15);

		setfillstyle(SOLID_FILL,10);

		circle(510,470,7);

		floodfill(510,470,15);



		//5

		setfillstyle(SOLID_FILL,13);

		circle(540,470,7);

		floodfill(540,470,15);

		setfillstyle(SOLID_FILL,12);

		circle(570,470,7);

		floodfill(570,470,15);

		setfillstyle(SOLID_FILL,11);

		circle(598,470,7);

		floodfill(598,470,15);



		//happybirthday



		settextstyle(10,0,6);

		setcolor(13);

		outtextxy(14,20,"H");

		setcolor(4);

		outtextxy(60,20,"A");

		setcolor(9);

		outtextxy(110,20,"P");

		setcolor(10);

		outtextxy(155,20,"P");

		setcolor(8);

		outtextxy(196,20,"Y");



		setcolor(6);

		outtextxy(270,20,"B");

		setcolor(5);

		outtextxy(320,20,"I");

		setcolor(11);

		outtextxy(340,20,"R");

		setcolor(10);

		outtextxy(386,20,"T");

		setcolor(6);

		outtextxy(437,20,"H");

		setcolor(2);

		outtextxy(484,20,"D");

		setcolor(4);

		outtextxy(525,20,"A");

		setcolor(5);

		outtextxy(560,20,"Y");

		setcolor(15);

	       }



	       if(z<200)

	       {

		 //happyBirthday



		 settextstyle(10,0,6);

		setcolor(2);

		outtextxy(14,20,"H");

		setcolor(13);

		outtextxy(60,20,"A");

		setcolor(8);

		outtextxy(110,20,"P");

		setcolor(5);

		outtextxy(155,20,"P");

		setcolor(6);

		outtextxy(196,20,"Y");



		setcolor(9);

		outtextxy(270,20,"B");

		setcolor(10);

		outtextxy(320,20,"I");

		setcolor(11);

		outtextxy(340,20,"R");

		setcolor(12);

		outtextxy(386,20,"T");

		setcolor(2);

		outtextxy(437,20,"H");

		setcolor(4);

		outtextxy(484,20,"D");

		setcolor(5);

		outtextxy(525,20,"A");

		setcolor(6);

		outtextxy(560,20,"Y");

		setcolor(15);



	       //top



		setfillstyle(SOLID_FILL,RED);

		circle(7,10,7);

		floodfill(7,10,15);

		setfillstyle(SOLID_FILL,YELLOW);

		circle(35,10,7);

		floodfill(35,10,15);

		setfillstyle(SOLID_FILL,BLUE);

		circle(60,10,7);

		floodfill(60,10,15);



		setfillstyle(SOLID_FILL,RED);

		circle(90,10,7);

		floodfill(90,10,15);

		setfillstyle(SOLID_FILL,YELLOW);

		circle(120,10,7);

		floodfill(120,10,15);

		setfillstyle(SOLID_FILL,BLUE);

		circle(150,10,7);

		floodfill(150,10,15);



		//1

		setfillstyle(SOLID_FILL,RED);

		circle(180,10,7);

		floodfill(180,10,15);

		setfillstyle(SOLID_FILL,YELLOW);

		circle(210,10,7);

		floodfill(210,10,15);

		setfillstyle(SOLID_FILL,BLUE);

		circle(240,10,7);

		floodfill(240,10,15);



		//2

		setfillstyle(SOLID_FILL,RED);

		circle(270,10,7);

		floodfill(270,10,15);

		setfillstyle(SOLID_FILL,YELLOW);

		circle(300,10,7);

		floodfill(300,10,15);

		setfillstyle(SOLID_FILL,BLUE);

		circle(330,10,7);

		floodfill(330,10,15);



		//3

		setfillstyle(SOLID_FILL,RED);

		circle(360,10,7);

		floodfill(360,10,15);

		setfillstyle(SOLID_FILL,YELLOW);

		circle(390,10,7);

		floodfill(390,10,15);

		setfillstyle(SOLID_FILL,BLUE);

		circle(420,10,7);

		floodfill(420,10,15);



		//4

		setfillstyle(SOLID_FILL,RED);

		circle(450,10,7);

		floodfill(450,10,15);

		setfillstyle(SOLID_FILL,YELLOW);

		circle(480,10,7);

		floodfill(480,10,15);

		setfillstyle(SOLID_FILL,BLUE);

		circle(510,10,7);

		floodfill(510,10,15);



		//5

		setfillstyle(SOLID_FILL,RED);

		circle(540,10,7);

		floodfill(540,10,15);

		setfillstyle(SOLID_FILL,YELLOW);

		circle(570,10,7);

		floodfill(570,10,15);

		setfillstyle(SOLID_FILL,BLUE);

		circle(598,10,7);

		floodfill(598,10,15);



		//buttom

		setfillstyle(SOLID_FILL,RED);

		circle(7,470,7);

		floodfill(7,470,15);

		setfillstyle(SOLID_FILL,YELLOW);

		circle(35,470,7);

		floodfill(35,470,15);

		setfillstyle(SOLID_FILL,BLUE);

		circle(60,470,7);

		floodfill(60,470,15);



		setfillstyle(SOLID_FILL,RED);

		circle(90,470,7);

		floodfill(90,470,15);

		setfillstyle(SOLID_FILL,YELLOW);

		circle(120,470,7);

		floodfill(120,470,15);

		setfillstyle(SOLID_FILL,BLUE);

		circle(150,470,7);

		floodfill(150,470,15);



		//1

		setfillstyle(SOLID_FILL,RED);

		circle(180,470,7);

		floodfill(180,470,15);

		setfillstyle(SOLID_FILL,YELLOW);

		circle(210,470,7);

		floodfill(210,470,15);

		setfillstyle(SOLID_FILL,BLUE);

		circle(240,470,7);

		floodfill(240,470,15);



		//2

		setfillstyle(SOLID_FILL,RED);

		circle(270,470,7);

		floodfill(270,470,15);

		setfillstyle(SOLID_FILL,YELLOW);

		circle(300,470,7);

		floodfill(300,470,15);

		setfillstyle(SOLID_FILL,BLUE);

		circle(330,470,7);

		floodfill(330,470,15);



		//3

		setfillstyle(SOLID_FILL,RED);

		circle(360,470,7);

		floodfill(360,470,15);

		setfillstyle(SOLID_FILL,YELLOW);

		circle(390,470,7);

		floodfill(390,470,15);

		setfillstyle(SOLID_FILL,BLUE);

		circle(420,470,7);

		floodfill(420,470,15);



		//4

		setfillstyle(SOLID_FILL,RED);

		circle(450,470,7);

		floodfill(450,470,15);

		setfillstyle(SOLID_FILL,YELLOW);

		circle(480,470,7);

		floodfill(480,470,15);

		setfillstyle(SOLID_FILL,BLUE);

		circle(510,470,7);

		floodfill(510,470,15);



		//5

		setfillstyle(SOLID_FILL,RED);

		circle(540,470,7);

		floodfill(540,470,15);

		setfillstyle(SOLID_FILL,YELLOW);

		circle(570,470,7);

		floodfill(570,470,15);

		setfillstyle(SOLID_FILL,BLUE);

		circle(598,470,7);

		floodfill(598,470,15);

	       }



	}

	delay(3);

     }

}
