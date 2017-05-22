## C++ notes
### Convert a String to an Int
`std::stoi( str )`

```c++
#include <iostream>

int main()
{
  char str[] = "35"; // example number is 35
  std::cout << std::stoi( str ) << std::endl; // 35
  return 0;
}
```

### Convert an Int to a String
#include <string>
std::string s = std::to_string(42);

```c++
#include <iostream>
#include <string>

int main()
{
  std::string s = std::to_string(42);
  std::cout << s << std::endl; // 42

  return 0;
}
```
