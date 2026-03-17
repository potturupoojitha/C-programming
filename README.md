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

//1.To print an integer reverse #include <stdio.h> void main() { int n,rev=0; scanf("%d",&n); while(n!=0) { int digit=n%10; rev=rev*10+digit; n=n/10; } printf("reversed=%d",rev); }

//2.To print a number is palindrome #include <stdio.h> void main() { int n,O,remainder,rev=0; scanf("%d",&n); O=n; while (n!=0) { remainder=n%10; rev=rev*10+digit; n=n/10; } if (O==rev) printf("palindrome"); else printf("not"); }

//3mTo print a number is amstrong number or not #include <stdio.h> void main() { int n,O,rev=0; scanf("%d",&n); O=n; while(n!=0) { int digit=n%10; rev=rev+digitdigitdigit; n=n/10; } if (rev==O) printf("amstrong no."rev); else printf("not",rev); }

//4.To print sum of digits #include <stdio.h> void main() { int n,digit,sum=0; scanf("%d",&n); while (n!=0) { digit=n%10; sum=sum+digit; n=n/10; } printf("sum=%d",sum); }

//5.To print a number is happy number #include <stdio.h> int main() { int n,O,digit,sum; scanf("%d",&n); O=n; while (O!=1&&O!=4) { sum=0; while (O>0) { digit=O%10; sum=sum+digit*digit; O=O/10; } O=sum; } if (O==1) printf("%d id happy number",n); else printf("%d is not happy number",n); return 0; }

//6.To print a number is automorphic #include <stdio.h> int main() { int n,sq,O; scanf("%d",&n); sq=n*n; O=n; while (O>0) { if (O%10!=sq%10) { printf("not"); return 0; } O=O/10; sq=sq/10; } printf("automorphic"); return 0; }

//7.To print a number is harshad number or not #include <stdio.h> void main() { int n,O,digit,sum=0; scanf("%d",&n); O=n; while(n!=0) { digit=n%10; sum=sum+digit; n=n/10; } n=sum; if(O%sum==0) { printf("harshad no."); }else{ printf("not") } }

//8.To print a number is magic number or not #include <stdio.h> int main() { int n,O,digit,sum; scanf("%d",&n); O=n; while(n>9) { sum=0; while(n!=0) { digit=n%10; sum=sum+digit; n=n/10; } n=sum; } if(n==1) printf("magic no."); else printf("not"); return 0; }

//9.To print even number using for loop #include <stdio.h> void main() { for (int i=1;i<=10;i++) { if(i%2==0) { printf("%d\n",i); } } }

//10.To find sum of n-natural numbers using for loop #include <stdio.h> void main() { int i,sum,=0,n; scanf("%d",&n); for (i=1;i<=10;i++) { sum=sum+i; } printf("sum=%d\n",sum); }

//11.to print first n even numbers using for loop #include <stdio.h> void main() { int i,sum=0,n; scanf("%d",&n); for (i=1;i<=n;i++) { if (i%2==0) { sum=sum+i; } } printf("%d\n",i); }

//12.To find factorial using for loop #include <stdio.h> void main() { int i,fact=1,n; scanf("%d",&n); for (i=1;i<=10;i++) { fact=fact*i; } printf("fact=%d\n",fact); }

//13.To print multiplication table #include <stdio.h> void main() { int i,n,m; scanf("%d",&n); for (i=1;i<=10;i++) { m=n*i } printf("%dX%d=%d\n",i,n,m); }

//14.To print factors of given number #include <stdio.h> void main() { int i,n; scanf("%d",&n); for (i=1;i<=n;i++) { if (n%i==0) printf("factors=%d\n",i); } }

//15.To find given number is perfect or not #include <stdio.h> void main() { int i,n,sum=0,t; scanf("%d",&n); for (i=1;i<=n;i++) { if (n%i==0) { sum=sum+i; } } if(t==sum) { printf("%d is perfect",t); }else{ printf("%d is not perfect",t); } }


//1.To find the given number is prime or not #include<stdio.h> void main() { int num,i,isPrime=1; printf("Enter the number: "); scanf("%d",&num); if (num<=1){ isPrime=0; } else{ for(i=2;i<=num/2;i++){ if(num%i==0){ isPrime=0; break; } } } if(isPrime){ printf("%d is a prime number"); } else{ printf("%d is not a prime number"); } }

//2.To find the prime numbers in a given set of numbers #include<stdio.h> int main() { int num,i,j,isPrime; printf("Enter the number: "); scanf("%d",&num); for(i=2;i<=num;i++){ isPrime=1; for(j=2;j<=i/2;j++){ if(i%j==0){ isPrime=0; break; } } if(isPrime){ printf("%d is a Prime number.\n",i); } } return 0; }

//3.Program to find the given pattern #include<stdio.h> int main() { int n,i,j; scanf("%d",&n); for (i=1;i<=5;i++) { for (j=1;j<=5;j++){ printf("*"); } printf("\n"); } return 0; }

//4.To print the hallow pattern #include<stdio.h> int main() { int n,i,j; scanf("%d",&n); for(i=1;i<=n;i++){ for(j=1;j<=n;j++){ if(i==1||i==n||j==1||j==n){ printf("*"); } else{ printf(" "); } } printf("\n"); } return 0; }

//5.To print the staircas of stars #include<stdio.h> int main() { int n,i,j; scanf("%d",&n); for (i=1;i<=n;i++){ for (j=1;j<=i;j++){ printf("*"); } printf("\n"); } return 0; }

//6.To print the given pattern #include<stdio.h> int main() { int n,i,j; scanf("%d",&n); for(i=1;i<=n;i++){ for(j=1;j<=i;j++){ printf("%d",i); } printf("\n"); } return 0; }

//7.To print the given pattern #include<stdio.h> int main() { int n,i,j; scanf("%d",&n); for (i=5;i.=1;i--){ for (j=1;j<=i;j++){ printf("*"); } printf("\n"); } return 0; }

//8.To print the given pattern #include<stdio.h> int main() { int n,i,j; scanf("%d",&n); for(i=5;i>=1;i--){ for(j=1;j<=i;j++){ printf("%d",j); } printf("\n"); }return 0; }

//9.To print the given pattern #include<stdio.h> int main() { int n,i,j; scanf("%d",&n); for(i=1;i<=n;i++){ for(j=1;j<=i;j++){ printf(""); } printf("\n"); } for (i=n-1;i>=1;i--){ for(j=1;j<=i;j++){ printf(""); } printf("\n"); } return 0;
}

//10.To print the given pattern #include<stdio.h> int main() { int i,j,s;
for(i=1;i<=5;i++){ for(s=1;s<=5-i;s++){ printf(" "); } for(j=1;j<=i;j++){ printf("* "); } printf("\n"); } return 0; }

//11.To print the given program #include<stdio.h> void main() { int i,j,n,num; num=1; scanf("%d",&n); for(i=1;i<=n;i++){ for(j=1;j<=i;j++){ printf("%d",num); num++; } printf("\n"); } }

//12.To print the given pattern #include<stdio.h> int main() { int n,i,j; scanf("%d",&n); for (i=1;i<=n;i++){ for (j=1;j<=n-j;j++){ printf(" "); } for(j=1;j<=(2i-1);j++){ if(i==1||i==n||j==1||j==(2i-1)){ printf("*"); } else{ printf(" "); } printf(" "); } printf("\n"); } return 0; }

//13.To print the palindrome number #include <stdio.h> int main() { int n, rev = 0, r, temp; printf("Enter a number: "); scanf("%d", &n); temp = n; while(n > 0) { r = n % 10; rev = rev * 10 + r; n = n / 10; } if(temp == rev) printf("Palindrome number"); else printf("Not a palindrome"); return 0; }


//To find the given number is prime or not #include<stdio.h> void main() { int num,i,isPrime=1; printf("Enter the number: "); scanf("%d",&num); if (num<=1){ isPrime=0; } else{ for(i=2;i<=num/2;i++){ if(num%i==0){ isPrime=0; break; } } } if(isPrime){ printf("%d is a prime number"); } else{ printf("%d is not a prime number"); } }

//To find the prime numbers in a given set of numbers #include<stdio.h> int main() { int num,i,j,isPrime; printf("Enter the number: "); scanf("%d",&num); for(i=2;i<=num;i++){ isPrime=1; for(j=2;j<=i/2;j++){ if(i%j==0){ isPrime=0; break; } } if(isPrime){ printf("%d is a Prime number.\n",i); } } return 0; }

//Program to find the given pattern #include<stdio.h> int main() { int n,i,j; scanf("%d",&n); for (i=1;i<=5;i++) { for (j=1;j<=5;j++){ printf("*"); } printf("\n"); } return 0; }

//To print the hallow pattern #include<stdio.h> int main() { int n,i,j; scanf("%d",&n); for(i=1;i<=n;i++){ for(j=1;j<=n;j++){ if(i==1||i==n||j==1||j==n){ printf("*"); } else{ printf(" "); } } printf("\n"); } return 0; }

//To print the staircas of stars #include<stdio.h> int main() { int n,i,j; scanf("%d",&n); for (i=1;i<=n;i++){ for (j=1;j<=i;j++){ printf("*"); } printf("\n"); } return 0; }

//To print the given pattern #include<stdio.h> int main() { int n,i,j; scanf("%d",&n); for(i=1;i<=n;i++){ for(j=1;j<=i;j++){ printf("%d",i); } printf("\n"); } return 0; }

//To print the given pattern #include<stdio.h> int main() { int n,i,j; scanf("%d",&n); for (i=5;i.=1;i--){ for (j=1;j<=i;j++){ printf("*"); } printf("\n"); } return 0; }

//To print the given pattern #include<stdio.h> int main() { int n,i,j; scanf("%d",&n); for(i=5;i>=1;i--){ for(j=1;j<=i;j++){ printf("%d",j); } printf("\n"); }return 0; }

//To print the given pattern #include<stdio.h> int main() { int n,i,j; scanf("%d",&n); for(i=1;i<=n;i++){ for(j=1;j<=i;j++){ printf(""); } printf("\n"); } for (i=n-1;i>=1;i--){ for(j=1;j<=i;j++){ printf(""); } printf("\n"); } return 0;
}

README
                                          //09-03-2026//Monday
//To display our name. #include<stdio.h> int main() { printf("My name is Pardhu"); printf("Welcome to SIMATS"); return 0; }

//To find area of square #include<stdio.h> int main() { int side; int area; scanf("%d",&side); area=side*side; printf("%d",area); return 0; }

//To add two integer values #include<stdio.h> int main() { int a,b; int c; scanf("%d%d",&a,&b); c=a+b; printf("%d",c); return 0; }

//add two floating points #include<stdio.h> int main() { float a,b; float sum; scanf("%f%f",&a,&b); sum=a+b; printf("%f",sum); return 0; }

//To find the area of circle #include<stdio.h> int main() { float r; float area; scanf("%f",&r); area=3.14rr; printf("%f",area); return 0; }

//To find area and perimeter of rectangle #include<stdio.h> int main() { int l,b,area,perimeter; scanf("%d%d",&l,&b); area=lb perimter=2(l+b); printf("%d",area); printf("%d",perimeter); return 0; }

//To find area of the traingle #include<stdio.h> int main() { float a,b,area; scanf("%f%f",&a,&b); area=0.5ab; printf("%f",area); return 0; }

//Converting celsius to fahrenheit scale #include<stdio.h> int main() { float C,F; scanf("%f",&C); F=(C*9/5)+32; printf("%f",F); return 0: }

//To convert Fahrenheit to celsius scale #include<stdio.h> int main() { float C,F; scanf("%f",&F); C=(F-32)*5/9; printf("%f",C); return 0; }

//To find the Simple interest #include<stdio.h> int main() { float P,T,R,SI; scanf("%f%f%f",&P,&T,&R); SI=(PTR)/100; printf("%f",SI); return 0; }

                                              //10-03-2026//Tuesday
//Find the area of circle #include<stdio.h> void main() { constant float pi=3.14; float r=10,area; area=pirr; printf("%.2f",area); }

//FInd the area of circle using define #include<stdio.h> #define pi 3.14 void main() { int r; float area; area=pirr; printf(".2f",area); }

//decimal to octal #include<stdio.h> void main() { int a=20; printf("Octal number=%o",a); }

//decimal to hexa #include<stdio.h> void main() { int a=20; printf("Hexadecimal=%x",a); }

//Octal to decimal #include<stdio.h> void main() { int a=010; printf("Decimal=%d",a); }

//Hexadecimal to decimal #include<stdio.h> void main() { int a=0x15; printf("Decimal=%d",a); }

//Print character and find ASCII value #include<stdio.h> void main() { char ch='g'; printf("ch=%c\n",ch); printf("ch=%d,hence an integer\n",ch); printf("ch1=%c\n,ch+1); printf("ch1=%d,hence an integer",ch+1); }

//To find quotient and ramainder #include<stdio.h> int main() { int a=5; int q,r; q=a/2; r=a%2; printf("Quotient=%d\n",q); print("Remainder=%d",r); return 0; }

//Area of traingle #include<stdio.h> int main() { int b=3,h=3; float area; area= (1/2.0)bh; printf("Area=%.2f",area); return }

//To swap two integers using third variable #include<stdio.h> int main() { int a=10,b=20,t; printf("a=%d\tb=%d\n",a,b); t=a; a=b; b=t; print("a=%d\tb=%d",a,b); return 0; }

//Swapping without third variable #include<stdio.h> int main() { int a=10,b=20; printf("a=%d\tb=%d\n",a,b); a=b; b=a/2; printf("a=%d\tb=%d",a,b); return 0; }

//To dispaly a number if it is negative #include<stdio.h> int main() { int number; scanf("%d",&number); if (number<0){ printf("You entered %d\n",number); } printf("The if statement is easy"); return 0; }

//To find whether a integer is odd or even #include<stdio.h> int main() { int n; printf("Enter the number= "); scanf("%d",&number); if (n%2==0){ printf("%d is even",n); } else{ printf("%d is odd",n); } return 0; }

//Eligible to vote or not #include<stdio.h> int main() { int age; printf("Enter the age ="); scanf("%d",&age); if (age>18) { print("%d is eligible to vote",age); } else{ printf("%d is not elligible to vote",age); } return 0; }

//To find a student pass or fail #include<stdio.h> int main() { int n; printf("Enter the n= "); scanf("%d",&n); if (n>=35) { printf("%dis pass",n); } else { printf("%d is fail",n); } return 0; }

//To convert days into months and days #include<stdio.h> int main() { int totaldays; int months,days; printf("Enter totaldays= "); scanf("%d",&totaldays); months=totaldays/30; days=totaldays%30; printf("months="%d/n",months); printf("days="%d",days); return 0; }

//To convert days into years,months and days #include<stdio.h> int main() { int Totaldays; int years,months,days; printf("Enter Totaldays="); scanf("%d",Totaldays); years=Totaldays/365; months=Totaldays%365; days=Totaldays%30; printf("Years=%d\n",years); printf("Months=%d\n",months); printf("Days=%d",days); return 0; }

//To find the grade of a student #include<stdio.h> int main() { int marks; printf("Enter the marks= "); if (marks<0||marks>100){ printf("Number is invaid"); } else if (marks>=90){ printf("Grade=S"); } else if (marks>=80){ printf("Grade=A"); } else if (marks>=70){ printf("Grade=B); } else if (marks>=60){ printf("Grade=C"); } else if (marks>=50){ printf("Grade=D"); } else(marks<50){ printf("Fail"); { return 0; }

//Finding the greatest number #include<stdio.h> int main() { int c=10,b=22,a=9; if (a>b){ if (a>c); printf("%d",a); else; printf("%d",c); } else{ if (b>=c); printf("%d",b); else; printf("%d",c); } return 0; }

                                              //11-03-2026//Wednesday
//To find the biggest among three #include<stdio.h> int main() { scanf("%d%d%d",&num1,&num2,&num3); if (num1>num2)&&(num1>num3) printf("max=",num1); } else if(num2>num3){ printf("Max=",num2); } else{ printf("Max=",num3); } return 0; }

//to check whether the number is in the range 01 to 100 #include<stdio.h> int main() { int num; scanf("%d",&num); if (num>=1&&num<=100){ printf("Within range"); } else{ printf("Not in range"); } return 0; }

//To find the character in the range a to z #include<stdio.h> int main() { char n; scanf("%c",&n); if(n>=a&&n<=z){ printf("Within range"); } else{ printf("Not in range"); } return 0; }

//To increment a value #include<stdio.h> void main() { int x,i; i=10; x=++i; printf("x:%d",x); printf("i:%d",i); }

//conditonal operators #include<stdio.h> void main() { int a=10,b=20; int max; max=(a>b)?a:b; printf("Maximum number=%d\n",max); }

//To find the day in a week
#include<stdio.h> int main() { int day; scanf("%d",&day); switch day;{ case 1: printf("Monday"); break; case 2: printf("Tuesday"); break; case 3: printf("Wednesday"); break; case 4: printf("Thursday"); break; case 5: printf("Friday"); break; case 6: printf("Saturday"); break; case 7: printf("Sunday"); break; default: printf("Invalid"); } return 0; }

//Program to break statement #include<stdio.h> int main() { int i; for (i=1;i<=10;i++){ if (i==5) break; printf("%d\n",i); }

//goto statement #include<stdio.h> int main() { int i=1; start: if(i<=5){ printf("%d\n",i); i++; goto start; } return 0; }

//continue statement #Finclude<stdio.h> int main() { int i; for (i=1;i<=10;i++){ if (i==5) continue: printf("%d\n",i); } return 0; }

//To describe one to ten #include<stdio.h> void main() { int i=1; while(i<=10) { printf("%d\n",i); i++; } printf("End"); }

//to describe odd numbers from one to 10 #include<stdio.h> void main() { int i=1; while(i<=10); if (i%2==1) { printf("%d",i); i++; } printf("End"); }

//to describe even numbers #include<stdio.h> void main() { int i=1; while(i<=10); if (i%2==0){ printf("%d\n",i); i++; } printf("End"); }

//To find the first 10 natural numbers #include<stdio.h> void main() { int i=1,sum=0; while(i<=10) { sum=sum+i; i++; } printf("Sum=%d\n",sum); printf("End"); }

//To find the sum of odd numbers #include<stdio.h> void main() { int i=1,sum=0; while(i<=10); if(i%2==1) { sum=sum+i; } i++; printf("Sum=%d\n",sum); printf("End"); }

//To find the sum of even numbers #include<stdio.h> void main() { int i=1,sum=0; while(i<=10); if(i%2==0) { sum=sum+i; } i++; printf("Sum=%d/n",sum); printf("End"); }

//To find the factorial of a given number #include<stdio.h> void main() { int i=1,factorial=1; whhile(i<=5) { factorial=factorial*i; i++; } printf("Factorial = %d/n",factorial); printf("End"); }

//To print the Fibomacci series #include<stdio.h> void main() { int i=0,first=0,second=1,next; while(i<=10) { printf("%d/n",first); next=first+second; first=second; second=next; i++; } }

//To print 1 to 10 in reverse order #include<stdio.h> void main() { int i=10; while (i>=1) { printf("%d/n",i); } printf("End"); }

//To check the number whether it is in the range of 1 to 1000 #include<stdio.h> int main() { int num; scanf("%d",&num); if(num>=1&&num<=1000){ printf("Within range"); } else{ printf("Not in range"); } return 0; }

//To check the number in the range of 1 to 200 #include<stdio.h> int main() { int num; scanf("%d",&num); if(num>=1&num<=200){ printf("Within range"); } else{ printf("Not in range"); } return 0; }

                                            //12-03-2026//Thursday
//To print an integer reverse #include <stdio.h> void main() { int n,rev=0; scanf("%d",&n); while(n!=0) { int digit=n%10; rev=rev*10+digit; n=n/10; } printf("reversed=%d",rev); }

//To print a number is palindrome #include <stdio.h> void main() { int n,O,remainder,rev=0; scanf("%d",&n); O=n; while (n!=0) { remainder=n%10; rev=rev*10+digit; n=n/10; } if (O==rev) printf("palindrome"); else printf("not"); }

//To print a number is amstrong number or not #include <stdio.h> void main() { int n,O,rev=0; scanf("%d",&n); O=n; while(n!=0) { int digit=n%10; rev=rev+digitdigitdigit; n=n/10; } if (rev==O) printf("amstrong no."rev); else printf("not",rev); }

//To print sum of digits #include <stdio.h> void main() { int n,digit,sum=0; scanf("%d",&n); while (n!=0) { digit=n%10; sum=sum+digit; n=n/10; } printf("sum=%d",sum); }

//To print a number is happy number #include <stdio.h> int main() { int n,O,digit,sum; scanf("%d",&n); O=n; while (O!=1&&O!=4) { sum=0; while (O>0) { digit=O%10; sum=sum+digit*digit; O=O/10; } O=sum; } if (O==1) printf("%d id happy number",n); else printf("%d is not happy number",n); return 0; }

//To print a number is automorphic #include <stdio.h> int main() { int n,sq,O; scanf("%d",&n); sq=n*n; O=n; while (O>0) { if (O%10!=sq%10) { printf("not"); return 0; } O=O/10; sq=sq/10; } printf("automorphic"); return 0; }

//To print a number is harshad number or not #include <stdio.h> void main() { int n,O,digit,sum=0; scanf("%d",&n); O=n; while(n!=0) { digit=n%10; sum=sum+digit; n=n/10; } n=sum; if(O%sum==0) { printf("harshad no."); }else{ printf("not") } }

//To print a number is magic number or not #include <stdio.h> int main() { int n,O,digit,sum; scanf("%d",&n); O=n; while(n>9) { sum=0; while(n!=0) { digit=n%10; sum=sum+digit; n=n/10; } n=sum; } if(n==1) printf("magic no."); else printf("not"); return 0; }

//To print even number using for loop #include <stdio.h> void main() { for (int i=1;i<=10;i++) { if(i%2==0) { printf("%d\n",i); } } }

//To find sum of n-natural numbers using for loop #include <stdio.h> void main() { int i,sum,=0,n; scanf("%d",&n); for (i=1;i<=10;i++) { sum=sum+i; } printf("sum=%d\n",sum); }

//to print first n even numbers using for loop #include <stdio.h> void main() { int i,sum=0,n; scanf("%d",&n); for (i=1;i<=n;i++) { if (i%2==0) { sum=sum+i; } } printf("%d\n",i); }

//To find factorial using for loop #include <stdio.h> void main() { int i,fact=1,n; scanf("%d",&n); for (i=1;i<=10;i++) { fact=fact*i; } printf("fact=%d\n",fact); }

//To print multiplication table #include <stdio.h> void main() { int i,n,m; scanf("%d",&n); for (i=1;i<=10;i++) { m=n*i } printf("%dX%d=%d\n",i,n,m); }

//To print factors of given number #include <stdio.h> void main() { int i,n; scanf("%d",&n); for (i=1;i<=n;i++) { if (n%i==0) printf("factors=%d\n",i); } }

//To find given number is perfect or not #include <stdio.h> void main() { int i,n,sum=0,t; scanf("%d",&n); for (i=1;i<=n;i++) { if (n%i==0) { sum=sum+i; } } if(t==sum) { printf("%d is perfect",t); }else{ printf("%d is not perfect",t); }

                                            //13-03-2026//Friday
//To find the given number is prime or not #include<stdio.h> void main() { int num,i,isPrime=1; printf("Enter the number: "); scanf("%d",&num); if (num<=1){ isPrime=0; } else{ for(i=2;i<=num/2;i++){ if(num%i==0){ isPrime=0; break; } } } if(isPrime){ printf("%d is a prime number"); } else{ printf("%d is not a prime number"); } }

//To find the prime numbers in a given set of numbers #include<stdio.h> int main() { int num,i,j,isPrime; printf("Enter the number: "); scanf("%d",&num); for(i=2;i<=num;i++){ isPrime=1; for(j=2;j<=i/2;j++){ if(i%j==0){ isPrime=0; break; } } if(isPrime){ printf("%d is a Prime number.\n",i); } } return 0; }

//Program to find the given pattern #include<stdio.h> int main() { int n,i,j; scanf("%d",&n); for (i=1;i<=5;i++) { for (j=1;j<=5;j++){ printf("*"); } printf("\n"); } return 0; }

//To print the hallow pattern #include<stdio.h> int main() { int n,i,j; scanf("%d",&n); for(i=1;i<=n;i++){ for(j=1;j<=n;j++){ if(i==1||i==n||j==1||j==n){ printf("*"); } else{ printf(" "); } } printf("\n"); } return 0; }

//To print the staircas of stars #include<stdio.h> int main() { int n,i,j; scanf("%d",&n); for (i=1;i<=n;i++){ for (j=1;j<=i;j++){ printf("*"); } printf("\n"); } return 0; }

//To print the given pattern #include<stdio.h> int main() { int n,i,j; scanf("%d",&n); for(i=1;i<=n;i++){ for(j=1;j<=i;j++){ printf("%d",i); } printf("\n"); } return 0; }

//To print the given pattern #include<stdio.h> int main() { int n,i,j; scanf("%d",&n); for (i=5;i.=1;i--){ for (j=1;j<=i;j++){ printf("*"); } printf("\n"); } return 0; }

//To print the given pattern #include<stdio.h> int main() { int n,i,j; scanf("%d",&n); for(i=5;i>=1;i--){ for(j=1;j<=i;j++){ printf("%d",j); } printf("\n"); }return 0; }

//To print the given pattern #include<stdio.h> int main() { int n,i,j; scanf("%d",&n); for(i=1;i<=n;i++){ for(j=1;j<=i;j++){ printf(""); } printf("\n"); } for (i=n-1;i>=1;i--){ for(j=1;j<=i;j++){ printf(""); } printf("\n"); } return 0;

}

//To print the given pattern #include<stdio.h> int main() { int i,j,s;

for(i=1;i<=5;i++){
    for(s=1;s<=5-i;s++){
        printf(" ");
    }
    for(j=1;j<=i;j++){
        printf("* ");
    }
    printf("\n");
}
return 0;
}

//To print the given program #include<stdio.h> void main() { int i,j,n,num; num=1; scanf("%d",&n); for(i=1;i<=n;i++){ for(j=1;j<=i;j++){ printf("%d",num); num++; } printf("\n"); } }

//To print the given pattern #include<stdio.h> int main() { int n,i,j; scanf("%d",&n); for (i=1;i<=n;i++){ for (j=1;j<=n-j;j++){ printf(" "); } for(j=1;j<=(2i-1);j++){ if(i==1||i==n||j==1||j==(2i-1)){ printf("*"); } else{ printf(" "); } printf(" "); } printf("\n"); } return 0; }

//To print the palindrome number #include <stdio.h> int main() { int n, rev = 0, r, temp; printf("Enter a number: "); scanf("%d", &n); temp = n; while(n > 0) { r = n % 10; rev = rev * 10 + r; n = n / 10; } if(temp == rev) printf("Palindrome number"); else printf("Not a palindrome"); return 0; }

//To find the sum of n natural numbers #include<stdio.h> void main() { int i=1,sum=0; while(i<=10){ sum=sum+i; i++; } printf("Sum=%d\n",sum); printf("END"); }

//To find the LCM of two integers #include <stdio.h> int main() { int a, b, max, lcm; printf("Enter two numbers: "); scanf("%d %d", &a, &b); max = (a > b) ? a : b; while(1) { if(max % a == 0 && max % b == 0) { lcm = max; break; } max++; } printf("LCM = %d", lcm); return 0; }

//To find the sum of digits #include <stdio.h> int main() { int n, sum = 0, r; printf("Enter number: "); scanf("%d", &n); while(n > 0) { r = n % 10; sum = sum + r; n = n / 10; } printf("Sum of digits = %d", sum); return 0; }

//To find whether the given number is armstrong ar not #include<stdio.h> int main() { int n,r,sum=0,temp; scanf("%d",&n); temp=n; while(n>0){ r=n%10; sum=sum+(rrr); n=n/10; } if sum==temp;{ printf("Armstrong number"); } else{ printf("Not"); }

//To reverse the number #include <stdio.h> int main() { int n, rev = 0, r; printf("Enter a number: "); scanf("%d", &n); while(n > 0) { r = n % 10; rev = rev * 10 + r; n = n / 10; } printf("Reversed number = %d", rev); return 0; }

//To find the fibonacci series #include <stdio.h> int main() { int n, a = 0, b = 1, c, i; printf("Enter number of terms: "); scanf("%d", &n); printf("Fibonacci Series:\n"); for(i = 1; i <= n; i++) { printf("%d ", a); c = a + b; a = b; b = c; } return 0; }

#iclude<stdio.h> void main() { int i,a[5]; scanf("%d",&n); printf("Enter the integer: ); for (i=0;i=n;i++) { scanf("%d",&a[i]); } printf("Displaying Integers: "); for (int i=0;i<n;++i){ printf("%d"\n",a[i]); } }

//To make the arrays in reverse order #include<stdio.h> void main() { int i,n,a[100]; scanf("%d",&n); for(i=0;i<n;++i){ scanf("%d",a[i]); } for(int i=n-1;;i>=0;i--){ printf("%d",a[i]); } }

//To find the sum of the array elements #include<stdio.h> void main() { int i,n,a[100]; scanf("%d",&n); printf("Enter the number: "); for (i=0;i<n;i++){ scanf("%d",a[i]);} for(i=0;i<=n;i++){ sum=sum+a[i]; printf("Sum%d=",sum); } }

//To find the average of array elements #include<stdio.h> void main() { int i,n,a[100],sum=0,avg; scanf("%d",&n); printf("Enter the integer: "); for (i=0;i<n;i++){ scanf("%d",&a[i]); for(i=0;i<=n;i++){ sum=sum+a[i]; } avg=float(sum)/a[i]; printf("Avg %d=",avg); } }

//To find the largest element #include<stdio.h> void main() { int i,n,a[100],largest; printf("Enter number of elements: "); scanf("%d",&n); printf("Enter the integers:\n"); for(i=0;i<n;i++) { scanf("%d",&a[i]); } largest = a[0]; for(i=1;i<n;i++) { if(a[i] > largest) { largest = a[i]; } } printf("Largest element = %d",largest); }

//To find the given elment in a array #include<stdio.h> void main() { int i,n,a[100],key,flag=0; printf("Enter number of elements: "); scanf("%d",&n); printf("Enter the integers:\n"); for(i=0;i<n;i++) { scanf("%d",&a[i]); } printf("Enter element to search: "); scanf("%d",&key); for(i=0;i<n;i++) { if(a[i] == key) { flag = 1; break; } } if(flag == 1) printf("Element found"); else printf("Element not found"); }

//To find the smallest integer in an array #include<stdio.h> void main() { int i,n,a[100],smallest; printf("Enter number of elements: "); scanf("%d",&n); printf("Enter the integers:\n"); for(i=0;i<n;i++) { scanf("%d",&a[i]); } smallest = a[0]; for(i=1;i<n;i++) { if(a[i] < smallest) { smallest = a[i]; } } printf("Smallest element = %d",smallest); }

//To count even and odd numbers in array #include<stdio.h> void main() { int i,n,a[100],even=0,odd=0; printf("Enter number of elements: "); scanf("%d",&n); printf("Enter the integers:\n"); for(i=0;i<n;i++) { scanf("%d",&a[i]); } for(i=0;i<n;i++) { if(a[i] % 2 == 0) { even++; } else { odd++; } } printf("Even numbers = %d\n",even); printf("Odd numbers = %d",odd); }

//To sort the elements in ascending order #include<stdio.h> void main() { int i,j,n,a[100],temp; printf("Enter number of elements: "); scanf("%d",&n); printf("Enter the integers:\n"); for(i=0;i<n;i++) { scanf("%d",&a[i]); } for(i=0;i<n;i++) { for(j=i+1;j<n;j++) { if(a[i] > a[j]) { temp = a[i]; a[i] = a[j]; a[j] = temp; } } } printf("Array in ascending order:\n"); for(i=0;i<n;i++) { printf("%d ",a[i]); } }

//To sort the element sin the array descending order #include<stdio.h> void main() { int i,j,n,a[100],temp; printf("Enter number of elements: "); scanf("%d",&n); printf("Enter the integers:\n"); for(i=0;i<n;i++) { scanf("%d",&a[i]); } for(i=0;i<n;i++) { for(j=i+1;j<n;j++) { if(a[i] < a[j]) { temp = a[i]; a[i] = a[j]; a[j] = temp; } } } printf("Array in descending order:\n"); for(i=0;i<n;i++) { printf("%d ",a[i]); } }

//To count the positive and negative number in an array #include<stdio.h> void main() { int i,n,a[100],positive=0,negative=0; printf("Enter number of elements: "); scanf("%d",&n); printf("Enter the integers:\n"); for(i=0;i<n;i++) { scanf("%d",&a[i]); } for(i=0;i<n;i++) { if(a[i] > 0) { positive++; } else if(a[i] < 0) { negative++; } } printf("Positive numbers = %d\n",positive); printf("Negative numbers = %d",negative); }

//To find the second largest in an array #include<stdio.h> void main() { int i,n,a[100],largest,second; printf("Enter number of elements: "); scanf("%d",&n); printf("Enter the integers:\n"); for(i=0;i<n;i++) { scanf("%d",&a[i]); } largest = a[0]; second = a[0]; for(i=1;i<n;i++) { if(a[i] > largest) { second = largest; largest = a[i]; } else if(a[i] > second && a[i] != largest) { second = a[i]; } } printf("Second largest element = %d",second); }}



//To enter yuour name using string #include<stdio.h> int main() { char name[20]; printf("Enter your name: "); scanf("%s",name); printf("Your name is %s",name); return 0; }

//To fidn the length of the string #include<stdio.h> #include<string.h> int main() { char str[50]="POOJITHA"; int len=strlen(str); printf("Length of the string:%d",len); return 0; }

//To find the lowercase,uppercase and string reverse #include<stdio.h> #include<string.h> int main() { char str[50]="POOJITHA"; char str1[50]="poojitha"; char str2[50]="POOJITHA"; strlwr(str); strupr(str1); strrev(str2); printf("In uppercase:%s\n",str); printf("In lowercase:%s\n",str1); printf("In reverse:%s",str2); return 0; }

//To compare two strings #include<stdio.h> #include<string.h> int main() { char s1[20]="YOSHNA"; char s2[20]="YAVANIKA"; if(strcmp(s1,s2)==0){ printf("s1 and s2 are equal"); } else{ printf("s1 and s2 are not equal"); } return 0; }

//To concatenation a string #include<stdio.h> int main() { char s1[50]="POTHURU"; char s2[30]="POOJITHA"; strcat(s1,s2); printf("After concatenation:%s",s1); return 0; }

//To copy a string into another #include<stdio.h> int main() { char s1[30]="pothuru"; char s2[30]="poojitha"; strcpy(s1,s2); printf("Output string copy:%s",s1); return 0; }

//To find the string lenght without using string ffunction #include<stdio.h> int main() { char str[30]="POOJITHA"; //gets [str] int i=0,len=0; while (str[i]!='\0'){ len++; i++; } printf("Length of the string:%d",str); return 0; }

//To count the no of words in the given statement #include<stdio.h> #include<string.h> int main() { char [50]="POTHURU POOJITHA"; int i; count=1; for (i=0;str[i]!='\0';i++){ if(str[i]==' '){ count++; } } printf("No.of words:%d",count); return 0; }

//To concatenate without using string function #include<stdio.h> int main() { char str1[20]="POTHURU"; char str2[20]="POOJITHA"; int i=0,j=0; while(str1[i]!='\0'){ i++;} str1[i]=str2[j]; while (str2[j]!='\0'){ i++; j++; } str1[i]='\0'; printf("Concatenated string=%s",str1); return 0; }

//To convert to uppercase without using str function #include<stdio.h> int main() { char str[20]="poojitha" int i=0; while(str[i]!='\0'){ if (str[i]>='a'&&str[i]<='z'){ str[i]=str[i]-32; } i++; } printf(str); return 0; }

//to convert into lower case letters without uing the the string fuctions #include<stdio.h> int main() { int i=0; char str[20]="POOJITHA"; int i=0; while (str[i]>='A'&&str[i]<='Z'){ str[i]=str[i]+32; } i++; printf(str); return 0; }

//To reverse a string without string functions #include<stdio.h> #include<string.h> int main() { char str[20]="POOJITHA"; char rev[20]; int i,j=0,l; l=strlen(str); for (i=l-1;i>=0;i--){ reev[j]=str[i]; j++; } rev[j]='\0'; printf("Reverse string:%s",rev); return 0; }

//To print the palindrome using string #include<stdio.h> #include<string.h> void main() { char str[20]="malayalam"; int i,length,flag=0; length =strlen(str); for (i=0;i<length;i++){ if(str[i]!=str[length-i-1]){ flag=1; break; } } if (flag==1){ printf("%s is not a palindrome",str); } else{ printf("%s is a palindrome",str); } return 0; }

//To count the no of vowels and consonants in a sentence #include<stdio.h> void main() { char sentence[30]="pothuru poojitha"; int i,vowels=0,consonants=0; char ch; for(i=0;sentence[i]!='\0';i++){ ch=sentence[i]; if(ch>='a'&&ch<='z'){ if(ch=='a'||ch=='e'||ch=='i'||ch=='o'||ch=='u') vowels++; else consonants++; } } printf("No.of vowels=%d\n",vowels); printf("No of consonants=%d\n",consonants); }

//To remove the duplicates #include<stdio.h> #include<string.h>
int main() { char str[100] = "poojitha"; int i,j,k,length; length = strlen(str); for(i=0;i<length;i++) { for(j=i+1;j<length;j++) { if(str[i] == str[j]) { for(k=j;k<length;k++) { str[k] = str[k+1]; } length--; j--; } } } printf("String after removing duplicates: %s",str); return 0; }

//To check if the given string is a pangram #include<stdio.h> #include<string.h>

int main() { char str[200] = "the quick brown fox jumps over the lazy dog"; int i, index; int alphabet[26] = {0}; int flag = 1; for(i=0; str[i] != '\0'; i++) { if(str[i] >= 'a' && str[i] <= 'z') { index = str[i] - 'a'; alphabet[index] = 1; } else if(str[i] >= 'A' && str[i] <= 'Z') { index = str[i] - 'A'; alphabet[index] = 1; } }

for(i=0;i<26;i++) { if(alphabet[i] == 0) { flag = 0; break; } } if(flag == 1) printf("The string is a Pangram"); else printf("The string is not a Pangram"); return 0; }
