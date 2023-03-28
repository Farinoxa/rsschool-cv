# **Sergey Farino**

#### _Software Engineer_

### _Contact Information:_

phone number: +37529-206 03 07;
e-mail: farino.sergey@gmail.com;
telegram: @fara_sg.

### _Personal profile_

- Experience in JavaScript and React
- Extensive experience in HTML5, CSS3 and ES5/6
- Performance optimization skills
- Always learning new technologies related to the Web
- Capable team player with good communication skills
- Responsible and focused on result

### _Core competencies_

JavaScript and React

### _Technical skills_

**OS Platforms:** Mac OS, Windows, Linux
**Languages and technologies:** JavaScript (ES5/ES6), React, HTML5, CSS3, SCSS
**VSC:** GIT
**Application Development Systems:** WebStorm, VS Code
**Automation Testing Tools:** Mocha, Chai, Jasmine, Sinon

### _Education_

Vitebsk State Medical University, Pharmaceutical Department

### _Code Sample_

```
function Content() {
  const { appliedFilter, setAppliedFilter, filtredArticles } =
    useArticleContext();
  const handleChipsChange = (currentCategory) => {
    if (appliedFilter.categories.includes(currentCategory)) {
      setAppliedFilter((filterValue) => ({
        ...filterValue,
        categories: appliedFilter.categories.filter(
          (chip) => chip !== currentCategory,
        ),
      }));
    } else {
      setAppliedFilter((filterValue) => ({
        ...filterValue,
        categories: [...appliedFilter.categories, currentCategory],
      }));
    }
};
```

### _Recent and major projects_

**[Blog la-Medium](https://farinoxa.github.io/blog-platform-la_medium/)**
**In Progress...**

### _English level_

Pre-Intermediate
