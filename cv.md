# Maksim Ustsinovich

### Software Engineer

---

### Contact information:

Location: Minsk, Belarus<br>
**E-mail:** maksimustsinovich@gmail.com<br>
**Telegram:** [@noname_nonamov](https://t.me/noname_nonamov)<br>
[**LinkedIn**](https://www.linkedin.com/in/maksim-ustsinovich-a82b12314)<br>

---

### Summary

As a software engineer student,
I am dedicated to developing a strong foundation in computer science and software development principles. 
I have experience with various development frameworks and tools. 
I am eager to apply my knowledge and skills to real-world problems and collaborate with others to design and implement
innovative software solutions. My goal is to become a skilled and versatile software engineer who can make a positive
impact in the industry.

---

### Education

- Bachelor degree in Computer Science <br>
  Belarusian State University of Informatics and Radio-electronics (2022-2026) <br>
  Faculty of Computer Systems and Networks

---

### Skills

- Java
- Spring Framework
- JavaScript
- TypeScript
- HTML
- CSS
- React
- Postgres
- Redis
- MongoDB
- Docker
- Git

---

### Languages

- **Russian** - Native
- **Belarusian** - Native
- **English** - B1

---

### Code examples

[**Reverse integer**](https://leetcode.com/problems/reverse-integer/description/)
Given a signed 32-bit integer x, return x with its digits reversed. 
If reversing x causes the value to go outside the signed 32-bit integer range [-231, 231 - 1], then return 0.
Assume the environment does not allow you to store 64-bit integers (signed or unsigned).

```java
class Solution {

    public int reverse(int x) {
        long reverse = 0;
        int temp;

        while (x != 0) {
            temp = x % 10;
            reverse = reverse * 10 + temp;
            x = x / 10;

            if (reverse > Integer.MAX_VALUE || reverse < Integer.MIN_VALUE) {
                return 0;
            }
        }

        return (int) reverse;
    }

}
```

---

### Pet-projects

[**Collaborative editor**](https://github.com/maksimustsinovich/collaborative-editor) - 4th semester coursework.
A web application using tokenized document access. Collaboration is achieved using web sockets.

#### Used technologies:

- Java
- Spring Framework
- Vite
- React
- TypeScript
- MongoDB