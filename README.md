# Greetings! This is Jack.
  [![Tech Blog Badge](http://img.shields.io/badge/-Tech%20blog-black?style=flat-square&logo=github&link=https://Jack-93.github.io/)](https://Jack-93.github.io/)
  [![Instagram Badge](https://img.shields.io/badge/Insta-ff8000?style=flat-square&logo=Instagram&link=https://www.instagram.com/zig_jack93/)](www.instagram.com/zig_jack93/)
  [![Gmail Badge](https://img.shields.io/badge/Gmail-d14836?style=flat-square&logo=Gmail&logoColor=white&link=mailto:worl5@korea.ac.kr)](mailto:worl5@korea.ac.kr)
  [![Sparrow's github stats](https://github-readme-stats.vercel.app/api?username=Jack-93)](https://github.com/Jack-93/github-readme-stats)
  
  <svg role="img" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><title>C++</title><path d="M22.394 6c-.167-.29-.398-.543-.652-.69L12.926.22c-.509-.294-1.34-.294-1.848 0L2.26 5.31c-.508.293-.923 1.013-.923 1.6v10.18c0 .294.104.62.271.91.167.29.398.543.652.69l8.816 5.09c.508.293 1.34.293 1.848 0l8.816-5.09c.254-.147.485-.4.652-.69.167-.29.27-.616.27-.91V6.91c.003-.294-.1-.62-.268-.91zM12 19.11c-3.92 0-7.109-3.19-7.109-7.11 0-3.92 3.19-7.11 7.11-7.11a7.133 7.133 0 016.156 3.553l-3.076 1.78a3.567 3.567 0 00-3.08-1.78A3.56 3.56 0 008.444 12 3.56 3.56 0 0012 15.555a3.57 3.57 0 003.08-1.778l3.078 1.78A7.135 7.135 0 0112 19.11zm7.11-6.715h-.79v.79h-.79v-.79h-.79v-.79h.79v-.79h.79v.79h.79zm2.962 0h-.79v.79h-.79v-.79h-.79v-.79h.79v-.79h.79v.79h.79z"/></svg>
  ## Worst To Better
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

