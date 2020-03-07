# Vadzim Matskevich
## Contact Info:
* Email: vadim_belarusminsk@mail.ru
* Tel. number: +37529 5535316

## Summary: I want to get experience in commercial development and become a highly qualified developer. Clever, sharp, responsible, quickly acquires the information. 
## Skills: programming languages, software and tools – C#, HTML, CSS, JavaScript, MS Office.
## Code example:
```module.exports = function zeros(expression) {
  let array = expression.split('*');
  let num;
  let count_num;
  let fact; 
  let result = 0;
  let sumTwo = 0; 
  let sumFive = 0;
  for (let i = 0; i < array.length; i++) {
    if (array[i].search('!!') > 0) {
      num = array[i].replace('!!', '');
      fact = 2;
    } else {
      num = array[i].replace('!', '');
      fact = 1;
    }
    while (num != 0 && num != 1) {
      count_num = num;
      while (count_num % 2 === 0) {
       sumTwo++;
       count_num = count_num / 2;
      }
      while (count_num % 5 === 0) {
       sumFive++;
       count_num = count_num / 5;
      }
      num = num - fact;
    }
  }
  result = Math.min(sumTwo, sumFive);
  return result
}
```
## Experience: https://htmlacademy.ru/profile/id1195601 - HTML Basics, CSS Basics, JS.
## Education: BNTU, Power Engineer. I have been working as a design engineer for 9 years. Online learning оf programming courses on htmlacademy.ru (HTML, CSS, JS). 
## English: Pre-intermediate, study english on courses, study english on platforms Lingualeo, Duolingo my own.
