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

1. Task: https://github.com/rolling-scopes-school/tasks/blob/master/tasks/cv/cv-stage0.md
2. Screenshot:
   ![](https://github.com/maksimustsinovich/rsschool-cv/blob/rsschool-cv-html/img.png?raw=true)
3. Deploy: https://chakapega-fancy-weather.netlify.com/
4. Done 07.07.2020 / deadline 08.07.2024
5. Score: 120/130
- [+] студент засабмитил в rs app ссылку на своё CV, задеплоенное на gh-pages +10
- [+] вёрстка валидная +10
- вёрстка семантическая +20
  - [+] header, main, footer +5
  - [+] элемент nav +5
  - [+] только один заголовок h1 +5
  - [+] заголовки h2 +5
- [+] в footer есть ссылка на гитхаб автора работы, год создания приложения, логотип курса со ссылкой на курс +10
- [+] для оформления СV используются css-стили +10
- [ ] при уменьшении масштаба страницы браузера вёрстка размещается по центру по горизонтали, а не сдвигается в сторону +0
- [+] на странице СV есть фото или аватарка автора, пропорции изображения не искажены, у изображения есть атрибут alt +10
- [+] навигация, контакты для связи и перечень навыков оформлены в виде списка ul > li или ul > li > a +10
- [+] Содержание CV +30
  - [+] краткую информацию о себе +5
  - [+] контакты для связи +5
  - [+] перечень навыков +5
  - [+] пример кода. Код добавляется при помощи символов и тегов, а не картинкой +5
  - [+] перечень выполненных учебных проектов со ссылками на исходный код или страницу приложения +5
  - [+] информацию об образовании и уровне английского +5
  - [+] CV выполнено на английском языке +10