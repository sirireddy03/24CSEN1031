#include <stdio.h>

int main() {
 int a=3,b=1,c=8,d=10,temporary;
 printf("\nbefore  sorting: a=%d,b=%d,c=%d,d=%d ",a,b,c,b);
 if(a>b){
    temporary=a; a=b; b=temporary;
 }
 if(a>c){
    temporary=a; a=c; c=temporary;
 }
 if(b>c){
    temporary=b; b=c; c=temporary;
 }
 if(c>d){
    temporary=c; c=d; d=temporary;
 }
if(b>c){
    temporary=b; b=c; c=temporary;
 }
 if(a>d){
    temporary=a; a=d; d=temporary;
 }
 if(b>d){
     temporary=b; b=d; d=temporary;
     
 }
 printf("\nafter sorting: a=%d,b=%d,c=%d,d=%d",a,b,c,d);
return 0;
