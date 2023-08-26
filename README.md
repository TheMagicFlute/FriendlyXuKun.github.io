<h1>Hello, I'm fine. And you?</h1>
<h2>If you happy, please smile.</h2>

```cpp
#include<iostream>
#include "myself.h"
using namespace std;
int main()
{
  string state;
  state = myself.my_state();
  if (state == "happy")
  {
    myself.smile("happily");
  }
  return 0;
}
```

