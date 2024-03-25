```c
#include <stdio.h>

typedef struct {
    const char* name;
    const char* studying;
    const char* learning;
} Hacker;

typedef struct {
    Hacker base;
} AboutMe;

typedef struct {
    Developer base;
    const char* languages[3];
    const char* tools[1];
} Skills;

int main() {
    AboutMe aboutMe;
    aboutMe.base.name = "Maiquel Paiva";
    aboutMe.base.studying = "Information Systems";
    aboutMe.base.learning = "Web Hacking";
}
```
