# Programming basics syllabus

**Course:** [ArtG 2260](https://wl11gp.neu.edu/udcprod8/bwckctlg.p_disp_course_detail?cat_term_in=201630&subj_code_in=ARTG&crse_numb_in=2260)

**Instructor:** Francisco Dias

**Communication:** [artg2260st2016.slack.com](https://artg2260st2016.slack.com/messages/@slackbot/)

## Course Description

### Prerequisites

## Overview

# Syllabus
```javascript
var syllabus = [];

var class0 = {
  // 2016, January, 12
  date: new Date(2016, 1, 12),
  agenda: [
    "introductions",
    "Communication (slack)",
    "p5.js",
    "p5.js editor",
    "drawing",
    "github [wip]"
  ]
};
syllabus.push(class0)
```

```javascript
var class1 = {
  date: new Date(2016, 1, 19),
  agenda: [
    "variables",
    "scope",
    "functions"
  ]
};

syllabus.push(class1)
```

```javascript
var class2 = {
  date: new Date(2016, 1, 26),
  agenda: [
  ]
};

syllabus.push(class2)
```

```javascript
var class3 = {
  date: new Date(2016, 2, 2),
  agenda: [
    "constructor functions"
  ]
};

syllabus.push(class3)
```

```javascript
// Takes in a date and an array of topics then puts class in syllabus
function Class (date, agenda) {
  this.date = date;
  this.agenda = agenda;

  syllabus.push(this);
};

var class4 = new Class(new Date(2016, 2, 9), []);
```

```javascript
var class5 = new Class(new Date(2016, 2, 16), []);
```

```javascript
var class6 = new Class(new Date(2016, 2, 23), []);
```

```javascript
var class7 = new Class(new Date(2016, 3, 1), []);
```

```javascript
var class8 = new Class(new Date(2016, 3, 8), ["No Class"]);
```

```javascript
var class9 = new Class(new Date(2016, 3, 15), []);
```

```javascript
var class10 = new Class(new Date(2016, 3, 22), []);
```

```javascript
var class11 = new Class(new Date(2016, 3, 29), []);
```

```javascript
var class12 = new Class(new Date(2016, 4, 5), []);
```

```javascript
var class13 = new Class(new Date(2016, 4, 12), []);
```

```javascript
var class14 = new Class(new Date(2016, 4, 19), []);
```

```javascript
var final = new Class(new Date(), []);
```

