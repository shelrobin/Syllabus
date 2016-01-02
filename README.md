# Programming basics syllabus

- [Catalog description](#catalog-description)
- [About this course](#about-this-course)
- [communication](#communication)
- [Format](#format)
- [Grading](#grading)
- [Assignments](#assignments)
- [References](#references)
- [Schedule](#schedule)
- [Collaboration, original work and use of 3rd party source code](#collaboration-original-work-and-use-of-3rd-party-source-code)
- [Mobile phones, texting, instant messaging, email, social media, web browsing](#mobile-phones-texting-instant-messaging-email-social-media-web-browsing)
- [Attendance](#attendance)
- [Laptop and software requirements](#laptop-and-software-requirements)
- [Disabilities statement](#disabilities-statement)
- [Trace](#trace)

# Catalog description
[ArtG 2260](https://wl11gp.neu.edu/udcprod8/bwckctlg.p_disp_course_detail?cat_term_in=201630&subj_code_in=ARTG&crse_numb_in=2260): This course exposes students to basic programming design for user interfaces. Offers students an opportunity to become familiar with the logical elements of programming languages. Through lectures, hands-on in-class exercises, and modular projects, explores Web-based design and programming solutions for managing interaction and animation.

# About this course
You will become familiar with the process of programming in a creative context. The power of computational media will be revealed through examination of code and data as a medium for creative expression. The final project will allow you to explore a specific area of interest. You will develop basic fluency in programming and enhance your analytical thinking skills. The main platform used in the course will be P5.js, a simple, flexible yet powerful development environment and JavaScript framework based on Processing. Once we have established a solid foundation we will explore other web based JavaScript libraries, what you can use in browser, digital product development and cover the basics of server-side js development (Node.js).

# Communication
Communication will take place over two channels:
- [Slack](https://artg2260st2016.slack.com/messages/@slackbot/)
- [Github](https://github.com/ArtG2260SpringTuesday2016)
There is a slack room and [Github repository](http://readwrite.com/2013/09/30/understanding-github-a-journey-for-beginners-part-1) pertaining to each class and assignement where you will be able to ask specific questions based on that subject matter.

You'll also be able to reach out directly to the instructor, [Francisco](https://artg2260st2016.slack.com/messages/@francisco) for live help.

There are no standing office hours (as the instructor does not have an office) but time will be made available as needed.

# Format
This is a project-based, hybrid lecture/studio course. Class meetings will start each week with a presentation introducing the topic of the week and reviewing the programming exploration assigned the previous week. The balance of class time will consist of instructor-led hands-on exercises and/or independent work.

# Grading
Within 14 days after an assignment is due, grades will be posted. I will place a grading sheet in the assignment cloud folder. If you have any questions about how your grade was determined, don’t hesitate to make an appointment. The overall grade you earn in this course will be based on the following:
- 10% Active participation in presentation, discussion, and workshop sessions
- 10% Help contribution in the class repository (issues, branches, notes).
- 40% Programming assignments
- 40% Final project

# Assignments
Assignments will be handed in two stages. First a pull request will be submitted on a private repository assigned to each student by the end of Sunday before class mentioning [@frandias](https://github.com/frandias). They will then get feedback on that pull request (Sunday/Monday/Tuesday) and then have until the end of Wednesday to make corrections and mention [@frandias](https://github.com/frandias) again to submit their assignement. A pull request alone, commits or an edited comment will not be taken as proof of when work occured.

If a pull request is submitted earlier than Sunday it'll get reviewed earlier (think of it like asking for help) but does not have to be complete, a complete PR is still expected on Sunday. **So it is advantageous to try to work on/finish assignments earlier as you will be able to take advantage of more help**

# References
- [Daniel Shiffman](http://shiffman.net/)
  - [Nature of code: Simulating Natural Systems in Proccessing (advanced)](http://smile.amazon.com/Nature-Code-Simulating-Natural-Processing/dp/0985930802/ref=sr_1_2?ie=UTF8&qid=1451709164&sr=8-2&keywords=Daniel+shiffman)
  - [p5.js tutorial Foundations of programming](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA) Videos
  - [p5.js tutorial HTML/CSS/DOM](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6bI1SlcCRfLH79HZrFAtBvX)
  - [p5.js tutorial Working with Data](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6a-SQiI4RtIwuOrLJGnel0r)
  - [p5.js tutorial additional topics](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6ZmA-d3D0iFIvgrB5_7kB8H)
- Marjin Haverbeke
  - [Eloquent JavaScript](http://eloquentjavascript.net/)
- John Ducket
   - [HTML and CSS: Design and Build Websites. John Wiley & Sons, 2011](http://smile.amazon.com/JavaScript-JQuery-Interactive-Front-End-Development/dp/1118531647/ref=sr_1_1?s=books&ie=UTF8&qid=1451709553&sr=1-1&keywords=john+Ducket) [PDF](http://wtf.tw/ref/duckett.pdf)
   - [JavaScript and jQuery: Interactive Front-End Web Development.](http://smile.amazon.com/HTML-CSS-Design-Build-Websites/dp/1118008189/ref=sr_1_2?s=books&ie=UTF8&qid=1451709553&sr=1-2&keywords=john+Ducket)
- [Lauren McArthy](http://lauren-mccarthy.com/)
  - [Getting started with p5.js: Making Interactive Graphics in JavaScript](http://smile.amazon.com/Getting-Started-p5-js-Interactive-JavaScript/dp/1457186772?sa-no-redirect=1)

# Schedule
You should try copying and pasting this into the console in [web inspector](https://developers.google.com/web/tools/chrome-devtools/?hl=en) (not just chrome) and playing around with the `syllabus` [array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array).

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
    "Github"
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


# Collaboration, original work and use of 3rd party source code
For your code exploration assignments and project work you are expected to write original code. You must be able to explain how your program functions whenever asked. It is acceptable and encouraged to seek design, coding, and debugging assistance from other students, staff, or faculty in order to complete your work. Likewise, you are encouraged to help other students whenever possible. You are encouraged to study and learn from code examples. You may use third-party libraries to simplify coding, however, grading is based on the functionality of your original code (in compliance with their licence) along with the clarity of your comments and documentation. Whenever you incorporate third-party open source materials in your work you must properly attribute the works. Any student submitting work that can be reasonably believed to not be their own will be reported to the Office of Student Conduct and Complaint Resolution according to the Northeastern University Academic Integrity Policy.

# Mobile phones, texting, instant messaging, email, social media, web browsing
We're all adults here. The class is for your benefit. Use good judgement. We will have breaks during class where you'll have time to attend whatever you need.

# Attendance
You are expected to attend every class on time. I will intentionally wait 5 minutes after the class start time to begin the session to give people a couple extra minutes of buffer.

Three unexcused absences will result in a failing grade, as will chronic lateness. If you are going to be absent or late, please, at the very least, email me. Per University policy, excused absences must be documented. Except for extreme emergencies (you are in an ambulance), do not expect to receive an excused absence if you email me during or after class.

# Laptop and software requirements
You must bring your laptop to all class meetings fully-charged and ready to roll. A student-owned laptop is necessary for all students to complete assignments and projects. Generally, Apple laptops are the standard for most majors in Art + Design, however, Windows computers are also suitable.

More details related to the laptop requirement at http://www.neu.edu/camd/artdesign/about/laptop-software-fonts/.

The importance of backing up files cannot be stressed enough. I suggest using dropbox.

If you don’t have a laptop and purchasing one now presents a hardship, or if your laptop is broken and out for repairs and you need one to use in class, contact Chris Franson, College of Arts, Media and Design Technical Director, with questions via email to c.franson@neu.edu or call 617-373-7168.

# Disabilities statement
Northeastern University strives to provide academic accommodations to students with documented disabilities. Accommodations are approved by the Disability Resource Center at 20 Dodge Hall. Students need to register with the DRC and bring their instructors a letter from that office stating approved accommodations. If you will be requesting accommodations in this class, please let the instructor know as soon as possible to avoid delays. Visit http://www.drc.neu.edu for more information.

# Trace
Your participation in the Teacher Rating and Course Evaluation (TRACE) survey is expected.



