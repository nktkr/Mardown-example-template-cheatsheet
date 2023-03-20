# Mardown-example-template-cheatsheet
In this repo I store the frequently used markdown elements 


### Hidden output of program 

<details>
<summary>Output:</summary>

```bash
10  15.5
i  d
```

</details>
<br>


### code snippet C++

```cpp
#include<typeinfo>
#include<isostream>
using namespace std;

int main(){
  auto a = 10;  // here 10 is literal
  auto b = 15.5; // here literal is 15.5
  cout << a << "  " << b
  cout << typeid(a).name() << "  " << typeid(b).name();
  return 0;
}
```