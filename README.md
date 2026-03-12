//1.To display our name.
#include<stdio.h>
int main()
{
printf("My name is POOJITHA"); 
printf("Welcome to SIMATS"); 
return 0;
}

//2.To find area of square 
#include<stdio.h> 
int main() 
{ 
int side; 
int area; 
scanf("%d",&side);
area=side*side; 
printf("%d",area); 
return 0; 
}

//3.To add two integer values
#include<stdio.h> 
int main() 
{ 
int a,b; 
int c; 
scanf("%d%d",&a,&b); 
c=a+b;
printf("%d",c); 
return 0; 
}

//4.add two floating points 
#include<stdio.h> 
int main() 
{ 
float a,b;
float sum;
scanf("%f%f",&a,&b);
sum=a+b; 
printf("%f",sum);
return 0; 
}

//5.To find the area of circle
#include<stdio.h> 
int main()
{ 
float r; 
float area; 
scanf("%f",&r); 
area=3.14rr; 
printf("%f",area); 
return 0; 
}

//6.To find area and perimeter of rectangle
#include<stdio.h>
int main()
{
int l,b,area,perimeter;
scanf("%d%d",&l,&b); 
area=lb;
perimter=2(l+b);
printf("%d",area); 
printf("%d",perimeter);
return 0; 
}

//7.To find area of the traingle
#include<stdio.h> int main()
{ 
float a,b,area; 
scanf("%f%f",&a,&b); 
area=0.5ab; 
printf("%f",area);
return 0; 
}

//8.Converting celsius to fahrenheit scale 
#include<stdio.h> 
int main()
{ float C,F; 
scanf("%f",&C);
F=(C*9/5)+32; 
printf("%f",F); 
return 0; 
}

//9.To convert Fahrenheit to celsius scale
#include<stdio.h> 
int main()
{ 
float C,F; 
scanf("%f",&F);
C=(F-32)*5/9;
printf("%f",C);
return 0; 
}

//10.To find the Simple interest
#include<stdio.h>
int main() 
{ 
float P,T,R,SI;
scanf("%f%f%f",&P,&T,&R);
SI=(PTR)/100; 
printf("%f",SI);
return 0; 
}


//1.Find the area of circle #include<stdio.h> void main() { constant float pi=3.14; float r=10,area; area=pirr; printf("%.2f",area); }

//2.FInd the area of circle using define #include<stdio.h> #define pi 3.14 void main() { int r; float area; area=pirr; printf(".2f",area); }

//3.decimal to octal #include<stdio.h> void main() { int a=20; printf("Octal number=%o",a); }

//4.decimal to hexa #include<stdio.h> void main() { int a=20; printf("Hexadecimal=%x",a); }

//5.Octal to decimal #include<stdio.h> void main() { int a=010; printf("Decimal=%d",a); }

//6.Hexadecimal to decimal #include<stdio.h> void main() { int a=0x15; printf("Decimal=%d",a); }

//7.Print character and find ASCII value #include<stdio.h> void main() { char ch='g'; printf("ch=%c\n",ch); printf("ch=%d,hence an integer\n",ch); printf("ch1=%c\n,ch+1); printf("ch1=%d,hence an integer",ch+1); }

//8.To find quotient and ramainder #include<stdio.h> int main() { int a=5; int q,r; q=a/2; r=a%2; printf("Quotient=%d\n",q); print("Remainder=%d",r); return 0; }

//9.Area of traingle #include<stdio.h> int main() { int b=3,h=3; float area; area= (1/2.0)bh; printf("Area=%.2f",area); return }

//10.To swap two integers using third variable #include<stdio.h> int main() { int a=10,b=20,t; printf("a=%d\tb=%d\n",a,b); t=a; a=b; b=t; print("a=%d\tb=%d",a,b); return 0; }

//11.Swapping without third variable #include<stdio.h> int main() { int a=10,b=20; printf("a=%d\tb=%d\n",a,b); a=b; b=a/2; printf("a=%d\tb=%d",a,b); return 0; }

//12.To dispaly a number if it is negative #include<stdio.h> int main() { int number; scanf("%d",&number); if (number<0){ printf("You entered %d\n",number); } printf("The if statement is easy"); return 0; }

//13.To find whether a integer is odd or even #include<stdio.h> int main() { int n; printf("Enter the number= "); scanf("%d",&number); if (n%2==0){ printf("%d is even",n); } else{ printf("%d is odd",n); } return 0; }

//14.Eligible to vote or not #include<stdio.h> int main() { int age; printf("Enter the age ="); scanf("%d",&age); if (age>18) { print("%d is eligible to vote",age); } else{ printf("%d is not elligible to vote",age); } return 0; }

//15.To find a student pass or fail #include<stdio.h> int main() { int n; printf("Enter the n= "); scanf("%d",&n); if (n>=35) { printf("%dis pass",n); } else { printf("%d is fail",n); } return 0;
} 
//16.To convert days into months and days #include<stdio.h> int main() { int totaldays; int months,days; printf("Enter totaldays= "); scanf("%d",&totaldays); months=totaldays/30; days=totaldays%30; printf("months="%d/n",months); printf("days="%d",days); return 0; }

//17.To convert days into years,months and days #include<stdio.h> int main() { int Totaldays; int years,months,days; printf("Enter Totaldays="); scanf("%d",Totaldays); years=Totaldays/365; months=Totaldays%365; days=Totaldays%30; printf("Years=%d\n",years); printf("Months=%d\n",months); printf("Days=%d",days); return 0; }

//18.To find the grade of a student #include<stdio.h> int main() { int marks; printf("Enter the marks= "); if (marks<0||marks>100){ printf("Number is invaid"); } else if (marks>=90){ printf("Grade=S"); } else if (marks>=80){ printf("Grade=A"); } else if (marks>=70){ printf("Grade=B); } else if (marks>=60){ printf("Grade=C"); } else if (marks>=50){ printf("Grade=D"); } else(marks<50){ printf("Fail"); { return 0; }

//19.Finding the greatest number #include<stdio.h> int main() { int c=10,b=22,a=9; if (a>b){ if (a>c); printf("%d",a); else; printf("%d",c); } else{ if (b>=c); printf("%d",b); else; printf("%d",c); } return 0;
}
//20.To find a student pass or fail
#include<stdio.h> 
int main() {
int n;
printf("Enter the n= "); 
scanf("%d",&n); 
if (n>=35) {
printf("%dis pass",n); 
}
else {
printf("%d is fail",n);
}
return 0;
}

11-03-2026//Wednesday

//1.To find the biggest among three
#include<stdio.h>
int main() {
scanf("%d%d%d",&num1,&num2,&num3);
if (num1>num2)&&(num1>num3)
printf("max=",num1);
}
else
if(num2>num3){
printf("Max=",num2);
}
else{
printf("Max=",num3); 
}
return 0;
}

//2.to check whether the number is in the range 01 to 100 
#include<stdio.h> 
int main() {
int num;
scanf("%d",&num);
if (num>=1&&num<=100){
printf("Within range");
} 
else{
printf("Not in range");
}
return 0;
}

//3.To find the character in the range a to z
#include<stdio.h> 
int main() {
char n; 
scanf("%c",&n);
if(n>=a&&n<=z){
printf("Within range");
}
else{ 
printf("Not in range"); 
}
return 0;
}

//4.To increment a value 
#include<stdio.h> 
void main(){
int x,i;
i=10;
x=++i;
printf("x:%d",x);
printf("i:%d",i);
}

//5.conditonal operators
#include<stdio.h>
void main()
{ int a=10,b=20; 
int max; 
max=(a>b)?a:b;
printf("Maximum number=%d\n",max);
}

//6.To find the day in a week
#include<stdio.h> 
int main() 
{ int day; 
scanf("%d",&day); 
switch day;
{ case 1:
printf("Monday"); 
break; 
case 2:
printf("Tuesday");
break;
case 3: 
printf("Wednesday");
break;
case 4:
printf("Thursday"); 
break; 
case 5:
printf("Friday");
break;
case 6:
printf("Saturday");
break;
case 7: 
printf("Sunday");
break; 
default:
printf("Invalid");
}
return 0;
}

//7.Program to break statement
#include<stdio.h>
int main() { 
int i;
for (i=1;i<=10;i++){
if (i==5) break; 
printf("%d\n",i);
}

//8.go to statement 
#include<stdio.h>
int main()
{ int i=1;
start: if(i<=5){
printf("%d\n",i);
i++;
goto start;
}
return 0;
}

//9.continue statement 
#include<stdio.h>
int main() 
{
int i; 
for (i=1;i<=10;i++){
if (i==5) continue:
printf("%d\n",i);
}
return 0;
}

//10.To describe one to ten 
#include<stdio.h>
void main() 
{
int i=1; while(i<=10)
{
printf("%d\n",i);
i++; 
}
printf("End");
}

//11.to describe odd numbers from one to 10
#include<stdio.h>
void main()
{ 
int i=1;
while(i<=10);
if (i%2==1) 
{
printf("%d",i); i++;
}
printf("End"); 
}

//12.to describe even numbers
#include<stdio.h>
void main() 
{
int i=1; 
while(i<=10);
if (i%2==0)
{
printf("%d\n",i);
i++; 
}
printf("End");
}

//13.To find the first 10 natural numbers 
#include<stdio.h> 
void main() {
int i=1,sum=0;
while(i<=10)
{ 
sum=sum+i;
i++;
}
printf("Sum=%d\n",sum); 
printf("End");
}

//14.To find the sum of odd numbers
#include<stdio.h>
void main() {
int i=1,sum=0;
while(i<=10);
if(i%2==1) {
sum=sum+i; 
}
i++; 
printf("Sum=%d\n",sum);
printf("End");
}

//15.To find the sum of even numbers 
#include<stdio.h> 
void main() {
int i=1,sum=0;
while(i<=10); 
if(i%2==0)
{
sum=sum+i;
}
i++;
printf("Sum=%d/n",sum);
printf("End");
}

//16.To find the factorial of a given number 
#include<stdio.h> 
void main() {
int i=1,factorial=1;
whhile(i<=5) {
factorial=factorial*i;
i++;
}
printf("Factorial = %d/n",factorial); 
printf("End"); 
}

//17.To print the Fibomacci series
#include<stdio.h> 
void main() {
int i=0,first=0,second=1,next; 
while(i<=10) {
printf("%d/n",first);
next=first+second;
first=second; 
second=next;
i++; 
}
}

//18.To print 1 to 10 in reverse order 
#include<stdio.h> 
void main() 
{
int i=10;
while (i>=1) {
printf("%d/n",i);
}
printf("End");
}

//19.To check the number whether it is in the range of 1 to 1000 
#include<stdio.h>
int main() {
int num;
scanf("%d",&num); 
if(num>=1&&num<=1000){
printf("Within range");
}
else{ 
printf("Not in range");
}
return 0;
}

//20.To check the number in the range of 1 to 200 
#include<stdio.h>
int main() {
int num; 
scanf("%d",&num);
if(num>=1&num<=200){
printf("Within range"); 
}
else{
printf("Not in range");
}
return 0;
}

//21.to check whether the number is in the range 01 to 100 
#include<stdio.h>
int main() {
int num;
scanf("%d",&num);
if (num>=1&&num<=100){
printf("Within range");
}
else{ 
printf("Not in range");
} 
return 0;
}

//22.To find the character in the range a to z
#include<stdio.h> 
int main() {
char n; 
scanf("%c",&n);
if(n>=a&&n<=z){ 
printf("Within range");
}
else{ 
printf("Not in range");
}
return 0;
}


//23.To increment a value 
#include<stdio.h> 
void main() {
int x,i;
i=10;
x=++i;
printf("x:%d",x);
printf("i:%d",i);
}

//24.conditonal operators 
#include<stdio.h>
void main() {
int a=10,b=20; 
int max; 
max=(a>b)?a:b;
printf("Maximum number=%d\n",max); 
}

//25.To check the number in the range of 1 to 200 
#include<stdio.h> 
int main() {
int num; 
scanf("%d",&num); 
if(num>=1&num<=200){
printf("Within range");
}
else{ 
printf("Not in range");
}
return 0;
}
