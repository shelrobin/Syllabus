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
  // 2016, January, 19
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
  // 2016, January, 26
  date: new Date(2016, 1, 26),
  agenda: [
  ]
};

syllabus.push(class2)
```

```javascript
var class3 = {
  // 2016, February, 2
  date: new Date(2016, 2, 2),
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

// 2016, February, 9
var class4 = new ClassRoomSession(new Date(2016, 2, 9), []);
```

```javascript
// 2016, February, 16
var class5 = new ClassRoomSession(new Date(2016, 2, 16), []);
```

```javascript
// 2016, February, 23
var class6 = new ClassRoomSession(new Date(2016, 2, 23), []);
```

```javascript
// 2016, March, 1
var class7 = new ClassRoomSession(new Date(2016, 3, 1), []);
```

```javascript
// 2016, March, 8
var class8 = new ClassRoomSession(new Date(2016, 3, 8), ["No Class"]);
```

```javascript
// 2016, March, 15
var class9 = new ClassRoomSession(new Date(2016, 3, 15), []);
```

```javascript
// 2016, March, 22
var class10 = new ClassRoomSession(new Date(2016, 3, 22), []);
```

```javascript
// 2016, March, 29
var class11 = new ClassRoomSession(new Date(2016, 3, 29), []);
```

```javascript
// 2016, April, 5
var class12 = new ClassRoomSession(new Date(2016, 4, 5), []);
```

```javascript
// 2016, April, 12
var class13 = new ClassRoomSession(new Date(2016, 4, 12), []);
```

```javascript
// 2016, April, 19
var class14 = new ClassRoomSession(new Date(2016, 4, 19), []);
```

```javascript
// 2016, April,
var final = new ClassRoomSession(new Date(), []);
```

