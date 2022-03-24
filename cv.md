# [rsschool-cv](https://github.com/Rarity110/rsschool-cv.git)
***
## TATSIANA KISIALEVICH
***
### Contact information:
* Phone: +375 33 3328622
* Email: rarity110@mail.ru
* GitHub: rarity110
***
### About myself
Nowadays I work as an economist at a bank. It’s a great job. But I always feel that I like automation of any task more than analysis of a paying capacity of companies. So I succesfully finished the stage 0 at RS School. And I'm excited about my learning at this school. I really want to realize myself as a developer.
***
### Skills
* HTML
* CSS
* JavaScript
* Figma
***
### Code example
```
function duplicateCount(text){
  let count = 0;  
  let lowwer_text = text.toLowerCase();
  let allredy_analized = '';
  for (let char of lowwer_text){
      if (allredy_analized.indexOf(char) == -1){
          let pos = -1;
          let count_letter = 0;
          while ((pos = lowwer_text.indexOf(char, pos + 1)) != -1) {
            count_letter++;
          }
          console.log(char + '  ' + count_letter + '  ' + allredy_analized);
          if (count_letter > 1) count++;
          allredy_analized = allredy_analized + char;
      }
  }
  return count 
}
```
***
### Experience
* 2004-Currently - Economist, bank
* 2022 [tic-tac-toe](https://rolling-scopes-school.github.io/rarity110-JSFEPRESCHOOL/tic-tac/) 
***
### Education
* 1999-2004 - Вelarus State Economic University, Finance and  Banking, economist
* 2022 - RS School, Course «JavaScript/Front-end. Stage 0»
* RS School, Course «JavaScript/Front-end. Stage 1» (in progress)
***
### Language
English level - A2
