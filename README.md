# Greetings! This is introduction of me, Jack

  ## Worst To Better
  ## Lotto Is Best
 
* [My github Page] (https://jack-93.github.io/)
* [Instagram] (https://www.instagram.com/zig_jack93/)
```c

#include <iostream>
#include <time.h>
using namespace std;

int main(){
  int num[45]={};
  
  for(int i=0;i<45;i++){
    num[i]=i+1;
  }
    srand((unsigned int)time(0));
    int Temp,index1,index2;
    for (int i = 0; i < 100; i++)
    {
        index1 = rand() % 45;
        index2 = rand() % 45;
        temp = num[index1];
        num[index1]; = num[index2];
        num[index2]; = temp;
    }
    for (int i = 0; i < 5; i++)
    {
        cout << (i + 1) << "번째 번호 : " << num[i] << "\n";
    }
    cout << num[5] << "\n";
    
    return 0;
}
```

