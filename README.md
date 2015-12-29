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
  // 2016, January, 12 6PM
  date: new Date(2016, 0, 12, 18),
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
  // 2016, January, 19 6PM
  date: new Date(2016, 0, 19, 18),
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
  // 2016, January, 26 6PM
  date: new Date(2016, 0, 26, 18),
  agenda: undefined
};

syllabus.push(class2)
```

```javascript
var class3 = {
  // 2016, February, 2 6PM
  date: new Date(2016, 1, 2, 18),
  agenda: [
    "constructor functions"
  ]
};

syllabus.push(class3)
```

```javascript
// Takes in a date and an array of topics
// puts ClassRoomSession in syllabus
function ClassRoomSession (date, agenda) {
  this.date = date;
  this.agenda = agenda;

  syllabus.push(this);
};

// 2016, February, 9 6PM
var class4 = new ClassRoomSession(new Date(2016, 1, 9, 18), undefined);
```

```javascript
// 2016, February, 16 6PM
var class5 = new ClassRoomSession(new Date(2016, 1, 16, 18), undefined);
```

```javascript
// 2016, February, 23 6PM
var class6 = new ClassRoomSession(new Date(2016, 1, 23, 18), undefined);
```

```javascript
// 2016, March, 1 6PM
var class7 = new ClassRoomSession(new Date(2016, 2, 1, 18), undefined);
```

```javascript
// 2016, March, 8
// No class
var class8 = null;
syllabus.push(class8);
```

```javascript
// 2016, March, 15 6PM
var class9 = new ClassRoomSession(new Date(2016, 2, 15, 18), undefined);
```

```javascript
// 2016, March, 22 6PM
var class10 = new ClassRoomSession(new Date(2016, 2, 22, 18), undefined);
```

```javascript
// 2016, March, 29 6PM
var class11 = new ClassRoomSession(new Date(2016, 2, 29, 18), undefined);
```

```javascript
// 2016, April, 5 6PM
var class12 = new ClassRoomSession(new Date(2016, 3, 5, 18), undefined);
```

```javascript
// 2016, April, 12 6PM
var class13 = new ClassRoomSession(new Date(2016, 3, 12, 18), undefined);
```

```javascript
// 2016, April, 19 6PM
var class14 = new ClassRoomSession(new Date(2016, 3, 19, 18), undefined);
```

```javascript
// 2016, April,
var final = new ClassRoomSession(undefined, undefined);
```

