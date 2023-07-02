### [rsschool-cv](rsccool-cv)


#  Roman Lobovikov
#### Junior Frontend Developer
---
## Contact Info

* **Location:** Russia, Izhevsk
* **E-mail:** [camomile.one@gmail.com](camomile.one@gmail.com)
* **GitHub:** [camomileOne](https://github.com/camomileOne/)
* [Telegram](https://t.me/IZH_Roman_Lobovikov)
* [LinkedIn](https://www.linkedin.com/in/roman-lobovikov-1850a327/)


## Self Introduction

I'm patient and hardworking person. I desperately want to become a Web Developer. I'm currently taking a preparatory course «JavaScript/Front-end. Stage 0» at RS School.

## Skills

* HTML, CSS
* **Programming languages:** JavaScript, Python, C, C++, C#

## Code example
This is a solution of problem given in my University. You have to find Amicable numbers in given range using C language.

```c
#include <stdio.h>
#include <stdlib.h>

#define SIZE 14

int getSumOfDivisors(int n) {
    int sum = 1;
    int i = 2;
    for (; i < n / i; i++) {
        if (n / i * i == n) {
            sum += i + n / i;
        }
    }
    if (i * i == n)
        sum += i;
    return sum;
}

int main() {
    system("chcp 1251");
    system("cls");
    
    int m, n;
    char input[SIZE] = "";
    printf("Введите строку:\n");
    fgets(input, SIZE, stdin);
    printf("Размер буфера до отсечения строки: %zu\n", sizeof(input));
    input[2] = '\0';
    printf("Размер буфера после отсечения строки: %zu\n", sizeof(input));
    printf("Строка после отсечения: %s\n", input);
    (void) sscanf_s(input, "%d %d", &m, &n);
    int k = 0;
    for (; m <= n; ++m) {
        k++;
        int m2 = getSumOfDivisors(m);
        if (m < m2 && m2 <= n && m == getSumOfDivisors(m2)) {
            printf("%d %d\n", m, m2);
        }
        if (k == 100000) {
            break;
        }
    }
    printf("%d\n", m);
    printf("%d\n", m);
    (void) getchar();
}
```
## Education

Bachelor of **Software Engineering** in Izhevsk State Technical University

## Experience

I've complited several Online courses (HTML, CSS, JavaScript, etc.). Here it is my C# certificate:
[<img align="center" alt="C# Certificate" width="100px"  src="img/cert.png" />](https://rs.school/) 

## Languages

- Russian - native
- English - Intermediate (CEFR B1)
