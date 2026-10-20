# count-vowels-by-string-

#include<iostream>
#include<string>
 using namespace std;
     int main(){
         string str;
         int vowels=0;

         cout<<"enter a string ";
         getline(cin,str);

         int ch;
         for(int i=0;i<str.length();i++){
             ch=str[i];
             
             if(ch=='a'||ch=='e'||ch=='i'||ch=='o'||ch=='u'){
                 vowels++;
             }
         }

         cout<<"vowels"<<vowels;

         return 0;
     }
