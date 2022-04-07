# Siarhei Muliarenka

### Contact information:

**Phone:** +375 (29) 517-79-98<br/>
**Email:** warwhisper@tut.by<br/>
[LinkedId](https://www.linkedin.com/in/sierhei-muliarenka-9a8163115)

---
### Briefly About Myself:
I having started my cariera as a programmer for SCADA-systems. I have developed the software for PC to control the chemical proсesses. Then I have cources of programming for PLC-controllers: Alan Bredlly and Siemens. At the same time I got some skills in C# - ASP.Net - SQL stack to develop some software for production goal.

Some times ago I've become passionate the Web Development . It provides you enless possibilities for develope anything you can imagine.

I believe, that my ability to learn and to gain new skills will lead me through this path of becoming a proficient Frontend Developer.

---

### Skills and Proficiency:
* HTML, CSS Basics
* Git, GitHub
* VS Code, Intellij IDEA
* Figma Basics
* C#, ASP.NET
* Transact SQL

---

### Code example:
**Create a function taking a positive integer as its parameter and returning a string containing the Roman Numeral representation of that integer**
Modern Roman numerals are written by expressing each digit separately starting with the left most digit and skipping any digit with a value of zero. In Roman numerals 1990 is rendered: 1000=M, 900=CM, 90=XC; resulting in MCMXC. 2008 is written as 2000=MM, 8=VIII; or MMVIII. 1666 uses each Roman symbol in descending order: MDCLXVI.
 
```
const solution = num => {
    const dec = [900,500,400,100,90,50,40,10,9,5,4,1];
    const rom = ['CM','D','CD','C','XC','L','XL','X','IX','V','IV','I'];

    let result = '';
    if (num >= 1000) {
        result = 'M'.repeat(num / 1000);
        num %= 1000;
    }
    return dec.reduce((result, item, i) => {
        while (num >= item) {
            result +=rom[i];
            num -= item;
        }
        return result;
    }, result);
};
```
### Languages:
* English - Pre Intermediate (B2)
* Russian - Native





