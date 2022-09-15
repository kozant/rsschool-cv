# Anton Kazlou

## Contact information:

* **Email:** anton.s.kazlou@gmail.com
* **Phone:** +375 (29) 831-20-18
* **Telegram:** [@antonkozlovv](https://t.me/antonkozlovv)
* **LinkedIn:** [anton-kazlou](https://www.linkedin.com/in/anton-kazlou-081838134)
* **Discord:** Anton Kazlou (@kozant)

## About Me

I started my career as a frontend developer in a small minsk company less than two years ago. I'm working on one big project and since I'd started I increased my html, css, js, sql skills. But sometimes I have some doubts about the quality of those skills. I don't cover all aspects of my profession. So i decided to take rss courses to improve my skills; it's something like recertification for me.

## Skills

* HTML
* CSS
* JavaScript, ReactJS, Redux, flow, styled-components, reselect
* SQL
* SVN
* VS Code

## Code example

**Count the number of Duplicates** 

Write a function that will return the count of **distinct case-insensitive** alphabetic characters and numeric digits that occur more than once in the input string. The input string can be assumed to contain only alphabets (both uppercase and lowercase) and numeric digits.

```
function duplicateCount(text){
  const stringArray = text.split("");
  if (!stringArray.length) return 0;
  let arrayOfDuplicates = [];
  for (let i = 0; i < stringArray.length; i++) {
    if (arrayOfDuplicates.includes(stringArray[i].toLowerCase())) continue;
    for (let j = i; j < stringArray.length - 1; j++) {
      if (stringArray[i].toLowerCase() === stringArray[j + 1].toLowerCase()) {
        arrayOfDuplicates.push(stringArray[i].toLowerCase());
        break;
      }
    }
  }
  return arrayOfDuplicates.length
}
```

## Experience

**Frontend-developer**   
Imbue Systems · Full-time  
Dec 2020 - Present · 1 yr 10 mos

Project - [Handle by CustomerTRAX](https://customertrax.com/)

## Education

* **Belarusian State University (2016 - 2020)**
 + Faculty of Mechanics and Mathematics
   - Speciality: Mathematics and Information Technologies (Web-Programming and Internet Technologies
   
* There were some js courses, but I don't have information about them; you just only have my word :)

## English

B1. I practice English with a tutor.