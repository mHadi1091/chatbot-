# chatbot-
my first project in cpp regarding the given unis assignments 
```
#include <iostream>
#include <string>
using namespace std;
int main(){
    //introduction from user
    string name;
    cout<<"hi user plzz introduce yourself!!"<<endl;
     cout<<"lets start with ur name -->:";
      cin>>name;
       cout<<"hi "<<name<<endl;
    // ask for more info
     cout<<"well "<<name<<" tell me more about yourself"<<endl;
      cout<<"lets start with your age"<<endl;
    int age;
     cout<<"tell me how old are you "<<name<<" :";
     cin>>age;
    if (age>=14){
        cout<<"ohh so your a teenager"<<endl;
    }
    else if (age>=20){
      cout<<"so your a grown adult"<<endl;
    } else 
       cout<<"ohh so your a kid"<<endl;
    // ask for nationality
    string national;
     cout<<"well "<<name<<" what's your nationality:";
      cin>>national;
        cout<<"good to hear about you indeed "<<national<<" is a great place.";
      //ask the permission to say something in their native language
      int lang;
      cout<<"what is ur native language"<<endl;
      cout<<"1.(urdu)"<<endl;
      cout<<"2.(punjabi)"<<endl;
      cout<<"3.(phusto)"<<endl;
      cout<<"4.(sindhi)"<<endl;
      cout<<"let me know ur language I wannan say hi"<<endl;
      cin>>lang;
      switch (lang){
          case 1: cout<<"آپ کیسے ہو (urdu)"<<endl;
          break;
          case 2: cout<<"تُسی کِدّاں ہو? (punjabi)"<<endl;
          break;
          case 3: cout<<"ستاسو څه یاست؟ (phusto)" <<endl;
          break;
          case 4: cout<<"توهان ڪيئن آهيو؟ (sindhi)"<<endl;
          break;
          default: cout<<"I dont know the language!!"<<endl;
          break;
      }

    return 0;

   }

//loop based game 

```
