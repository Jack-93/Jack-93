# Greetings! This is Jack.

  [![Tech Blog Badge](http://img.shields.io/badge/-Tech%20blog-black?style=flat-square&logo=github&link=https://Jack-93.github.io/)](https://Jack-93.github.io/)
  [![Instagram Badge](https://img.shields.io/badge/Insta-ff8000?style=flat-square&logo=Instagram&link=https://www.instagram.com/zig_jack93)](www.instagram.com/zig_jack93)
  [![Gmail Badge](https://img.shields.io/badge/Gmail-d14836?style=flat-square&logo=Gmail&logoColor=white&link=mailto:worl5@korea.ac.kr)](mailto:worl5@korea.ac.kr)
  
  [![Sparrow's github stats](https://github-readme-stats.vercel.app/api?username=Jack-93)](https://github.com/Jack-93/github-readme-stats)
  
  ---------------------
  
  ![C++ Badge](https://img.shields.io/badge/C++-blue.svg?&style=for-the-badge&logo=c%2B%2B&logoColor=white)
  ![Python](https://img.shields.io/badge/Python-3776AB.svg?&style=for-the-badge&logo=Python&logoColor=white)
  
  ![HTML5](https://img.shields.io/badge/HTML5-E34F26.svg?&style=for-the-badge&logo=HTML5&logoColor=white)
  ![CSS3](https://img.shields.io/badge/CSS3-157286.svg?&style=for-the-badge&logo=CSS3&logoColor=white)
  ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E.svg?&style=for-the-badge&logo=JavaScript&logoColor=white)
  
  ---------------------
  
  
  

  ## Lotto Is Best
```c

#include <iostream>
using namespace std;

int main(){
  int num[45]={};

  for(int i=0;i<45;i++){
    num[i]=i+1;
  }
    int temp,index1,index2;
    for (int i = 0; i < 100; i++)
    {
        index1 = rand() % 45;
        index2 = rand() % 45;
        temp = num[index1];
        num[index1] = num[index2];
        num[index2] = temp;
    }
    for (int i = 0; i < 6; i++)
    {
        cout << (i + 1) << "번째 번호 : " << num[i] << "\n";
    }
    cout << "이번 주 로또 번호는 !: "<< num[0] << ", " << num[1] << ", " << num[2] << ", " << num[3] << ", "
     << num[4] << ", " << num[5] << "\n";
    return 0;
}
```

