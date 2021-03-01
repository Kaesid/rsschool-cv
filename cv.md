## Personal details

### Alexander Bobikov

Samara

keskaesid@gmail.com

https://github.com/Kaesid

Discord: Kaesid#5240

## Personal Profile Statement

Highly motivated, responsible and dedicated mathematician/system programmer looking for opportunity to improve his professional skills and JavaScript knowledge.

## Skills

- Creo Parametric 4.0
- Option File Generator/FIL Editor
- Java
- JavaScript

## Examples of code

#### JavaScript

```javascript
"use strict";

const min = function (arr) {
  if (arr === undefined || +arr === 0) return 0;
  let a = [];
  typeof arr !== "object" ? (a = Array.from(arguments)) : (a = arr);
  return a.sort((x, y) => x - y)[0];
};

const max = function (arr) {
  if (arr === undefined || +arr === 0) return 0;
  let a = [];
  typeof arr !== "object" ? (a = Array.from(arguments)) : (a = arr);
  return a.sort((x, y) => y - x)[0];
};

const avg = function (arr) {
  if (arr === undefined || +arr === 0) return 0;
  let a = [];
  typeof arr !== "object" ? (a = Array.from(arguments)) : (a = arr);
  return a.reduce((a, b) => a + b, 0) / a.length;
};
```

#### FIL:

```
CIMFIL/ON,MODE
DMY=POSTF(20)
TYPMOD=POSTF(7,4)
CASE/TYPMOD
	WHEN/ICODEF(MILL)
		FLMOD=0
		DMY=POSTF(2,1,25,4)
		XX = POSTF(2,3,486,1)
		DMY=POSTF(3,3,(355+7))
		DMY=POSTF(3,3,(355+24))
		DMY=POSTF(3,3,(355+25))
		DMY=POSTF(3,3,(355+26))
	WHEN/ICODEF(TURN)
		FLMOD=1
		XX = POSTF(2,3,486,2)
		DMY=POSTF(2,1,25,53)
		DMY=POSTF(3,3,(355+7))
		DMY=POSTF(3,3,(355+24))
		DMY=POSTF(3,3,(355+26))
ENDCAS
CIMFIL/OFF
```

## Education

#### Education and Training

2018 Professional development course: “Mentoring practice in industrial sector”. «Учебный центр Курс».

2014 Professional development course: “Modern metalworking systems with program control”. Samara State Aerospace University.

2008–2013 Applied mathematics. Samara State Aerospace University. Master degree.

## Employment and work experience

#### Employment history

Jun 2013 – Present Engineer-mathematician АО РКЦ «Прогресс»

Main duties performed:

- Mentoring and training new staff members;
- Developing and maintaining program products in industrial sector;
- 3D modeling in Creo Parametric 4.0;
- Developing projects in Option File Generator/FIL Editor;
- Developing external applications for projects;
- Maintaining project’s authorization system;
- Preparing, revising and maintaining software documentation;

## English level

B1
