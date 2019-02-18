# My-LaTeX
This repo includes my LaTeX documents.

#### Note to user:

User should CTRL + F `CHANGE ME` in `CKpremable.sty` and properly setup the figures directory.

### Changes from v18:

- Cleaned the code and deleted unnecessary cluttering macros
- Merged Crowdmark.sty and PrintedAssignment.sty into CKassignment.sty
- Various macros behave accordingly to specific class. i.e. if the class is specified as PMATH 351, then the figures path is automatically set to figures/pmath351 folder etc.

NOTE: Ideally, you should only use the packages you need for your document. For ease of use, I included most of the packages I use in my preamble. This is very practical but highly inefficient.

### Description of .sty files.

- **CKpreamble.sty**: Preamble for every document.
- CKassignment.sty: For assignments submitted via Crowdmark or printed assignments.
- CKlecture.sty: For lectures notes and exam practice.

### Description of .tex files.

- Crowdmark.tex: Template for assignments submitted by Crowdmark. [__CROWDMARK SAMPLE__](http://www.student.math.uwaterloo.ca/~c2kent/LectureNotes/templates/Crowdmark.pdf#page=7)
- PrintedAssignment.tex: Template for printed assignments or printed projects. [__PRINTED ASSIGNMENT SAMPLE__](http://www.student.math.uwaterloo.ca/~c2kent/LectureNotes/templates/PrintedAssignment.pdf#page=8)
- Lecture.tex: Template for lectures. [__LECTURE SAMPLE__](http://www.student.math.uwaterloo.ca/~c2kent/LectureNotes/templates/Lecture.pdf)
  - Conversion for class based notes: [__class based option__](http://www.student.math.uwaterloo.ca/~c2kent/LectureNotes/templates/LectureChapBased.pdf)
- ExamPractice.tex: Template for exam practice document. [__EXAM PRACTICE SAMPLE__](http://www.student.math.uwaterloo.ca/~c2kent/LectureNotes/templates/ExamPractice.pdf)
