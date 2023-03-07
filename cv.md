# Pchelkin Roman
### Junior Frontend Developer

---

### Contact information:  
**Phone:** +7 (916) 037-2137  
**Email:** i@rpchelkin.ru  
**Telegram:** @vavilentar  
[GitHub](https://github.com/vavilentar)  
[LinkedIn](https://www.linkedin.com/in/vavilen/)  

---

### Skills and Proficiency:
+ HTML5, CSS3
+ JavaScript, JQuery, React Basics
+ Git, GitHub
+ VS Code
+ Figma, Adobe Photoshop

---

### Work experience:  
### Russian Television and Radio Broadcasting Network · Full-time  
### Moscow, Moscow City, Russia  
#### Web Developer
> Nov 2021 - Present · 1 yr 5 mos

+ Designed and developed dynamic web pages using HTML, CSS, and Javascript.
+ Worked on CSS background, CSS positioning, CSS text, CSS border, pseudo-classes, pseudo-elements.
+ Finding out the bugs, broken links and missing images etc. and rectifying them.
+ Creating modal windows, sliders, add content on sites. 
+ Using base Jquery and Bootstrap at my work.

#### Lead Engineer
> Apr 2016 - Present · 7 yrs  

+ Providing guidance on the use of the software
+ System testing/debugging
+ Assisting with setup and configuration of software
+ Diagnosing and fixing software configuration issues
+ Escalating urgent customer issues
+ Assisting in documentation – create knowledge-base articles, FAQs and how-to guides for the users of the software
+ Troubleshooting errors and resolving issues and questions from the employees
+ Document maintenance
+ Hardware maintenance


  
### Mostransavto · Full-time  
### Taldom, Russia  

#### System Engineer  
> Jul 2014 - Feb 2016 · 1 yr 8 mos  
  
+ Hardware maintenance
+ Maintenance of the navigation and video surveillance systems in public transport
+ Troubleshooting errors and resolving issues and questions from the employees
+ Technical support of workstations

---

### Code example:
**KATA from Codewars**: *Write a function, **persistence**, that takes in a positive parameter **num** and returns its multiplicative persistence, which is the number of times you must multiply the digits in **num** until you reach a single digit.*  
```javascript
function persistence(sum) {  
  let counter = 0, newSum = 0;  
  let myFunc = num => Number(num);  
  let sumArr = Array.from(String(sum), myFunc);  
  do {  
    if (sum >= 10) {  
        counter++;  
        newSum = sumArr.reduce((acc, rec) => acc * rec);  
        sumArr = Array.from(String(newSum), myFunc);  
    } else {  
        return 0;  
    }  

  } while (newSum >= 10);

  return counter;
}
```

---

### Courses:  
+ [Udemy](https://www.udemy.com/) JavaScript + React course
+ [Udemy](https://www.udemy.com/) Web-Developer course

---

### Languages:  
+ English - B1
+ Russian - Native  
