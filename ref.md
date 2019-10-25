## 引用
### __declspec(dllexport)
        函数导出声明
### 代码示范
* api.dll


动态库提供方
>api.h

```

#of def DLL_EXPORT 
    #define api_export __declspec(dllexport)
#else
    #define api_export __declspec(dllimport)
#endif
```
>api.c

```

#define DLL_EXPORT
#include "api.h"
api_export class Animal

{
    private:
        string animalName;
        int  animalAge;
    public:
        Anima& GetAge()
        {
            retrun age;
        }
};

class Bird: public Animal
{
    
};

api_export Animal& GetPeople(Build* data,Animal ref, Bird& o)
{
    return *this;
    Anima ff;
    return ff;
    return o;
};

int RandomNumber(int min, int max)
{
    return fun(min,max)
}
```

* 动态库调用方

api.h,
api.dll

```
api_export class Animal;

api_export Animal& GetPeople(Build* data,Animal ref, Build& o);

```
