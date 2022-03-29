# strings.cpp
#include <bits/stdc++.h>
using namespace std;

int main() {
	// your code goes here
	//upper case to lower case lower to upper case
	string s;
	cin>>s;
//	transform(s.begin(),s.end(),s.begin(),::tolower);
//	transform(s.begin(),s.end(),s.begin(),::toupper);
/*	for(int i=0;i<s.size();i++)
	{
	    if(s[i]>='a'&&s[i]<='z')
	    {
	        s[i]=s[i]-32;
	    }
	
//	for(int i=0;i<s.size();i++)
//	{
	    else if(s[i]>='A'&&s[i]<='Z')
	    {
	        s[i]=s[i]+32;
	    }
	}
**************************************************************************	*/
	//print the largest number from the given string
/*	sort(s.begin(),s.end());
	cout<<s<<endl;
	reverse(s.begin(),s.end());
	cout<<s;*/
	//or
	//sort(s.begin(),s.end(),greater<int>());
//*****************************************************************************************	
//how many times the char occours in the strings eg:yashwanth "a" occurs 2 times
/*int c=0;
cout<<m;
for(int i=0;i<s.size();i++)
{
    if(s[i]=='a')
    {
        c=c+1;
    }
}
cout<<c;*/

//********************************************************************************************
//string reverse and palindrome
/*string temp=s;
reverse(s.begin(),s.end());
if(s==temp)
cout<<"it is pallindrome";
else
cout<<"no";
*/


	
	
	
	
	//cout<<s;
	return 0;
}
