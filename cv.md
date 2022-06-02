# Sergei Marmysh
***
### Contact information:
* Phone: +375 25 971-30-01
* Discord: Viruss#6122
* Telegram: @Viruss13k
* E-mail: MarmyshMD@gmail.com
* [LinkedIn](https://www.linkedin.com/in/sergei-marmysh-870851232/)

***

### About me:
I am a practicing cardiac surgeon. Since 2010, I started to get involved in creating primitive sites using only HTML in CSS.
While studying at the medical university, I continued my hobby, and in 2012 I started learning PHP.

In 2016, I was selected for an internship at INTEXSOFT, which I could not complete, because. chose medicine.
Having been doing freelancing for the past few years, I decided to change direction and move from practical medicine to programming.

I hope that my ability to absorb large amounts of information will help me become a good Frontend developer.

***

### Skills:
| skills    	| low 	| medium 	| above average 	| god level 	|
|---------------|-------|-----------|-------------------|---------------|
| HTML      	|     	|    +   	|       +       	|           	|
| CSS       	|     	|    +   	|       +       	|           	|
| BOOTSTRAP 	|     	|    +   	|       +       	|           	|
| PHP       	|     	|    +   	|               	|           	|
| JQ        	|     	|    +   	|               	|           	|
| JS        	|  +  	|        	|               	|           	|
| lua       	|  +  	|        	|               	|           	|
| Larawel   	|  +  	|        	|               	|           	|
| SASS/LASS 	|  +   	|        	|               	|           	|

***

### Code example:
**Duplicate Encoder (CODEWARS):** _The goal of this exercise is to convert a string to a new string where each character in the new string is "(" if that character appears only once in the original string, or ")" if that character appears more than once in the original string. Ignore capitalization when determining if a character is a duplicate._
```
function duplicateEncode(word){
    let str = word.toLowerCase();
    let result = '';
    for (let i = 0; i < str.length; i++) {
        (str.indexOf(str[i]) === str.lastIndexOf(str[i])) ? result += '(' : result += ')';
    }
    return result;
}
```

**Invert values (CODEWARS):** _Given a set of numbers, return the additive inverse of each. Each positive becomes negatives, and the negatives become positives._
```
function invert(array) {
    let resultArray = [];
    for (let i = 0; i < array.length; i++) {
        (array[i] > 0) ? resultArray[i] = array[i] * -1 : resultArray[i] = array[i] * -1;
    }
    return resultArray;
}
```

**Abbreviate a Two Word Name (CODEWARS):** _Write a function to convert a name into initials. This kata strictly takes two words with one space in between them. The output should be two capital letters with a dot separating them._
```
function abbrevName(name){
    let nameArray = name.trim().split(' ');
    let initialsArray = [];
    for (i = 0; i < nameArray.length; i++) {
        initialsArray[i] = nameArray[i][0];
    }
    let result = initialsArray.join('.').toUpperCase();
    return result;
}
```

***

### Education and courses:
1. Internship PHP developer, IntexSoft 2016
2. Front End Developer, TeachMeSkills (start jule 2022)
3. JS, CSS, HTML, Git video courses on YouTube
4. HTML academy [https://htmlacademy.ru/courses]
5. Codecademy [https://www.codecademy.com/learn/learn-html]
6. \[Udemy] The Complete JavaScript Course + React 2021 (online)
7. \[WebForMySelf] Bootstrap Framework, Responsive Layout Practice from A to Z (online)
8. Laravel framework. Zero to Pro (online)


### Languages:
* **Russian** - _native speaker_
* **English** - _elementary_