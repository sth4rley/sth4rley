
```cpp
sth@fedora~: cat whoami.cpp

#include <iostream>

class Me {
  public:
    Me(){};

    void sayHello() const {
      std::cout << "Welcome to my profile!\n";
  }

  public:
    std::string name = "Stharley";
    std::string age = "21";
    std::string skills = "Developer, Contestant";
    std::string tech = "Linux, Git, Python, C/C++, JavaScript";
    std::string extra = "x86_64 assembly";

  private:
    std::string secret = "Nothing Here...";
};

int main() {
  Me Stharley;

  Stharley.sayHello();

  return EXIT_SUCCESS;
}

```
